# Test-for-new-friend
---
**这是一个团队邀请测试**

##测试1
## 要求

**题目**：使用任意编程语言实现一个医院患者管理系统。

**任务描述**：

设计并实现一个简单的医院患者管理系统。系统需要实现以下基本功能：

1. **患者信息管理**：
   - 添加患者：包括姓名、年龄、性别、联系方式、病历编号、病史等信息。
   - 编辑患者：更新患者信息。
   - 删除患者：删除指定患者的记录。
   - 查询患者：通过姓名、病历编号或其他关键字查询患者信息。

1. **病历管理**：
   - 记录病历：为患者记录就诊和治疗信息。
   - 更新病历：修改或追加病历内容。
   - 查询病历：按患者或病历编号查找病历。

1. **用户权限管理**：
   - 管理员和普通用户权限的区分。
   - 普通用户只能查看和编辑部分信息（如患者和预约），管理员具有所有权限。



## 要求
1. 使用任意语言编写，**物联网工程专业必须使用C语言**（大一期末考为C语言）。
2. 可以使用任意开源代码或人工智能技术。
3. 完成**第1项**即可提交，如有能力建议完成**第2项**和**第3项**。
4. 每个功能的代码块必须添加注释解释其作用。
5. 变量中至少有*两处*包含自己的姓名缩写。

## 提交要求

- **代码文件**：包括所有源代码文件。
- **测试代码**：包括单元测试和集成测试代码。
- **完成后请将项目托管在Github上**
- **最终提交GITHUB链接至邮箱：yunqi_tang@qq.com
  主题为：班级+姓名+编程语言+联系方式**

## 考察重点

- **问题解决能力**：能否根据需求设计出合理的系统架构。
- **编程能力**：代码实现是否高效，是否符合最佳实践。
- **学习与创新**：是否能够结合新技术或方法来优化系统。

---
# 测试 2：使用 YOLO 识别猪猪侠

## 任务描述

本次任务要求使用 YOLO（You Only Look Once）模型进行猪猪侠的目标检测。你需要在给定的图像或视频中准确识别出猪猪侠的位置。任务需要包括数据准备、模型训练、测试以及结果评估的完整流程。以下是具体的要求和步骤：

## 任务要求

1. **使用 YOLO 模型**：
   - 可以使用 YOLOv4、YOLOv5、YOLOv7 或更高版本。
   - 可以选择使用预训练模型进行迁移学习，也可以从头开始训练模型。

2. **数据准备**：
   - 收集并标注至少 300 张包含猪猪侠的图像（使用爬虫爬取）。图像中猪猪侠的姿态、大小、光照条件应尽可能多样化。
   - 图像应当标注猪猪侠的边界框（bounding boxes），格式可以使用 VOC、COCO 或 YOLO 格式。
   - 数据集应划分为训练集（70%）、验证集（20%）和测试集（10%）。

3. **模型训练**：
   - 训练 YOLO 模型，使用的超参数（如学习率、批次大小、训练轮数）需根据验证集性能调优。
   - 训练过程中应记录损失值及模型性能的变化情况。

4. **测试与评估**：
   - 使用测试集对模型进行评估，计算并报告以下指标：
     - 精确率（Precision）
     - 召回率（Recall）
     - 平均精度均值（mAP）
   - 输出每张测试图片中猪猪侠的识别结果，并展示识别框。

5. **代码注释与规范**：
   - 每个功能代码块必须添加注释，解释其作用。
   - 变量命名规范，至少两处包含开发者的姓名缩写。

6. **模型优化（可选）**：
   - 对训练好的模型进行优化，如模型压缩、量化等，以提高模型的推理速度或减少资源占用。
   - 测试优化后模型的性能变化情况。

7. **提交内容**：
   - **源代码**：包括模型训练、测试的完整代码。
   - **数据集**：标注好的数据集及其分割情况【截图就可以】。
   - **模型文件**：训练好的模型权重文件。
   - **结果报告**：包含任务描述、数据处理、模型训练过程、测试结果、问题解决及优化方案等内容。
   - **演示视频**：展示模型对测试集的识别效果。
   -  **完成后请将项目托管在Github上**
- **最终提交GITHUB链接至邮箱：yunqi_tang@qq.com
  主题为：班级+姓名+编程语言+联系方式**

## 其他注意事项

- 可使用任何深度学习框架（如 PyTorch、TensorFlow）。
- 可以借助已有的开源工具包，但必须在报告中注明并解释其使用方法。
- 确保代码能够在标准的硬件配置下运行（如单块 GPU）。


