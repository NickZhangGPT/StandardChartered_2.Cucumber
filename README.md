环境准备
 1. Java 环境
 • 安装 Java 8 或更高版本。
 • 验证：运行 java -version 检查版本。
 2. Maven
 • 安装 Maven 用于管理依赖。
 • 验证：运行 mvn -v 检查版本。
 3. Chrome 浏览器和 ChromeDriver
 • 安装 Google Chrome 浏览器。
 • 下载与 Chrome 版本匹配的 ChromeDriver。
 • 将 ChromeDriver 添加到系统环境变量，或在代码中指定路径。
 4. IDE
 • 推荐使用 IntelliJ IDEA 或 Eclipse。



如何运行
 1. 创建项目结构
 • 在本地创建一个空目录（如 enterprise-resumption-test）。
 • 按照上述结构创建文件夹和文件，并将代码复制到对应文件中。
 • 确保 screenshots/ 目录存在（可手动创建）。
 2. 配置 ChromeDriver
 • 将 ChromeDriver 可执行文件放入系统路径，或在 StepDefinitions.java 中通过 System.setProperty 指定路径。
 3. 运行测试
 • 使用 Maven：
 • 打开终端，进入项目根目录。
 • 运行命令：mvn test。
 • 使用 IDE：
 • 在 IDE 中打开项目。
 • 右键 TestRunner.java，选择“Run”。
 4. 查看结果
 • 测试完成后，查看 target/cucumber-reports.html 文件中的 HTML 测试报告。
 • 截图保存在 screenshots/ 目录下。
