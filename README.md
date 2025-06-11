#景点推荐系统

这是一个基于图像识别的内容过滤推荐系统

## 功能特点

- 支持上传 JPG、JPEG、PNG 格式的图片
- 使用 FastAI 训练的深度学习模型进行图像识别
- 显示预测结果和置信度
- 进行内容推荐

## 本地运行

1. 安装依赖：
```bash
pip install -r requirements.txt
```

2. 运行应用：
```bash
streamlit run aaa.py
```

## 部署到 Streamlit Cloud

1. 将代码推送到 GitHub 仓库
2. 在 [Streamlit Cloud](https://streamlit.io/cloud) 创建新应用
3. 连接到你的 GitHub 仓库
4. 指定主文件：`aaa.py`

## 注意事项

- 确保模型文件 `*.pkl` 存在于项目根目录
- 模型文件较大，建议使用 Git LFS 管理 