# Bidirectional Material Balance System

A comprehensive, single-page web application designed for professional material balance calculations in industrial production processes. This tool supports both forward and backward calculations, allowing users to simulate a multi-step production flow, visualize data, and export detailed results.

It is built with vanilla JavaScript and styled with Tailwind CSS, making it a standalone and easy-to-use tool that runs directly in any modern web browser.

## ✨ Features

  * **Dual Calculation Modes**:
      * **Forward Calculation**: Calculate the final product yield based on the initial raw material input.
      * **Backward Calculation**: Determine the required raw material input to achieve a target product quantity.
  * **Interactive Multi-Step Process**:
      * Simulates a 16-step production workflow, from raw material receiving to final packaging.
      * Each step has configurable parameters like efficiency, loss rate, and moisture content.
      * Users can calculate each step sequentially or skip non-essential steps.
  * **Intuitive User Interface**:
      * A clean and responsive layout built with Tailwind CSS.
      * A process flow navigation bar to easily jump between steps.
      * Visual indicators for step status (Completed, Active, Skipped, Not Started).
  * **Data Visualization & Reporting**:
      * **Final Summary**: Key metrics are highlighted, including total input, final output, total loss, and overall yield.
      * **Interactive Charts**: (Using Chart.js)
          * A line chart to visualize the material flow across all production steps.
          * A doughnut chart showing the distribution of material losses.
      * **Detailed Data Table**: A comprehensive table summarizing the input, output, loss, and efficiency for every step.
  * **Advanced Functionality**:
      * **Export Results**: Export the complete calculation data and summary to a JSON file.
      * **Persistent State**: Automatically saves your progress to local storage, allowing you to resume your work later.
      * **Settings Modal**: Customize default values, calculation precision, and UI preferences.
      * **Reset Functionality**: Easily clear all data to start a new calculation.

## 🛠️ Tech Stack

  * **Frontend**: HTML5, Vanilla JavaScript (ES6)
  * **Styling**: [Tailwind CSS](https://tailwindcss.com/)
  * **Charts**: [Chart.js](https://www.chartjs.org/)
  * **Icons**: [Font Awesome](https://fontawesome.com/)

## 🚀 How to Use

No installation or build process is required. Simply download the `index.html` file and open it with a modern web browser (such as Google Chrome, Firefox, or Edge).

1.  **Choose Calculation Direction**: Select "Forward Calculation" or "Backward Calculation".
2.  **Set Base Parameters**: Enter the initial raw material amount (for forward) or the target product amount (for backward). Click "Apply Base Parameters".
3.  **Process Step-by-Step**: Fill in the parameters for the active step and click the "Calculate" button.
4.  **Navigate or Skip**: Move to the next step or use the "Skip" button for non-essential stages.
5.  **View Results**: Once all required steps are completed, a final summary with charts and a detailed table will be displayed.
6.  **Export Data**: Click the "Export" button at the top to save your results.

-----

-----

# 双向物料衡算系统 (中文说明)

一个功能全面的单页面 Web 应用，专为工业生产过程中的专业物料衡算而设计。该工具支持正向和逆向双向计算，允许用户模拟一个多步骤的生产流程、实现数据可视化并导出详细的计算结果。

该系统使用原生 JavaScript 构建，并采用 Tailwind CSS 进行样式设计，是一个无需安装、在任何现代浏览器中即可直接运行的独立工具。

## ✨ 主要功能

  * **双计算模式**:
      * **正向计算**: 从已知的原料投入量开始，计算最终的产品产量。
      * **逆向计算**: 根据目标产品产量，反推出所需的原料投入量。
  * **交互式多步骤流程**:
      * 模拟一个从原料接收到成品包装的 16 步完整生产流程。
      * 每一步都包含可配置的参数，如效率、损耗率、含水量等。
      * 用户可以按顺序计算每个步骤，也可以跳过非必要的步骤。
  * **直观的用户界面**:
      * 基于 Tailwind CSS 构建的整洁、响应式的布局。
      * 一个工艺流程导航栏，用于在不同步骤之间快速跳转。
      * 清晰的步骤状态指示（已完成、处理中、已跳过、未开始）。
  * **数据可视化与报告**:
      * **最终结果汇总**: 突出显示关键指标，包括总投入、最终产出、总损失和总收率。
      * **交互式图表**: (使用 Chart.js)
          * 使用折线图可视化所有生产步骤中的物料流向。
          * 使用环形图展示各个环节的物料损失分布。
      * **详细数据表格**: 提供一个全面的表格，汇总了每一步的进料量、出料量、损失量和效率。
  * **高级功能**:
      * **导出结果**: 将完整的计算数据和汇总报告导出为 JSON 文件。
      * **状态持久化**: 自动将您的计算进度保存到浏览器本地存储，方便随时恢复工作。
      * **设置面板**: 可自定义默认值、计算精度和界面偏好。
      * **重置功能**: 一键清空所有数据，以开始新的计算。

## 🛠️ 技术栈

  * **前端**: HTML5, 原生 JavaScript (ES6)
  * **样式**: [Tailwind CSS](https://tailwindcss.com/)
  * **图表**: [Chart.js](https://www.chartjs.org/)
  * **图标**: [Font Awesome](https://fontawesome.com/)

## 🚀 如何使用

无需安装或构建。只需下载 `index.html` 文件，然后用现代浏览器（如 Google Chrome, Firefox, 或 Edge）打开即可。

1.  **选择计算方向**: 选择“正向计算”或“逆向计算”。
2.  **设置基础参数**: 输入初始原料投入量（正向计算）或目标产品量（逆向计算），然后点击“应用基础参数”。
3.  **分步计算**: 填写当前激活步骤的参数，然后点击“计算”按钮。
4.  **导航或跳过**: 完成后系统会自动进入下一步，您也可以点击“跳过”按钮处理非必要环节。
5.  **查看结果**: 当所有必需步骤完成后，系统将显示包含图表和详细表格的最终结果汇总。
6.  **导出数据**: 点击顶部的“导出”按钮，即可将计算结果保存到本地。
