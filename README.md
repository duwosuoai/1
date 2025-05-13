<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 800 600" width="800" height="600">
  <!-- 背景 -->
  <rect width="800" height="600" fill="#f9f9f9"/>
  
  <!-- 标题 -->
  <text x="400" y="40" font-family="Arial" font-size="24" text-anchor="middle" font-weight="bold" fill="#333">线性回归模型框架</text>
  
  <!-- 数据层 -->
  <rect x="100" y="100" width="600" height="100" rx="10" fill="#e6f7ff" stroke="#1890ff" stroke-width="2"/>
  <text x="400" y="150" font-family="Arial" font-size="18" text-anchor="middle" font-weight="bold" fill="#1890ff">数据层</text>
  <text x="400" y="180" font-family="Arial" font-size="14" text-anchor="middle" fill="#333">{(x₁,y₁), (x₂,y₂), ..., (xₙ,yₙ)}，其中x是特征向量，y是目标变量</text>
  
  <!-- 假设函数 -->
  <rect x="100" y="250" width="280" height="100" rx="10" fill="#fff2e8" stroke="#fa8c16" stroke-width="2"/>
  <text x="240" y="285" font-family="Arial" font-size="18" text-anchor="middle" font-weight="bold" fill="#fa8c16">假设函数</text>
  <text x="240" y="315" font-family="Arial" font-size="14" text-anchor="middle" fill="#333">h(x) = θ₀ + θ₁x₁ + θ₂x₂ + ... + θₙxₙ</text>
  <text x="240" y="345" font-family="Arial" font-size="14" text-anchor="middle" fill="#333">向量形式：h(x) = θ^T·x</text>
  
  <!-- 损失函数 -->
  <rect x="420" y="250" width="280" height="100" rx="10" fill="#f6ffed" stroke="#52c41a" stroke-width="2"/>
  <text x="560" y="285" font-family="Arial" font-size="18" text-anchor="middle" font-weight="bold" fill="#52c41a">损失函数</text>
  <text x="560" y="315" font-family="Arial" font-size="14" text-anchor="middle" fill="#333">均方误差(MSE)：J(θ) = (1/2m)Σ(h(x⁽ⁱ⁾)-y⁽ⁱ⁾)²</text>
  
  <!-- 优化算法 -->
  <rect x="100" y="400" width="600" height="100" rx="10" fill="#e9f7ef" stroke="#2e7d32" stroke-width="2"/>
  <text x="400" y="450" font-family="Arial" font-size="18" text-anchor="middle" font-weight="bold" fill="#2e7d32">优化算法</text>
  <text x="250" y="480" font-family="Arial" font-size="14" text-anchor="middle" fill="#333">梯度下降：θ_j = θ_j - α∂J(θ)/∂θ_j</text>
  <text x="550" y="480" font-family="Arial" font-size="14" text-anchor="middle" fill="#333">正规方程：θ = (X^T X)⁻¹ X^T y</text>
  
  <!-- 输出层 -->
  <rect x="300" y="520" width="200" height="60" rx="10" fill="#b3e5fc" stroke="#0288d1" stroke-width="2"/>
  <text x="400" y="555" font-family="Arial" font-size="18" text-anchor="middle" font-weight="bold" fill="#0288d1">最优参数 θ*</text>
  
  <!-- 连接线 -->
  <line x1="400" y1="200" x2="400" y2="250" stroke="#666" stroke-width="2" stroke-dasharray="5,5"/>
  <line x1="240" y1="350" x2="240" y2="400" stroke="#666" stroke-width="2"/>
  <line x1="560" y1="350" x2="560" y2="400" stroke="#666" stroke-width="2"/>
  <line x1="400" y1="500" x2="400" y2="520" stroke="#666" stroke-width="2"/>
</svg>
    
