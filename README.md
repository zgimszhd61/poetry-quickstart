# poetry-quickstart

`poetry` 是一个 Python 的依赖管理和打包工具，它旨在简化包的管理。下面是如何快速开始使用 `poetry` 的简要指南：

1. **安装 Poetry**:
   - 在您的系统上安装 Poetry。打开终端并运行以下命令：
     ```bash
     curl -sSL https://install.python-poetry.org | python3 -
     ```

2. **配置 Poetry**:
   - 你可以通过运行 `poetry config` 命令来进行一些基本的配置，例如设置 Python 的版本或者依赖的源。

3. **创建新的项目**:
   - 使用 Poetry 创建一个新的项目非常简单。在终端中运行：
     ```bash
     poetry new my-project
     ```
   - 这将创建一个名为 `my-project` 的新目录，里面包含了一些基本的项目文件和目录结构。

4. **添加依赖**:
   - 为你的项目添加依赖非常容易。例如，如果你想添加 `requests` 库，可以运行：
     ```bash
     poetry add requests
     ```
   - 这将自动更新 `pyproject.toml` 文件并安装该依赖。

5. **安装项目依赖**:
   - 进入项目目录中，使用以下命令来安装所有依赖：
     ```bash
     poetry install
     ```

6. **运行脚本和命令**:
   - 使用 Poetry 运行你的 Python 脚本非常简单：
     ```bash
     poetry run python my_script.py
     ```

7. **打包和发布**:
   - 使用 Poetry 打包你的项目很容易。只需运行：
     ```bash
     poetry build
     ```
   - 这将在 `dist` 目录生成轮（wheel）和源码包。
   - 要发布到 PyPI，先确保你有一个有效的账号，然后运行：
     ```bash
     poetry publish
     ```

8. **管理环境**:
   - Poetry 会自动管理虚拟环境，确保项目的依赖不会影响到全局 Python 环境。

这是一个简单的入门指南，希望对你有所帮助！如果你需要更详细的信息或者遇到任何问题，可以查阅官方文档或者寻求帮助。
