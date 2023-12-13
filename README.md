# autoBot
AutoBot is a comprehensive framework designed for seamless automation of API, web and mobile testing, featuring support for BDD, DDT , with a wealth of reusable functions.
# Test Automation Instructions

This test automation framework is designed to ensure the robust testing of any software
applications across three distinct platforms. Leveraging the power of the TestNG framework and enhancing it with
Cucumber(optional), our testing suite guarantees efficient and reliable automated testing. Our aim is to streamline the testing
process and maintain high-quality standards, ensuring the seamless functionality of our applications across multiple
platforms.

## Table of Contents

- [SoftwareComponents](#SoftwareComponents)
- [AutomationTestSetupRules](#AutomationTestSetupRules)
### SoftwareComponents

| Component                 | Version | Usage                                   | URL                                                                                     |
|---------------------------|---------|-----------------------------------------|-----------------------------------------------------------------------------------------|
| Gradle                    | 7.4     | Build Tool                              | [Gradle](https://gradle.org/install/)                                                   |
| Java                      | 17      | Java JDK                                | [Java 17](https://www.oracle.com/java/technologies/javase/jdk17-archive-downloads.html) |
| Selenium                  | 4.2.4   | Core Web Automation Library             | Auto-downloaded through build.gradle                                                    |
| TestNG                    | 7.7.1   | Core Library to Invoke Tests            | Auto-downloaded through build.gradle                                                    |
| Extent Reports/aventstack | 5.0.9   | To Generate Reports                     | Auto-downloaded through build.gradle                                                    |
| Eclipse/IntelliJ          | Latest  | IDE                                     | [Eclipse/IntelliJ](https://www.jetbrains.com/idea/download/)                            |
| Appium                    | 8.1.1   | Mobile Automation                       | [Appium](http://appium.io/)                                                             |
| GitBash                   | Latest  | For Git Shell                           | [GitBash](https://git-scm.com/downloads)                                                |
| GitHub Desktop            | Latest  | Git UI: For easy use of git navigations | [GitHub Desktop](https://desktop.github.com/)                                           |

### AutomationTestSetupRules

1. Clone Project from [https://github.com/Wolverine-karthick/testorg.git](https://github.com/Wolverine-karthick/testorg.git)
2. Launch Intellij and Import project as Gradle Project
3. Download Chrome Driver from below path and add it to src/test/resources/Utilities
   https://chromedriver.chromium.org/downloads
4. Download FireFox Driver from below path and add it to src/test/resources/Utilities
   https://github.com/mozilla/geckodriver/releases
5. Build the Project "gradle clean build"
6. If you are running for mobile, add .apk/.app/.ipa to src/test/resources/Utilities
8. Generate code by performing task : 'gradle task codeGen'
