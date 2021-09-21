# Demo Java unit test using gradle only without TestNg / JUnit / Other testing frameworks
Проект примеров тестирования Java-класса сценарием Gradle
## Предварительные требования
- OS macOS Big Sur / Linux Ubuntu 20.04 / Другие современные настольные OS (не проверено)
- JDK 11
- Gradle 7.1
## Скачивание и запуск
- скачать:

**git clone** https://github.com/YuriiTrofimenko/demo-java-testing-gradle-only.git

- компилировать классы для тестирования:

**./gradlew compileJava --info**

- запустить тесты на основе сценария сборки:

**./gradlew** generatorTest **--info**

## Показаны техники:
- создания пользовательской задачи gradle
- загрузки класса из тестируемого проекта в сценарий gradle
- модульного тестирования класса из тестируемого проекта в сценарии gradle