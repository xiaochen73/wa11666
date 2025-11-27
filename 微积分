<!DOCTYPE html>
<html lang="zh-CN">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>微积分极限经典习题集</title>
    <script src="https://cdn.jsdelivr.net/npm/mathjax@3/es5/tex-mml-chtml.js"></script>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Segoe UI', 'Microsoft YaHei', sans-serif;
        }
        
        body {
            background-color: #f5f7fa;
            color: #333;
            line-height: 1.6;
            padding: 20px;
            max-width: 1200px;
            margin: 0 auto;
        }
        
        header {
            text-align: center;
            margin-bottom: 40px;
            padding: 30px 20px;
            background: linear-gradient(135deg, #2c3e50, #4a6491);
            color: white;
            border-radius: 10px;
            box-shadow: 0 4px 12px rgba(0,0,0,0.1);
        }
        
        h1 {
            font-size: 2.2rem;
            margin-bottom: 10px;
        }
        
        .subtitle {
            font-size: 1.1rem;
            opacity: 0.9;
        }
        
        .container {
            display: grid;
            grid-template-columns: 1fr;
            gap: 25px;
        }
        
        .question-card {
            background: white;
            padding: 25px;
            border-radius: 10px;
            box-shadow: 0 4px 12px rgba(0,0,0,0.08);
            margin-bottom: 20px;
        }
        
        .question-number {
            display: inline-block;
            background: #3498db;
            color: white;
            width: 30px;
            height: 30px;
            border-radius: 50%;
            text-align: center;
            line-height: 30px;
            margin-right: 10px;
            font-weight: bold;
        }
        
        .question-text {
            font-size: 1.1rem;
            margin-bottom: 20px;
            padding-bottom: 15px;
            border-bottom: 1px solid #eee;
        }
        
        .math-expression {
            font-size: 1.2rem;
            text-align: center;
            margin: 15px 0;
            padding: 10px;
            background-color: #f8f9fa;
            border-radius: 5px;
            border-left: 3px solid #3498db;
        }
        
        .options {
            margin: 15px 0;
            padding-left: 20px;
        }
        
        .option {
            margin-bottom: 10px;
            padding: 8px 12px;
            border-radius: 5px;
            cursor: pointer;
            transition: background-color 0.2s;
        }
        
        .option:hover {
            background-color: #f0f7ff;
        }
        
        .option.selected {
            background-color: #e1f0ff;
            border-left: 3px solid #3498db;
        }
        
        .explanation {
            background-color: #f8f9fa;
            padding: 20px;
            border-radius: 8px;
            margin-top: 20px;
            display: none;
        }
        
        .explanation.active {
            display: block;
        }
        
        .key-point {
            background-color: #fff9e6;
            padding: 15px;
            border-left: 4px solid #f1c40f;
            margin: 20px 0;
            border-radius: 0 5px 5px 0;
        }
        
        .controls {
            display: flex;
            justify-content: space-between;
            margin-top: 30px;
        }
        
        button {
            padding: 10px 20px;
            background: #3498db;
            color: white;
            border: none;
            border-radius: 5px;
            cursor: pointer;
            font-size: 1rem;
            transition: background 0.3s;
        }
        
        button:hover {
            background: #2980b9;
        }
        
        button:disabled {
            background: #bdc3c7;
            cursor: not-allowed;
        }
        
        .summary {
            background: white;
            padding: 25px;
            border-radius: 10px;
            box-shadow: 0 4px 12px rgba(0,0,0,0.08);
            margin-top: 30px;
        }
        
        .concept-table {
            width: 100%;
            border-collapse: collapse;
            margin: 20px 0;
        }
        
        .concept-table th, .concept-table td {
            padding: 12px 15px;
            text-align: left;
            border-bottom: 1px solid #e0e0e0;
        }
        
        .concept-table th {
            background-color: #f1f5f9;
            font-weight: 600;
            color: #2c3e50;
        }
        
        .category-header {
            background: linear-gradient(135deg, #2c3e50, #4a6491);
            color: white;
            padding: 15px 20px;
            border-radius: 8px;
            margin: 30px 0 15px;
            font-size: 1.3rem;
        }
        
        @media (max-width: 768px) {
            .math-expression {
                font-size: 1rem;
                overflow-x: auto;
            }
        }
    </style>
</head>
<body>
    <header>
        <h1>微积分极限经典习题集</h1>
        <div class="subtitle">涵盖等价无穷小、连续性、重要极限与极限存在性判断</div>
    </header>
    
    <div class="container">
        <div class="category-header">第一部分：重要极限与等价无穷小</div>
        
        <div class="question-card">
            <div class="question-header">
                <span class="question-number">1</span>
                <span class="question-type">重要极限</span>
            </div>
            <div class="question-text">
                计算极限：\(\lim_{x \to 0} \frac{\sin 3x}{x}\)
            </div>
            <div class="options">
                <div class="option">A. 0</div>
                <div class="option">B. 1</div>
                <div class="option" data-correct="true">C. 3</div>
                <div class="option">D. 不存在</div>
            </div>
            <button class="show-explanation">查看解析</button>
            <div class="explanation">
                <p><strong>正确答案：C</strong></p>
                <p><strong>解析：</strong></p>
                <p>利用重要极限 \(\lim_{x \to 0} \frac{\sin x}{x} = 1\)，我们有：</p>
                <div class="math-expression">
                    \(\lim_{x \to 0} \frac{\sin 3x}{x} = \lim_{x \to 0} \frac{\sin 3x}{3x} \cdot 3 = 1 \cdot 3 = 3\)
                </div>
                <div class="key-point">
                    <strong>关键点：</strong>重要极限 \(\lim_{x \to 0} \frac{\sin x}{x} = 1\) 的变形应用。
                </div>
            </div>
        </div>
        
        <div class="question-card">
            <div class="question-header">
                <span class="question-number">2</span>
                <span class="question-type">等价无穷小</span>
            </div>
            <div class="question-text">
                计算极限：\(\lim_{x \to 0} \frac{\tan 2x}{\sin 5x}\)
            </div>
            <div class="options">
                <div class="option">A. 0</div>
                <div class="option" data-correct="true">B. \(\frac{2}{5}\)</div>
                <div class="option">C. 1</div>
                <div class="option">D. \(\infty\)</div>
            </div>
            <button class="show-explanation">查看解析</button>
            <div class="explanation">
                <p><strong>正确答案：B</strong></p>
                <p><strong>解析：</strong></p>
                <p>当 \(x \to 0\) 时，\(\tan x \sim x\)，\(\sin x \sim x\)，所以：</p>
                <div class="math-expression">
                    \(\lim_{x \to 0} \frac{\tan 2x}{\sin 5x} = \lim_{x \to 0} \frac{2x}{5x} = \frac{2}{5}\)
                </div>
                <div class="key-point">
                    <strong>关键点：</strong>等价无穷小替换 \(\tan x \sim x\)，\(\sin x \sim x\) (当 \(x \to 0\) 时)。
                </div>
            </div>
        </div>
        
        <div class="question-card">
            <div class="question-header">
                <span class="question-number">3</span>
                <span class="question-type">重要极限</span>
            </div>
            <div class="question-text">
                计算极限：\(\lim_{x \to \infty} \left(1 + \frac{2}{x}\right)^{3x}\)
            </div>
            <div class="options">
                <div class="option">A. 1</div>
                <div class="option">B. \(e^2\)</div>
                <div class="option" data-correct="true">C. \(e^6\)</div>
                <div class="option">D. \(e^8\)</div>
            </div>
            <button class="show-explanation">查看解析</button>
            <div class="explanation">
                <p><strong>正确答案：C</strong></p>
                <p><strong>解析：</strong></p>
                <p>利用重要极限 \(\lim_{x \to \infty} \left(1 + \frac{1}{x}\right)^x = e\)，我们有：</p>
                <div class="math-expression">
                    \(\lim_{x \to \infty} \left(1 + \frac{2}{x}\right)^{3x} = \lim_{x \to \infty} \left[\left(1 + \frac{2}{x}\right)^{\frac{x}{2}}\right]^{6} = e^6\)
                </div>
                <div class="key-point">
                    <strong>关键点：</strong>重要极限 \(\lim_{x \to \infty} \left(1 + \frac{1}{x}\right)^x = e\) 的变形应用。
                </div>
            </div>
        </div>
        
        <div class="question-card">
            <div class="question-header">
                <span class="question-number">4</span>
                <span class="question-type">等价无穷小</span>
            </div>
            <div class="question-text">
                计算极限：\(\lim_{x \to 0} \frac{\ln(1 + 3x)}{2x}\)
            </div>
            <div class="options">
                <div class="option">A. 0</div>
                <div class="option">B. 1</div>
                <div class="option" data-correct="true">C. \(\frac{3}{2}\)</div>
                <div class="option">D. \(\infty\)</div>
            </div>
            <button class="show-explanation">查看解析</button>
            <div class="explanation">
                <p><strong>正确答案：C</strong></p>
                <p><strong>解析：</strong></p>
                <p>当 \(x \to 0\) 时，\(\ln(1 + x) \sim x\)，所以：</p>
                <div class="math-expression">
                    \(\lim_{x \to 0} \frac{\ln(1 + 3x)}{2x} = \lim_{x \to 0} \frac{3x}{2x} = \frac{3}{2}\)
                </div>
                <div class="key-point">
                    <strong>关键点：</strong>等价无穷小替换 \(\ln(1 + x) \sim x\) (当 \(x \to 0\) 时)。
                </div>
            </div>
        </div>
        
        <div class="question-card">
            <div class="question-header">
                <span class="question-number">5</span>
                <span class="question-type">重要极限</span>
            </div>
            <div class="question-text">
                计算极限：\(\lim_{x \to 0} \frac{1 - \cos 2x}{x^2}\)
            </div>
            <div class="options">
                <div class="option">A. 0</div>
                <div class="option">B. 1</div>
                <div class="option" data-correct="true">C. 2</div>
                <div class="option">D. 4</div>
            </div>
            <button class="show-explanation">查看解析</button>
            <div class="explanation">
                <p><strong>正确答案：C</strong></p>
                <p><strong>解析：</strong></p>
                <p>方法一：使用等价无穷小，当 \(x \to 0\) 时，\(1 - \cos x \sim \frac{1}{2}x^2\)，所以：</p>
                <div class="math-expression">
                    \(\lim_{x \to 0} \frac{1 - \cos 2x}{x^2} = \lim_{x \to 0} \frac{\frac{1}{2}(2x)^2}{x^2} = \lim_{x \to 0} \frac{2x^2}{x^2} = 2\)
                </div>
                <p>方法二：使用三角恒等式 \(1 - \cos 2x = 2\sin^2 x\)：</p>
                <div class="math-expression">
                    \(\lim_{x \to 0} \frac{1 - \cos 2x}{x^2} = \lim_{x \to 0} \frac{2\sin^2 x}{x^2} = 2 \lim_{x \to 0} \left(\frac{\sin x}{x}\right)^2 = 2 \times 1^2 = 2\)
                </div>
                <div class="key-point">
                    <strong>关键点：</strong>等价无穷小 \(1 - \cos x \sim \frac{1}{2}x^2\) (当 \(x \to 0\) 时)。
                </div>
            </div>
        </div>
        
        <div class="category-header">第二部分：连续性判断</div>
        
        <div class="question-card">
            <div class="question-header">
                <span class="question-number">6</span>
                <span class="question-type">连续性</span>
            </div>
            <div class="question-text">
                函数 \(f(x) = \frac{x^2 - 1}{x - 1}\) 在 \(x = 1\) 处的连续性如何？
            </div>
            <div class="options">
                <div class="option">A. 连续</div>
                <div class="option" data-correct="true">B. 可去间断点</div>
                <div class="option">C. 跳跃间断点</div>
                <div class="option">D. 无穷间断点</div>
            </div>
            <button class="show-explanation">查看解析</button>
            <div class="explanation">
                <p><strong>正确答案：B</strong></p>
                <p><strong>解析：</strong></p>
                <p>函数在 \(x = 1\) 处无定义，但极限存在：</p>
                <div class="math-expression">
                    \(\lim_{x \to 1} f(x) = \lim_{x \to 1} \frac{x^2 - 1}{x - 1} = \lim_{x \to 1} (x + 1) = 2\)
                </div>
                <p>由于极限存在但函数在该点无定义，所以 \(x = 1\) 是可去间断点。</p>
                <div class="key-point">
                    <strong>关键点：</strong>可去间断点的特征是极限存在但函数在该点无定义或函数值不等于极限值。
                </div>
            </div>
        </div>
        
        <div class="question-card">
            <div class="question-header">
                <span class="question-number">7</span>
                <span class="question-type">连续性</span>
            </div>
            <div class="question-text">
                函数 \(f(x) = \begin{cases} 
                \frac{\sin x}{x}, & x \neq 0 \\
                1, & x = 0 
                \end{cases}\) 在 \(x = 0\) 处是否连续？
            </div>
            <div class="options">
                <div class="option" data-correct="true">A. 连续</div>
                <div class="option">B. 不连续</div>
                <div class="option">C. 无法判断</div>
                <div class="option">D. 仅左连续</div>
            </div>
            <button class="show-explanation">查看解析</button>
            <div class="explanation">
                <p><strong>正确答案：A</strong></p>
                <p><strong>解析：</strong></p>
                <p>我们需要检查三个条件：</p>
                <ol>
                    <li>函数在 \(x = 0\) 有定义：\(f(0) = 1\)</li>
                    <li>极限 \(\lim_{x \to 0} f(x)\) 存在：\(\lim_{x \to 0} \frac{\sin x}{x} = 1\)</li>
                    <li>函数值等于极限值：\(f(0) = \lim_{x \to 0} f(x) = 1\)</li>
                </ol>
                <p>三个条件都满足，因此函数在 \(x = 0\) 处连续。</p>
                <div class="key-point">
                    <strong>关键点：</strong>函数在某点连续需要满足：1) 函数在该点有定义；2) 极限存在；3) 函数值等于极限值。
                </div>
            </div>
        </div>
        
        <div class="question-card">
            <div class="question-header">
                <span class="question-number">8</span>
                <span class="question-type">连续性</span>
            </div>
            <div class="question-text">
                函数 \(f(x) = \begin{cases} 
                x^2, & x \leq 1 \\
                2x - 1, & x > 1 
                \end{cases}\) 在 \(x = 1\) 处是否连续？
            </div>
            <div class="options">
                <div class="option" data-correct="true">A. 连续</div>
                <div class="option">B. 不连续</div>
                <div class="option">C. 无法判断</div>
                <div class="option">D. 仅右连续</div>
            </div>
            <button class="show-explanation">查看解析</button>
            <div class="explanation">
                <p><strong>正确答案：A</strong></p>
                <p><strong>解析：</strong></p>
                <p>我们需要检查：</p>
                <ul>
                    <li>左极限：\(\lim_{x \to 1^-} f(x) = \lim_{x \to 1^-} x^2 = 1\)</li>
                    <li>右极限：\(\lim_{x \to 1^+} f(x) = \lim_{x \to 1^+} (2x - 1) = 1\)</li>
                    <li>函数值：\(f(1) = 1^2 = 1\)</li>
                </ul>
                <p>由于左极限、右极限和函数值都相等，所以函数在 \(x = 1\) 处连续。</p>
                <div class="key-point">
                    <strong>关键点：</strong>分段函数在分段点处的连续性需要检查左极限、右极限和函数值是否相等。
                </div>
            </div>
        </div>
        
        <div class="category-header">第三部分：极限存在性判断</div>
        
        <div class="question-card">
            <div class="question-header">
                <span class="question-number">9</span>
                <span class="question-type">极限存在性</span>
            </div>
            <div class="question-text">
                判断极限 \(\lim_{x \to 0} \frac{|x|}{x}\) 是否存在？
            </div>
            <div class="options">
                <div class="option">A. 存在，值为 0</div>
                <div class="option">B. 存在，值为 1</div>
                <div class="option">C. 存在，值为 -1</div>
                <div class="option" data-correct="true">D. 不存在</div>
            </div>
            <button class="show-explanation">查看解析</button>
            <div class="explanation">
                <p><strong>正确答案：D</strong></p>
                <p><strong>解析：</strong></p>
                <p>考虑左右极限：</p>
                <ul>
                    <li>右极限：\(\lim_{x \to 0^+} \frac{|x|}{x} = \lim_{x \to 0^+} \frac{x}{x} = 1\)</li>
                    <li>左极限：\(\lim_{x \to 0^-} \frac{|x|}{x} = \lim_{x \to 0^-} \frac{-x}{x} = -1\)</li>
                </ul>
                <p>由于左右极限不相等，所以极限不存在。</p>
                <div class="key-point">
                    <strong>关键点：</strong>极限存在的充要条件是左右极限存在且相等。
                </div>
            </div>
        </div>
        
        <div class="question-card">
            <div class="question-header">
                <span class="question-number">10</span>
                <span class="question-type">极限存在性</span>
            </div>
            <div class="question-text">
                判断极限 \(\lim_{x \to 0} x \sin \frac{1}{x}\) 是否存在？
            </div>
            <div class="options">
                <div class="option" data-correct="true">A. 存在，值为 0</div>
                <div class="option">B. 存在，值为 1</div>
                <div class="option">C. 不存在</div>
                <div class="option">D. 无法判断</div>
            </div>
            <button class="show-explanation">查看解析</button>
            <div class="explanation">
                <p><strong>正确答案：A</strong></p>
                <p><strong>解析：</strong></p>
                <p>使用夹逼定理：</p>
                <p>由于 \(-1 \leq \sin \frac{1}{x} \leq 1\)，所以 \(-|x| \leq x \sin \frac{1}{x} \leq |x|\)</p>
                <p>而 \(\lim_{x \to 0} (-|x|) = 0\)，\(\lim_{x \to 0} |x| = 0\)</p>
                <p>由夹逼定理得：\(\lim_{x \to 0} x \sin \frac{1}{x} = 0\)</p>
                <div class="key-point">
                    <strong>关键点：</strong>对于振荡函数乘以无穷小量，可以使用夹逼定理判断极限。
                </div>
            </div>
        </div>
        
        <div class="question-card">
            <div class="question-header">
                <span class="question-number">11</span>
                <span class="question-type">极限存在性</span>
            </div>
            <div class="question-text">
                判断极限 \(\lim_{x \to 0} \frac{1}{x}\) 是否存在？
            </div>
            <div class="options">
                <div class="option">A. 存在，值为 0</div>
                <div class="option">B. 存在，值为 1</div>
                <div class="option">C. 存在，值为 \(\infty\)</div>
                <div class="option" data-correct="true">D. 不存在</div>
            </div>
            <button class="show-explanation">查看解析</button>
            <div class="explanation">
                <p><strong>正确答案：D</strong></p>
                <p><strong>解析：</strong></p>
                <p>考虑左右极限：</p>
                <ul>
                    <li>右极限：\(\lim_{x \to 0^+} \frac{1}{x} = +\infty\)</li>
                    <li>左极限：\(\lim_{x \to 0^-} \frac{1}{x} = -\infty\)</li>
                </ul>
                <p>由于左右极限都不存在（为无穷大），且符号不同，所以极限不存在。</p>
                <div class="key-point">
                    <strong>关键点：</strong>当左右极限至少有一个为无穷大时，极限不存在。
                </div>
            </div>
        </div>
        
        <div class="question-card">
            <div class="question-header">
                <span class="question-number">12</span>
                <span class="question-type">极限存在性</span>
            </div>
            <div class="question-text">
                判断极限 \(\lim_{x \to 0} \frac{x^2 \sin \frac{1}{x}}{\sin x}\) 是否存在？
            </div>
            <div class="options">
                <div class="option" data-correct="true">A. 存在，值为 0</div>
                <div class="option">B. 存在，值为 1</div>
                <div class="option">C. 不存在</div>
                <div class="option">D. 无法判断</div>
            </div>
            <button class="show-explanation">查看解析</button>
            <div class="explanation">
                <p><strong>正确答案：A</strong></p>
                <p><strong>解析：</strong></p>
                <p>使用等价无穷小和夹逼定理：</p>
                <p>当 \(x \to 0\) 时，\(\sin x \sim x\)，所以：</p>
                <div class="math-expression">
                    \(\lim_{x \to 0} \frac{x^2 \sin \frac{1}{x}}{\sin x} = \lim_{x \to 0} \frac{x^2 \sin \frac{1}{x}}{x} = \lim_{x \to 0} x \sin \frac{1}{x}\)
                </div>
                <p>由于 \(-1 \leq \sin \frac{1}{x} \leq 1\)，所以 \(-|x| \leq x \sin \frac{1}{x} \leq |x|\)</p>
                <p>而 \(\lim_{x \to 0} (-|x|) = 0\)，\(\lim_{x \to 0} |x| = 0\)</p>
                <p>由夹逼定理得：\(\lim_{x \to 0} x \sin \frac{1}{x} = 0\)</p>
                <div class="key-point">
                    <strong>关键点：</strong>结合等价无穷小替换和夹逼定理解决复杂极限问题。
                </div>
            </div>
        </div>
        
        <div class="category-header">第四部分：综合应用题</div>
        
        <div class="question-card">
            <div class="question-header">
                <span class="question-number">13</span>
                <span class="question-type">综合应用</span>
            </div>
            <div class="question-text">
                计算极限：\(\lim_{x \to 0} \frac{e^{2x} - 1}{\ln(1 + 3x)}\)
            </div>
            <div class="options">
                <div class="option">A. 0</div>
                <div class="option">B. 1</div>
                <div class="option" data-correct="true">C. \(\frac{2}{3}\)</div>
                <div class="option">D. \(\infty\)</div>
            </div>
            <button class="show-explanation">查看解析</button>
            <div class="explanation">
                <p><strong>正确答案：C</strong></p>
                <p><strong>解析：</strong></p>
                <p>使用等价无穷小：</p>
                <p>当 \(x \to 0\) 时，\(e^x - 1 \sim x\)，\(\ln(1 + x) \sim x\)，所以：</p>
                <div class="math-expression">
                    \(\lim_{x \to 0} \frac{e^{2x} - 1}{\ln(1 + 3x)} = \lim_{x \to 0} \frac{2x}{3x} = \frac{2}{3}\)
                </div>
                <div class="key-point">
                    <strong>关键点：</strong>等价无穷小 \(e^x - 1 \sim x\)，\(\ln(1 + x) \sim x\) (当 \(x \to 0\) 时)。
                </div>
            </div>
        </div>
        
        <div class="question-card">
            <div class="question-header">
                <span class="question-number">14</span>
                <span class="question-type">综合应用</span>
            </div>
            <div class="question-text">
                计算极限：\(\lim_{x \to 0} \frac{\sqrt{1 + x} - \sqrt{1 - x}}{x}\)
            </div>
            <div class="options">
                <div class="option">A. 0</div>
                <div class="option" data-correct="true">B. 1</div>
                <div class="option">C. 2</div>
                <div class="option">D. \(\infty\)</div>
            </div>
            <button class="show-explanation">查看解析</button>
            <div class="explanation">
                <p><strong>正确答案：B</strong></p>
                <p><strong>解析：</strong></p>
                <p>方法一：有理化分子</p>
                <div class="math-expression">
                    \(\lim_{x \to 0} \frac{\sqrt{1 + x} - \sqrt{1 - x}}{x} = \lim_{x \to 0} \frac{(1 + x) - (1 - x)}{x(\sqrt{1 + x} + \sqrt{1 - x})} = \lim_{x \to 0} \frac{2x}{x(\sqrt{1 + x} + \sqrt{1 - x})} = \lim_{x \to 0} \frac{2}{\sqrt{1 + x} + \sqrt{1 - x}} = \frac{2}{1 + 1} = 1\)
                </div>
                <p>方法二：使用等价无穷小 \((1 + x)^a - 1 \sim ax\) (当 \(x \to 0\) 时)</p>
                <div class="math-expression">
                    \(\lim_{x \to 0} \frac{\sqrt{1 + x} - \sqrt{1 - x}}{x} = \lim_{x \to 0} \frac{[(1 + x)^{\frac{1}{2}} - 1] - [(1 - x)^{\frac{1}{2}} - 1]}{x} = \lim_{x \to 0} \frac{\frac{1}{2}x - (-\frac{1}{2}x)}{x} = \lim_{x \to 0} \frac{x}{x} = 1\)
                </div>
                <div class="key-point">
                    <strong>关键点：</strong>根式差可以使用有理化或等价无穷小 \((1 + x)^a - 1 \sim ax\) 处理。
                </div>
            </div>
        </div>
        
        <div class="question-card">
            <div class="question-header">
                <span class="question-number">15</span>
                <span class="question-type">综合应用</span>
            </div>
            <div class="question-text">
                计算极限：\(\lim_{x \to 0} \frac{\arctan 2x}{\sin 3x}\)
            </div>
            <div class="options">
                <div class="option">A. 0</div>
                <div class="option">B. 1</div>
                <div class="option" data-correct="true">C. \(\frac{2}{3}\)</div>
                <div class="option">D. \(\infty\)</div>
            </div>
            <button class="show-explanation">查看解析</button>
            <div class="explanation">
                <p><strong>正确答案：C</strong></p>
                <p><strong>解析：</strong></p>
                <p>使用等价无穷小：</p>
                <p>当 \(x \to 0\) 时，\(\arctan x \sim x\)，\(\sin x \sim x\)，所以：</p>
                <div class="math-expression">
                    \(\lim_{x \to 0} \frac{\arctan 2x}{\sin 3x} = \lim_{x \to 0} \frac{2x}{3x} = \frac{2}{3}\)
                </div>
                <div class="key-point">
                    <strong>关键点：</strong>等价无穷小 \(\arctan x \sim x\)，\(\sin x \sim x\) (当 \(x \to 0\) 时)。
                </div>
            </div>
        </div>
        
        <div class="summary">
            <h2>微积分极限知识点总结</h2>
            <table class="concept-table">
                <thead>
                    <tr>
                        <th>类别</th>
                        <th>重要公式/概念</th>
                        <th>应用场景</th>
                    </tr>
                </thead>
                <tbody>
                    <tr>
                        <td>重要极限</td>
                        <td>\(\lim_{x \to 0} \frac{\sin x}{x} = 1\)<br>\(\lim_{x \to \infty} (1 + \frac{1}{x})^x = e\)</td>
                        <td>三角函数极限、指数函数极限</td>
                    </tr>
                    <tr>
                        <td>等价无穷小</td>
                        <td>\(\sin x \sim x\)<br>\(\tan x \sim x\)<br>\(1 - \cos x \sim \frac{1}{2}x^2\)<br>\(\ln(1 + x) \sim x\)<br>\(e^x - 1 \sim x\)<br>\((1 + x)^a - 1 \sim ax\)</td>
                        <td>简化极限计算，替换复杂表达式</td>
                    </tr>
                    <tr>
                        <td>连续性</td>
                        <td>\(\lim_{x \to a} f(x) = f(a)\)</td>
                        <td>判断函数在某点是否连续</td>
                    </tr>
                    <tr>
                        <td>极限存在性</td>
                        <td>左右极限存在且相等</td>
                        <td>判断极限是否存在，特别是分段函数和含绝对值函数</td>
                    </tr>
                    <tr>
                        <td>夹逼定理</td>
                        <td>若 \(g(x) \leq f(x) \leq h(x)\) 且 \(\lim g(x) = \lim h(x) = L\)，则 \(\lim f(x) = L\)</td>
                        <td>处理振荡函数与无穷小量的乘积</td>
                    </tr>
                </tbody>
            </table>
            <div class="key-point">
                <strong>学习建议：</strong>掌握这些核心概念和公式，并通过大量练习熟悉各种极限计算技巧。特别注意等价无穷小的使用条件和夹逼定理的应用场景。
            </div>
        </div>
    </div>

    <script>
        document.addEventListener('DOMContentLoaded', function() {
            // 设置选项点击事件
            document.querySelectorAll('.option').forEach(option => {
                option.addEventListener('click', function() {
                    const card = this.closest('.question-card');
                    card.querySelectorAll('.option').forEach(opt => {
                        opt.classList.remove('selected');
                    });
                    this.classList.add('selected');
                    
                    // 如果点击了正确答案，显示解析
                    if (this.getAttribute('data-correct') === 'true') {
                        const explanation = card.querySelector('.explanation');
                        const button = card.querySelector('.show-explanation');
                        explanation.classList.add('active');
                        button.textContent = '隐藏解析';
                    }
                });
            });
            
            // 设置显示解析按钮事件
            document.querySelectorAll('.show-explanation').forEach(button => {
                button.addEventListener('click', function() {
                    const explanation = this.nextElementSibling;
                    explanation.classList.toggle('active');
                    this.textContent = explanation.classList.contains('active') ? '隐藏解析' : '查看解析';
                });
            });
            
            // 初始化MathJax
            if (window.MathJax) {
                window.MathJax.typeset();
            }
        });
    </script>
</body>
</html>
