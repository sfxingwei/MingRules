# MingRules
Ming rules for risk policy
#
由于文件大小限制，包文件参见如下链接，如失效，请发邮件至swufewxw@163.com
#
链接：https://pan.baidu.com/s/12edfvzt8sRdhPmU28qLb1g 
提取码：nl4y 
复制这段内容后打开百度网盘手机App，操作更方便哦

# 案例
from MingRules import rules_dm
#
mr=RuleMing(max_depth=3) 参数同决策树参数
#
mr.MingRules(X,y)
#
mr.Ming_Rule_plot() 展示决策树
#
mr.tune_ft_threshold(1.5,node_no='8') 修改节点阈值
#
mr.Ming_Rule_plot() 展示修改节点阈值后的决策树

# 决策树节点信息
node_id:节点id
#
samples：节点样本数
#
type_samples:[节点y=0的样本数，节点y=1的样本数]
#
badrate:节点坏样本占比
#
decisioninfo:[节点样本/总样本，节点坏样本/总体坏样本]
