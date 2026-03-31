# Food Calorie Tracker

## 项目简介
这是一个用于追踪食物卡���里的应用，用户可以通过拍照或输入食物名称，自动识别食物并查询其热量信息。

## 主要功能
- 拍照识别食物，一键获取热量
- 支持手动输入食物名并查热量
- 显示食物营养成分详情
- 用户每日热量摄入记录
- 查看历史摄入统计

## 快速启动
1. 克隆仓库
   ```bash
   git clone https://github.com/xealml/food-calorie-tracker.git
   cd food-calorie-tracker
   ```
2. 安装依赖（以前端 React Native、后端 FastAPI 为例）
   ```bash
   cd app
   npm install
   cd ../backend
   pip install -r requirements.txt
   ```
3. 运行前端
   ```bash
   cd app
   npm start
   ```
4. 启动后端
   ```bash
   cd backend
   uvicorn main:app --reload
   ```
