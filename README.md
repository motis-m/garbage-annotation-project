# 生活垃圾目标检测标注项目（Label Studio 版）

## 项目概述
本项目为垃圾分类目标检测模型提供训练数据，包含35张真实场景图片，
标注5个类别：塑料、纸张、金属、玻璃、其他垃圾。

## 使用工具
- Label Studio（标注平台）
- YOLO with Images 格式（输出格式）

## 项目成果
- 标注图片：35张
- 标注框总数：35个
- 抽检准确率：85.71%
- 导出格式：YOLO with Images（含 classes.txt 类别索引）

## 文件说明
- `images/`：原始图片
- `labels/`：YOLO格式标注文件
- `classes.txt`：类别索引文件
- `label_config.xml`：Label Studio 标注界面配置
- `annotation_guideline.md`：标注规范
- `quality_report.xlsx`：质量抽检报告