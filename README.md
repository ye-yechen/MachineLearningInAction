# MachineLearningInAction
# 目录
## 第一部分  分类
- **第二章  k-近邻算法**
> **工作原理**：存在一个训练样本集，并且样本集中每个数据都存在标签，即已知样本集中每一数据与所属分类的对应关系.输入没有标签的新数据后，将新数据的每个特征与样本集中数据对应的特征进行比较，算法提取样本集中特征最相似（最近邻）的分类标签。选择k(k<20)个最相似数据中出现次数最多的分类作为新数据的分类。
>**优点**：精度高，对异常值不敏感，无数据输入假定
>**缺点**：计算复杂度高，空间复杂度高
>**适用数据范围**：数值型和标称型

- **第三章  决策树**
> **工作原理**：决策树算法能够读取数据集合，构建决策树。决策树的一个重要任务是理解数据中所蕴含的知识信息，因此决策树可以使用不熟悉的数据集合，并从中提取出一系列的规则，这些机器根据数据集创建规则的过程，就是机器学习的过程。
>**优点**：计算复杂度不高，输出结果易于理解，对中间值的缺失不敏感，可以处理不相关特征数据
>**缺点**：可能会产生过度匹配问题
>**适用数据类型**：数值型和标称型
