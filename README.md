# Black-Litterman
## 概念
Black-Litterman模型是基于MPT基础上的资产配置理论。其主要的贡献是提供了一个理论框架，能够将市场均衡收益和个人观点整合到一块，用以重新估计更可靠的预期收益率，然后将预期收益率带入MVO，得出最优资产配置，使得优化结果更加稳定和准确。
## 公式
- 𝐸(𝑅)=[(𝜏𝛴)^(−1)+𝑃^𝑇 𝛺^(−1) 𝑃]^(−1) [(𝜏𝛴)^(−1) 𝜋+𝑃^𝑇 𝛺^(−1) 𝑞]
## 模型构建
1. 根据历史数据计算出历史收益率之均值及协方差矩阵
2. 求出先验预期收益之期望值
3. 融合投资人的个人观点
4. 根据公式计算出后验分布之期望值、协方差
5. 根据后验收益期望值与协方差矩阵，代入Markowitz模型进行资产配置
## 说明
### 𝜋：先验预期收益率之期望值
- 一般来说以历史收益率均值作为先验预期收益之期望值
- 根据市场现有价格、市场组合反推出市场隐含的均衡收益率来作为先验预期收益之期望值
- 根据capm模型中的alpha(历史超额收益率)来估计先验预期收益之期望值
### 疑惑解答
- 如有疑惑，请联系：yishantao@hnu.edu.cn