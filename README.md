# different-loss-functions-on-linear-regression
Experiments with different loss functions applied to linear regression.
-------------------------
This project has 5 headers
- Libraries(pandas, matplotlib)
- Data import(chatgpt made the datas) and scatter plot(matplotlib)
- Loss functions
    1. L2 loss
    2. L1 loss
- Partial derivatives using limit defination of differentiation
- Gradient decent
- Results


Since the project can use different loss functions as the imput of gradient decent u can add whatever loss function you want and see the results on three different small data sets.


Math Explanation

I made chatgpt write the functions i used later i will upload a full paper on this.
- Linear function
    1. ŷ = m·x + b
    
- L2 and L1 loss functions
    L2: L₂ = (1/n) * Σ (yᵢ - (m·xᵢ + b))²
    L1: L₁ = (1/n) * Σ |yᵢ - (m·xᵢ + b)|
    
- Partial derivatives using limit defination
    ∂L/∂m ≈ [ L(m + h, b) - L(m, b) ] / h where lim h goes to 0
    ∂L/∂b ≈ [ L(m, b + h) - L(m, b) ] / h where lim h goes to 0

- Gradient decent
    m ← m - η * (∂L/∂m)
    b ← b - η * (∂L/∂b)




