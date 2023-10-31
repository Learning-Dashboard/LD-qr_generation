# LD-qr_generator ![](https://img.shields.io/badge/License-Apache2.0-blue.svg)
Component generationg quality requirements (QR) candidates.

## Main Functionality
LD-qr_generator software component is a library responsible of the suggestion of quality requirements based on the results of the alerts component. These components use the external tool PABRE-WS to identify potential quality requirements patterns that can address the quality issue raised by some alerts. This library is integrated in [LD-learning-dashboard](https://github.com/Learning-Dashboard/LD-learning-dashboard).

## Technologies
| Property | Description |
| -------------------- | ---------------|
| Type of component    | Library        |
| Build                | .jar           |
| Programming language | Java           |
| Frameworks           | Gradle         |
| External libraries   | Retrofit, GSON |

## How to build
This is a Gradle project. You can use any IDE that supports Gradle to build it, or alternatively you can use the command line using the Gradle wrapper with the command *__gradlew__* if you don't have Gradle installed on your machine or with the command *__gradle__* if you do, followed by the task *__jar__*.

```
# Example: using Gradle wrapper to build with dependencies
cd LD-qr_generation
gradlew jar
```
After the build is done the JAR file can be found at the __build/libs__ directory

## Documentation
You can find the user documentation in the repository [Wiki](https://github.com/Learning-Dashboard/LD-qr_generation/wiki) and the technical documentation of the API [here](https://learning-dashboard.github.io/LD-qr_generation/).

## Licensing
Software licensed under the Apache License, Version 2.0 (the "License"); you may not use this file except in compliance with the License. You may obtain a copy of the License at [http://www.apache.org/licenses/LICENSE-2.0](http://www.apache.org/licenses/LICENSE-2.0)
 
Unless required by applicable law or agreed to in writing, software distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the License for the specific language governing permissions and limitations under the License.

## Contact
For problems regarding this component, please open an issue in the [issues section](https://github.com/Learning-Dashboard/LD-qr_generation/issues).
