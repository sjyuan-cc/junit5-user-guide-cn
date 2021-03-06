{% assign junit-team = 'https://github.com/junit-team' %}
{% assign junit5-samples-repo = junit-team | append: '/junit5-samples' %}
{% assign junit5-repo = junit-team | append: '/junit5' %}
{% assign current-branch = junit5-repo | append: '/tree/' | append: release-branch %}

{% assign javadoc-root = 'https://junit.org/junit5/docs/' | append: docs-version | append: '/api' %}                

{% assign snapshot-repo = 'https://oss.sonatype.org/content/repositories/snapshots' %}

{% assign DisabledCondition = '[DisabledCondition](' | append: current-branch | append: '/junit-jupiter-engine/src/main/java/org/junit/jupiter/engine/extension/DisabledCondition.java)' %}
{% assign RepetitionInfoParameterResolver = '[RepetitionInfoParameterResolver](' | append: current-branch | append: '/junit-jupiter-engine/src/main/java/org/junit/jupiter/engine/extension/RepetitionInfoParameterResolver.java)' %}
{% assign TestInfoParameterResolver = '[TestInfoParameterResolver](' | append: current-branch | append: '/junit-jupiter-engine/src/main/java/org/junit/jupiter/engine/extension/TestInfoParameterResolver.java)' %}
{% assign TestReporterParameterResolver = '[TestInfoParameterResolver](' | append: current-branch | append: '/junit-jupiter-engine/src/main/java/org/junit/jupiter/engine/extension/TestReporterParameterResolver.java)' %}
{% assign CustomTypeParameterResolver = '[CustomTypeParameterResolver](' | append: current-branch | append: '/junit-jupiter-engine/src/test/java/org/junit/jupiter/engine/execution/injection/sample/CustomTypeParameterResolver.java)' %}
{% assign CustomAnnotationParameterResolver = '[CustomAnnotationParameterResolver](' | append: current-branch | append: '/junit-jupiter-engine/src/test/java/org/junit/jupiter/engine/execution/injection/sample/CustomAnnotationParameterResolver.java)' %}
{% assign RandomParametersExtension = '[RandomParametersExtension]('| append: junit5-samples-repo | append: '/tree/' | append: release-branch | append: '/junit5-jupiter-extensions/src/main/java/com/example/random/RandomParametersExtension.java)' %}
{% assign junit5-jupiter-starter-gradle-kotlin = '[junit5-jupiter-starter-gradle-kotlin]('| append: junit5-samples-repo | append: '/tree/' | append: release-branch | append: '/junit5-jupiter-starter-gradle-kotlin)' %}
{% assign junit5-jupiter-starter-gradle-groovy = '[junit5-jupiter-starter-gradle-groovy]('| append: junit5-samples-repo | append: '/tree/' | append: release-branch | append: '/junit5-jupiter-starter-gradle-groovy)' %}
{% assign junit5-jupiter-starter-gradle = '[junit5-jupiter-starter-gradle]('| append: junit5-samples-repo | append: '/tree/' | append: release-branch | append: '/junit5-jupiter-starter-gradle)' %}
{% assign junit5-jupiter-starter-maven = '[junit5-jupiter-starter-maven]('| append: junit5-samples-repo | append: '/tree/' | append: release-branch | append: '/junit5-jupiter-starter-maven)' %}
{% assign junit5-jupiter-starter-ant = '[junit5-jupiter-starter-ant]('| append: junit5-samples-repo | append: '/tree/' | append: release-branch | append: '/junit5-jupiter-starter-ant)' %}
{% assign api-package = '[org.junit.jupiter.api](' | append: javadoc-root | append: '/org/junit/jupiter/api/package-summary.html)' %}


{% assign StackOverflow = '[Stack Overflow](https://stackoverflow.com/questions/tagged/junit5)' %}
{% assign Gitter = '[Gitter](https://gitter.im/junit-team/junit5)' %}                     
{% assign API = '[@API](https://apiguardian-team.github.io/apiguardian/docs/current/api/)' %}
{% assign API_Guardian = '[@API Guardian](https://github.com/apiguardian-team/apiguardian)' %}
{% assign AssertJ = '[AssertJ](http://joel-costigliola.github.io/assertj/)' %}
{% assign Hamcrest = '[Hamcrest](http://hamcrest.org/JavaHamcrest/)' %}
{% assign Log4j = '[Log4j](https://logging.apache.org/log4j/2.x/)' %}
{% assign Log4j_JDK_Logging_Adapter = '[Log4j JDK Logging Adapter](https://logging.apache.org/log4j/2.x/log4j-jul/index.html)' %}
{% assign Logback = '[Logback](https://logback.qos.ch/)' %}
{% assign LogManager = '[LogManager](https://docs.oracle.com/javase/8/docs/api/java/util/logging/LogManager.html)' %}
{% assign MockitoExtension = '[MockitoExtension](https://github.com/mockito/mockito/blob/release/2.x/subprojects/junit-jupiter/src/main/java/org/mockito/junit/jupiter/MockitoExtension.java)' %}
{% assign SpringExtension = '[SpringExtension](https://github.com/spring-projects/spring-framework/tree/master/spring-test/src/main/java/org/springframework/test/context/junit/jupiter/SpringExtension.java)' %}
{% assign Specsy = '[Specsy](http://specsy.org/)' %}
{% assign Truth = '[Truth](http://google.github.io/truth/)' %}
{% assign JUL_to_SLF4J_Bridge = '[JUL to SLF4J Bridge](https://www.slf4j.org/legacy.html#jul-to-slf4j)' %}


{% assign junit-platform-console = '[junit-platform-console](' | append: javadoc-root | append: '/org/junit/platform/console/package-summary.html)' %}
{% assign junit-platform-launcher = '[junit-platform-launcher](' | append: javadoc-root | append: '/org/junit/platform/launcher/package-summary.html)' %}
{% assign junit-platform-engine = '[junit-platform-engine](' | append: javadoc-root | append: '/org/junit/platform/engine/package-summary.html)' %}
{% assign junit-vintage-engine = '[junit-vintage-engine](' | append: javadoc-root | append: '/org/junit/vintage/engine/package-summary.html)' %}
{% assign junit-jupiter-engine = '[junit-jupiter-engine](' | append: javadoc-root | append: '/org/junit/jupiter/engine/package-summary.html)' %}

{% assign extension-api-package = '[org.junit.jupiter.api.extension](' | append: javadoc-root | append: '/org/junit/jupiter/api/extension/package-summary.html)' %}
{% assign junit-platform-support-package = '[org.junit.platform.commons.support](' | append: javadoc-root | append: '/org/junit/platform/commons/support/package-summary.html)' %}
{% assign params-provider-package = '[org.junit.jupiter.params.provider](' | append: javadoc-root | append: '/org/junit/jupiter/params/provider/package-summary.html)' %}
{% assign Launcher = '[Launcher](' | append: javadoc-root | append: '/org/junit/platform/launcher/Launcher.html)' %}
{% assign TestEngine = '[TestEngine](' | append: javadoc-root | append: '/org/junit/platform/engine/TestEngine.html)' %}
{% assign ArgumentsAccessor = '[ArgumentsAccessor](' | append: javadoc-root | append: '/org/junit/jupiter/params/aggregator/ArgumentsAccessor.html)' %}
{% assign ArgumentsAggregator = '[ArgumentsAggregator](' | append: javadoc-root | append: '/org/junit/jupiter/params/aggregator/ArgumentsAggregator.html)' %}
{% assign Assertions = '[org.junit.jupiter.api.Assertions](' | append: javadoc-root | append: '/org/junit/jupiter/api/Assertions.html)' %}
{% assign Assumptions = '[org.junit.jupiter.api.Assumptions](' | append: javadoc-root | append: '/org/junit/jupiter/api/Assumptions.html)' %}
{% assign BeforeAllCallback = '[BeforeAllCallback](' | append: javadoc-root | append: '/org/junit/jupiter/api/extension/BeforeAllCallback.html)' %}
{% assign BeforeEachCallback = '[BeforeEachCallback](' | append: javadoc-root | append: '/org/junit/jupiter/api/extension/BeforeEachCallback.html)' %}
{% assign BeforeTestExecutionCallback = '[BeforeTestExecutionCallback](' | append: javadoc-root | append: '/org/junit/jupiter/api/extension/BeforeTestExecutionCallback.html)' %}
{% assign AfterAllCallback = '[AfterAllCallback](' | append: javadoc-root | append: '/org/junit/jupiter/api/extension/AfterAllCallback.html)' %}
{% assign AfterEachCallback = '[AfterEachCallback](' | append: javadoc-root | append: '/org/junit/jupiter/api/extension/AfterEachCallback.html)' %}
{% assign AfterTestExecutionCallback = '[AfterTestExecutionCallback](' | append: javadoc-root | append: '/org/junit/jupiter/api/extension/AfterTestExecutionCallback.html)' %}
{% assign AnnotationSupport = '[AnnotationSupport](' | append: javadoc-root | append: '/org/junit/platform/commons/support/AnnotationSupport.html)' %}
{% assign ClassSupport = '[ClassSupport](' | append: javadoc-root | append: '/org/junit/platform/commons/support/ClassSupport.html)' %}
{% assign ReflectionSupport = '[ReflectionSupport](' | append: javadoc-root | append: '/org/junit/platform/commons/support/ReflectionSupport.html)' %}

{% assign Disabled = '[@Disabled](' | append: javadoc-root | append: '/org/junit/jupiter/api/Disabled.html)' %}
{% assign DisabledIf = '[@DisabledIf](' | append: javadoc-root | append: '/org/junit/jupiter/api/condition/DisabledIf.html'%}
{% assign DisabledIfEnvironmentVariable = '[@DisabledIfEnvironmentVariable](' | append: javadoc-root | append: '/org/junit/jupiter/api/condition/DisabledIfEnvironmentVariable.html)' %}
{% assign DisabledIfSystemProperty = '[@DisabledIfSystemProperty](' | append: javadoc-root | append: '/org/junit/jupiter/api/condition/DisabledIfSystemProperty.html)' %}
{% assign DisabledOnJre = '[@DisabledOnJre](' | append: javadoc-root | append: '/org/junit/jupiter/api/condition/DisabledOnJre.html)' %}
{% assign DisabledOnOs = '[@DisabledOnOs](' | append: javadoc-root | append: '/org/junit/jupiter/api/condition/DisabledOnOs.html)' %}
{% assign EnabledIf = '[@EnabledIf](' | append: javadoc-root | append: '/org/junit/jupiter/api/condition/EnabledIf.html)' %}
{% assign EnabledIfEnvironmentVariable = '[@EnabledIfEnvironmentVariable](' | append: javadoc-root | append: '/org/junit/jupiter/api/condition/EnabledIfEnvironmentVariable.html)' %}
{% assign SummaryGeneratingListener = '[SummaryGeneratingListener](' | append: javadoc-root | append: '/org/junit/platform/launcher/listeners/SummaryGeneratingListener.html)' %}
{% assign TestExecutionListener = '[TestExecutionListener](' | append: javadoc-root | append: '/org/junit/platform/launcher/TestExecutionListener.html)' %}
{% assign JUnitPlatform-Runner = '[JUnitPlatform](' | append: javadoc-root | append: '/org/junit/platform/runner/JUnitPlatform.html)' %}
{% assign ConsoleLauncher = '[ConsoleLauncher](' | append: javadoc-root | append: '/org/junit/platform/console/ConsoleLauncher.html)' %}

{% assign EnabledIfSystemProperty = '[@EnabledIfSystemProperty](' | append: javadoc-root | append: '/org/junit/jupiter/api/condition/EnabledIfSystemProperty.html)' %}
{% assign EnabledOnJre = '[@EnabledOnJre](' | append: javadoc-root | append: '/org/junit/jupiter/api/condition/EnabledOnJre.html)' %}
{% assign EnabledOnOs = '[@EnabledOnOs](' | append: javadoc-root | append: '/org/junit/jupiter/api/condition/EnabledOnOs.html)' %}
{% assign ExecutionCondition = '[ExecutionCondition](' | append: javadoc-root | append: '/org/junit/jupiter/api/extension/ExecutionCondition.html)' %}
{% assign ExtendWith = '[@ExtendWith](' | append: javadoc-root | append: '/org/junit/jupiter/api/extension/ExtendWith.html)' %}
{% assign ExtensionContext = '[ExtensionContext](' | append: javadoc-root | append: '/org/junit/jupiter/api/extension/ExtensionContext.html)' %}
{% assign ExtensionContext_Store = '[Store](' | append: javadoc-root | append: '/org/junit/jupiter/api/extension/ExtensionContext.Store.html)' %}
{% assign ParameterContext = '[ParameterContext](' | append: javadoc-root | append: '/org/junit/jupiter/api/extension/ParameterContext.html)' %}
{% assign ParameterizedTest = '[@ParameterizedTest](' | append: javadoc-root | append: '/org/junit/jupiter/params/ParameterizedTest.html)' %}
{% assign ParameterResolver = '[ParameterResolver](' | append: javadoc-root | append: '/org/junit/jupiter/api/extension/ParameterResolver.html)' %}
{% assign RegisterExtension = '[@RegisterExtension](' | append: javadoc-root | append: '/org/junit/jupiter/api/extension/RegisterExtension.html)' %}
{% assign MethodSource = '[@MethodSource](' | append: javadoc-root | append: '/org/junit/jupiter/params/provider/MethodSource.html)' %}
{% assign Execution = '[@Execution](' | append: javadoc-root | append: '/org/junit/jupiter/api/parallel/Execution.html)' %}
{% assign ResourceLock = '[@ResourceLock](' | append: javadoc-root | append: '/org/junit/jupiter/api/parallel/ResourceLock.html)' %}

{% assign ParallelExecutionConfigurationStrategy = '[ParallelExecutionConfigurationStrategy](' | append: javadoc-root | append: '/org/junit/platform/engine/support/hierarchical/ParallelExecutionConfigurationStrategy.html)' %}


{% assign RepetitionInfo = '[RepetitionInfo](' | append: javadoc-root | append: '/org/junit/jupiter/api/RepetitionInfo.html)' %}
{% assign TestExecutionExceptionHandler = '[TestExecutionExceptionHandler](' | append: javadoc-root | append: '/org/junit/jupiter/api/extension/TestExecutionExceptionHandler.html)' %}
{% assign TestInfo = '[TestInfo](' | append: javadoc-root | append: '/org/junit/jupiter/api/TestInfo.html)' %}
{% assign TestInstancePostProcessor = '[TestInstancePostProcessor](' | append: javadoc-root | append: '/org/junit/jupiter/api/extension/TestInstancePostProcessor.html)' %}
{% assign TestReporter = '[TestReporter](' | append: javadoc-root | append: '/org/junit/jupiter/api/TestReporter.html)' %}
{% assign TestTemplate = '[@TestTemplate](' | append: javadoc-root | append: '/org/junit/jupiter/api/TestTemplate.html)' %}
{% assign TestTemplateInvocationContext = '[TestTemplateInvocationContext](' | append: javadoc-root | append: '/org/junit/jupiter/api/extension/TestTemplateInvocationContext.html)' %}
{% assign TestTemplateInvocationContextProvider = '[TestTemplateInvocationContextProvider](' | append: javadoc-root | append: '/org/junit/jupiter/api/extension/TestTemplateInvocationContextProvider.html)' %}
{% assign HierarchicalTestEngine = '[HierarchicalTestEngine](' | append: javadoc-root | append: '/org/junit/platform/engine/support/hierarchical/HierarchicalTestEngine.html)' %}
{% assign TestInstanceFactory = '[TestInstanceFactory](' | append: javadoc-root | append: '/org/junit/jupiter/api/extension/TestInstanceFactory.html)' %}

