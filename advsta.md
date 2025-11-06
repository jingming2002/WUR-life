# Advanced statistics review
# 统计符号大全（GitHub README 兼容版）

## 📊 基础描述统计

| 符号 | 名称 | 含义 | 示例 |
|------|------|------|------|
| n | 样本量 | 观测值数量 | n = 100 |
| N | 总体大小 | 总体元素数量 | N = 1000 |
| x̄ | 样本均值 | 样本平均值 | x̄ = 25.3 |
| μ | 总体均值 | 总体平均值 | μ = 30.1 |
| s² | 样本方差 | 样本离散程度 | s² = 16.5 |
| σ² | 总体方差 | 总体离散程度 | σ² = 18.2 |
| s | 样本标准差 | 样本标准差 | s = 4.06 |
| σ | 总体标准差 | 总体标准差 | σ = 4.27 |
| med | 中位数 | 中间值 | med = 24 |
| mod | 众数 | 出现最频繁的值 | mod = 23 |
| Q₁, Q₂, Q₃ | 四分位数 | 25%, 50%, 75% 分位数 | Q₁ = 20, Q₂ = 25, Q₃ = 30 |
| IQR | 四分位距 | Q₃ - Q₁ | IQR = 10 |

## 📈 相关与回归

| 符号 | 名称 | 含义 | 示例 |
|------|------|------|------|
| r | 样本相关系数 | 线性相关强度 | r = 0.85 |
| ρ | 总体相关系数 | 总体相关强度 | ρ = 0.78 |
| R | 多重相关系数 | 多元相关 | R = 0.92 |
| R² | 决定系数 | 解释方差比例 | R² = 0.64 |
| adj R² | 调整决定系数 | 调整后的解释比例 | adj R² = 0.61 |
| β₀ | 截距项 | 回归常数项 | β₀ = 2.5 |
| β₁, β₂... | 回归系数 | 斜率参数 | β₁ = 0.8, β₂ = -0.3 |
| b₀, b₁... | 估计系数 | 系数估计值 | b₀ = 2.3, b₁ = 0.75 |
| ŷ | 预测值 | 模型预测结果 | ŷ = 25.3 |
| ε | 误差项 | 随机误差 | y = β₀ + β₁x + ε |

## 🎯 概率与分布

| 符号 | 名称 | 含义 | 示例 |
|------|------|------|------|
| P(A) | 概率 | 事件A发生的概率 | P(A) = 0.05 |
| P(A│B) | 条件概率 | B发生时A的概率 | P(A│B) = 0.3 |
| E(X) | 期望值 | 随机变量期望 | E(X) = μ |
| Var(X) | 方差 | 随机变量方差 | Var(X) = σ² |
| Cov(X,Y) | 协方差 | 两个变量协同变化 | Cov(X,Y) = 12.5 |
| ∼ | 服从分布 | 概率分布 | X ∼ N(0,1) |
| ∝ | 正比于 | 成比例关系 | y ∝ x |

## 📋 概率分布符号

| 分布 | 符号 | 参数 | 示例 |
|------|------|------|------|
| 正态分布 | N(μ, σ²) | 均值, 方差 | X ∼ N(50, 25) |
| 标准正态 | N(0, 1) | 标准正态 | Z ∼ N(0, 1) |
| t分布 | t(df) | 自由度 | T ∼ t(15) |
| F分布 | F(df₁, df₂) | 分子分母自由度 | F ∼ F(3, 20) |
| 卡方分布 | χ²(df) | 自由度 | χ² ∼ χ²(5) |
| 二项分布 | Bin(n, p) | 试验次数, 成功概率 | X ∼ Bin(10, 0.5) |
| 泊松分布 | Pois(λ) | 发生率 | X ∼ Pois(3) |
| 指数分布 | Exp(λ) | 速率参数 | X ∼ Exp(0.5) |

## 🔍 假设检验

| 符号 | 名称 | 含义 | 示例 |
|------|------|------|------|
| H₀ | 零假设 | 待检验的假设 | H₀: μ = 100 |
| H₁ | 备择假设 | 替代假设 | H₁: μ ≠ 100 |
| Hₐ | 备择假设 | 同H₁ | Hₐ: μ > 100 |
| α | 显著性水平 | 第一类错误概率 | α = 0.05 |
| β | 第二类错误概率 | 错误接受H₀的概率 | β = 0.20 |
| 1-β | 检验功效 | 正确拒绝H₀的概率 | 1-β = 0.80 |
| p | p值 | 观察到的极端概率 | p = 0.023 |
| CI | 置信区间 | 参数估计区间 | 95% CI: [45.2, 54.8] |

## 📏 检验统计量

| 符号 | 名称 | 公式/含义 | 示例 |
|------|------|------------|------|
| z | z统计量 | (x̄ - μ₀)/(σ/√n) | z = 2.15 |
| t | t统计量 | (x̄ - μ₀)/(s/√n) | t(25) = 2.31 |
| F | F统计量 | 方差比 | F(3,20) = 4.25 |
| χ² | 卡方统计量 | 拟合优度检验 | χ²(5) = 12.3 |
| U | Mann-Whitney U | 非参数检验 | U = 45 |

## 🧮 数学运算符

| 符号 | 名称 | 示例 |
|------|------|------|
| Σ | 求和 | Σxᵢ = x₁ + x₂ + ... + xₙ |
| Π | 求积 | Πxᵢ = x₁ × x₂ × ... × xₙ |
| ∫ | 积分 | ∫f(x)dx |
| ∂ | 偏导数 | ∂f/∂x |
| Δ | 差分 | Δx = x₂ - x₁ |
| lim | 极限 | lim(x→0)f(x) |
| ∞ | 无穷大 | n → ∞ |

## ⚖️ 比较运算符

| 符号 | 名称 | 示例 |
|------|------|------|
| = | 等于 | μ = 100 |
| ≠ | 不等于 | μ ≠ 100 |
| < | 小于 | p < 0.05 |
| > | 大于 | n > 30 |
| ≤ | 小于等于 | α ≤ 0.05 |
| ≥ | 大于等于 | 功效 ≥ 0.80 |
| ≈ | 约等于 | π ≈ 3.14159 |
| ≡ | 恒等于 | a ≡ b |

## 🔢 上下标数字

| 数字 | 上标 | 下标 | 使用示例 |
|------|------|------|----------|
| 0 | ⁰ | ₀ | x⁰, x₀ |
| 1 | ¹ | ₁ | β¹, x₁ |
| 2 | ² | ₂ | R², x₂ |
| 3 | ³ | ₃ | 2³, β₃ |
| 4 | ⁴ | ₄ | n⁴, x₄ |
| 5 | ⁵ | ₅ | χ²⁵, y₅ |
| 6 | ⁶ | ₆ | t⁶, z₆ |
| 7 | ⁷ | ₇ | F⁷, w₇ |
| 8 | ⁸ | ₈ | σ⁸, v₈ |
| 9 | ⁹ | ₉ | p⁹, u₉ |




## General idea about a population
--- Question about population  
--- Take sample   
--- Test hypothesis in the sample   
--- Take into account variation among samples  
--- Draw a conclusion about the population

## Confidence interval (CI)  
An interval that is expected to typically contain the parameter being estimated    
CI=Point Estimate±(t critical)×(Standard Error)  

Point Estimate: Exp. point estimate of popilation mean(&mu;) is sample's mean(x&#772;) 
 
T critical: Width of interval and Df(degrees of freedom) 
 
Standard Error: Size and variation of the sample  

## t-test
Degrees of freedom determine the shape of t-distribution; larger df will cause it more normality, if df → ∞, it will be exactly a normal distribution.  

### Single-sample t-test
Sample's mean compared with known &mu;   
1. H<sub>0</sub>: x&#772; = &mu;  
H<sub>a</sub>: x&#772; != &mu;  or  x&#772; > &mu; or x&#772; < &mu;  
2. t = (x̄ - μ₀) / (s/√n)
3. Under H<sub>0</sub>, t~t<sub>df = (n - 1)</sub>
4. Under H<sub>a</sub>, T.S tends to smaller or larger values than under H<sub>0</sub>
5. Using left, right, or two-tailed p-value
6. t = T.S
7. p-value compared with &alpha;
8. Conclusion
### Independent two-sample t-test
***SAME VARIANCE!!!!!!!!!!!!!***  
Comparing the two samples' means  
1. H<sub>0</sub>: &mu;<sub>1</sub>=&mu;<sub>2</sub>  
   H<sub>0</sub>: &mu;<sub>1</sub>!=&mu;<sub>2</sub> (Smaller, larger or just differ)
2. t= (x̄₁ - x̄₂) / [sₚ × √(1/n₁ + 1/n₂)]  
sₚ= √{ [ (n₁ - 1)s₁² + (n₂ - 1)s₂² ] / (n₁ + n₂ - 2) }  
df = n₁ + n₂ - 2
3. Under H<sub>0</sub>, t~t<sub>df</sub>
4. Under H<sub>a</sub>, T.S tends to smaller or larger values than under H<sub>0</sub>
5. Using left, right, or two-tailed p-value
6. t = T.S
7. p-value compared with &alpha;
8. Conclusion

#### Levene's test
This is close to F-test; they share a common statistic  
F = MSB/MSW  
MSB = [Mean<sub>A</sub>-Mean<sub>all</sub>)+(Mean<sub>B</sub>-Mean<sub>all</sub>)]/(k-1)  
MSW = [Σ(x<sub>i</sub>-x̄)<sup>2</sup>+Σ(x<sub>j</sub>-x̄<sub>1</sub>)<sup>2</sup>]/(N-k)  
N is nr of total units, k stands for nr of samples
#### Welch's t-test
Normally, we do not have two samples with exactly the same variances, so Welch's t-test could be applied.  
It is essentially the same as the t-test, but offers more conservative calculations and a lower probability of false positivity.
1. H<sub>0</sub>: &mu;<sub>1</sub>=&mu;<sub>2</sub>  
   H<sub>0</sub>: &mu;<sub>1</sub>!=&mu;<sub>2</sub> (Smaller, larger or just differ)
2. t= (x̄₁ - x̄₂) / [sₚ × √(1/n₁ + 1/n₂)]  
sₚ= √{ [ (n₁ - 1)s₁² + (n₂ - 1)s₂² ] / (n₁ + n₂ - 2) }  
***df = [ (s₁²/n₁ + s₂²/n₂)² ] / [ (s₁²/n₁)²/(n₁-1) + (s₂²/n₂)²/(n₂-1) ]***
3. Under H<sub>0</sub>, t~t<sub>df</sub>
4. Under H<sub>a</sub>, T.S tends to smaller or larger values than under H<sub>0</sub>
5. Using left, right, or two-tailed p-value
6. t = T.S
7. p-value compared with &alpha;
8. Conclusion

### Paired-sample t-test
Check there is any difference between one sample in two conditions.
1. H<sub>0</sub>: &mu;<sub>1</sub>=&mu;<sub>2</sub>  
   H<sub>0</sub>: &mu;<sub>1</sub>!=&mu;<sub>2</sub> (Smaller, larger or just differ)
2. t= d̄ / (s_d / √n)
3. Under H<sub>0</sub>, t~t<sub>df</sub>
4. Under H<sub>a</sub>, T.S tends to smaller or larger values than under H<sub>0</sub>
5. Using left, right, or two-tailed p-value
6. t = T.S
7. p-value compared with &alpha;
8. Conclusion

