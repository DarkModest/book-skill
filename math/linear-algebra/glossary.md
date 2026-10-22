# 术语表（中英对照）

按拼音首字母所属英文字母序排列；括号内为教材章节。

**adjugate 伴随矩阵** — 代数余子式矩阵的转置；A⁻¹ = adj A / det A（ch08）
**affine combination 仿射组合** — 权值之和为 1 的线性组合（ch20）
**affine independence 仿射无关** — Σcᵢvᵢ=0 且 Σcᵢ=0 只有零解；加高向量后即线性无关（ch20）
**attractor 吸引子** — 动力系统中所有特征值 |λ|<1，一切轨迹趋于 0（ch14）
**augmented matrix 增广矩阵** — 系数矩阵右侧加上常数列 [A|b]（ch01）
**barycentric coordinates 重心坐标** — 点关于仿射无关集的唯一仿射组合系数（ch20）
**basic variable 基本变量** — 主元列对应的变量；其余为自由变量（ch01）
**basis 基** — 线性无关的生成集（ch09）
**Bézier curve 贝塞尔曲线** — 控制点经混合多项式（P₃ 的基 (1−t)³, 3t(1−t)², 3t²(1−t), t³）加权而成的曲线，总位于控制点凸包内（ch21）
**Cayley-Hamilton 凯莱-哈密顿** — 矩阵满足自身特征多项式（本书习题层）
**characteristic equation 特征方程** — det(A−λI)=0（ch08, ch12）
**Cholesky 分解** — 对称正定阵 A=LLᵀ（ch06 习题层）
**cofactor 余因子** — (−1)^{i+j} 倍的子式；用于行列式展开（ch08）
**Col A 列空间** — A 的列的全部线性组合；基=原矩阵主元列（ch07, ch09）
**convex set 凸集** — 对凸组合封闭；等价于两点连线段在集内（ch20）
**Cramer's rule 克拉默法则** — 方阵方程的行列式解公式（ch08）
**determinant 行列式** — 方阵的数值指纹；可逆性/体积/特征多项式的来源（ch08）
**diagonalizable 可对角化** — A=PDP⁻¹；判据=各特征值几何重数=代数重数（ch12）
**dimension 维数** — 基所含向量个数（ch10）
**dual problem 对偶问题** — min bᵀy s.t. Aᵀy≥c, y≥0；与原始问题值相等（ch23）
**echelon form 阶梯形 / RREF 简化阶梯形** — 行化简的两个目标形态；RREF 唯一（ch01, ch24）
**eigenspace 特征空间** — Eig(A,λ)=Nul(A−λI)（ch12）
**eigenvalue/eigenvector 特征值/特征向量** — Ax=λx 的 λ 与非零 x（ch12）
**elementary matrix 初等矩阵** — 单位阵经一次行变换所得；左乘=行变换（ch05）
**equilibrium prices 均衡价格** — 列昂惕夫交换模型中的正特征向量方向（ch07）
**extreme point 极值点** — 凸集中不能表示为两点线段内点的点（ch20, ch22）
**factorization 矩阵分解** — A 表示为矩阵乘积：LU、QR、PDP⁻¹、UΣVᵀ（ch06, ch16, ch12, ch19）
**Fourier coefficients 傅里叶系数** — 函数到三角正交基的投影系数（ch17）
**Gram-Schmidt 格拉姆-施密特过程** — 减投影造正交基的递归算法（ch16）
**hyperplane 超平面** — {x: n·x=b}；法向量 n（ch21）
**identity matrix 单位矩阵** — Iₙ；乘法单位元（ch02, ch05）
**IMT 可逆矩阵定理** — 方阵 15 条等价命题网络（ch05）
**inconsistent 不相容** — 方程组无解（ch01）
**inner product space 内积空间** — 定义了满足四公理内积的向量空间（ch17）
**inverse 逆** — A⁻¹ 满足 AA⁻¹=A⁻¹A=I（ch05）
**kernel 核** — 线性变换的 T(x)=0 解集 = Nul A（ch09）
**least-squares 最小二乘** — 不相容系统的最小残差解；正规方程 AᵀAx̂=Aᵀb（ch16）
**Leontief input-output 列昂惕夫投入-产出** — x=Cx+d；列昂惕夫逆 (I−C)⁻¹（ch07）
**linear transformation 线性变换** — 保持加法与数乘的映射 T(x)=Ax（ch04）
**LU 分解** — A=LU，L 单位下三角（乘数日志），U 阶梯形（ch06）
**Markov chain 马尔可夫链** — x_{k+1}=Pxₖ，P 随机矩阵；稳态 q 满足 Pq=q（ch14）
**Nul A 零空间** — {x: Ax=0}；基=齐次解参数化向量（ch07, ch09）
**orthogonal 正交** — u·v=0；正交集两两垂直且自动线性无关（ch15）
**orthogonal projection 正交投影** — y 在子空间上的最近点 ŷ（ch15）
**orthogonal matrix 正交矩阵** — QᵀQ=I 的方阵；Q⁻¹=Qᵀ（ch15）
**PCA 主成分分析** — 协方差矩阵 S 的谱分解；方差占比=σᵢ²/Σσⱼ²（ch19）
**pivot 主元** — 行化简后主元位置的 1；主元列/自由变量的开关（ch01）
**power method 幂法** — 迭代 Ax 收敛到占优特征向量（ch14）
**probability vector 概率向量** — 非负且和为 1（ch14）
**QR 分解** — A=QR，Q 标准正交列，R 上三角（ch16）
**quadratic form 二次型** — Q(x)=xᵀAx；定号性由特征值符号决定（ch18）
**random matrix/stochastic 随机矩阵** — 各列为概率向量的方阵（ch14）
**rank 秩** — dim Col A = 主元个数；rank+dim Nul = n（ch07）
**Rayleigh quotient 瑞利商** — xᵀAx/xᵀx；特征值的滑动估计（ch18, ch14）
**regular stochastic matrix 正规随机矩阵** — 各项严格正；保证收敛唯一稳态（ch14）
**residual 残差** — 观测与模型预测之差 b−Ax̂（ch16）
** saddle point 鞍点** — max-min=min-max 的支付矩阵位置（ch22）
**shear 剪切变换** — 标准矩阵 [1 k; 0 1] 型线性变换（ch04）
**similar matrices 相似矩阵** — B=P⁻¹AP；同特征多项式（ch10, ch12）
**simplex method 单纯形法** — 沿极值点的表格主元算法（ch23）
**slack variable 松弛变量** — 把不等式变方程的辅助变量（ch23）
**span 生成集** — Span{v₁,…,vₚ}=全部线性组合（ch02）
**spectral theorem 谱定理** — 对称阵可正交对角化 A=QDQᵀ（ch18）
**steady-state vector 稳态向量** — Pq=q 的概率向量（ch14）
**SVD 奇异值分解** — A=UΣVᵀ；σᵢ=√λᵢ(AᵀA)（ch19）
**trace 迹** — 对角元之和=特征值之和（ch12）
**transpose 转置** — Aᵀ_{ij}=A_{ji}；(AB)ᵀ=BᵀAᵀ（ch05）
**vector space 向量空间** — 加法/数乘封闭且满足公理的集合（ch09）
**Wronskian 朗斯基行列式** — 函数组无关性的行列式判据（本书习题层）
**zero subspace/subvector 零子空间** — 仅含 {0} 的平凡子空间（ch09）
