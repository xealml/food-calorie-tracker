# Food Calorie Tracker 后端

本目录为 FastAPI 实现的后端接口。

## 快速开始

1. 安装依赖
   ```bash
   pip install -r requirements.txt
   ```
2. 运行服务
   ```bash
   uvicorn main:app --reload
   ```

接口启动后，访问 http://localhost:8000 即可看到健康检查（根路径）返回。

## 部署建议
- 推荐配合前端 app/ 目录使用
- 可以部署到云服务器或平台（如 Railway、Render、阿里云、腾讯云等）
- 支持Docker化部署，可根据需要自行添加 Dockerfile