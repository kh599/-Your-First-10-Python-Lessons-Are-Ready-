<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>First 10 Python Lessons</title>
    <style>
        @import url('https://fonts.googleapis.com/css2?family=Fira+Code:wght@400;500;700&family=Inter:wght@400;600;700&display=swap');
        
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }
        
        body {
            font-family: 'Inter', sans-serif;
            background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
            padding: 20px;
            color: #333;
            line-height: 1.6;
        }
        
        .container {
            max-width: 1200px;
            margin: 0 auto;
            background: white;
            border-radius: 15px;
            padding: 40px;
            box-shadow: 0 20px 60px rgba(0,0,0,0.3);
        }
        
        .header {
            text-align: center;
            margin-bottom: 40px;
            padding-bottom: 25px;
            border-bottom: 4px solid #667eea;
        }
        
        .header h1 {
            font-size: 2.8em;
            color: #667eea;
            margin-bottom: 10px;
        }
        
        .header p {
            font-size: 1.2em;
            color: #666;
        }
        
        .lesson {
            margin-bottom: 40px;
            border-left: 5px solid #667eea;
            padding-left: 25px;
        }
        
        .lesson-header {
            background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
            color: white;
            padding: 20px 25px;
            border-radius: 10px;
            margin-bottom: 20px;
            margin-left: -30px;
        }
        
        .lesson-number {
            font-size: 2em;
            font-weight: 700;
            margin-bottom: 5px;
        }
        
        .lesson-title {
            font-size: 1.5em;
            font-weight: 600;
        }
        
        .lesson-content {
            background: #f8f9fa;
            padding: 25px;
            border-radius: 10px;
            margin-bottom: 20px;
        }
        
        .what-it-does {
            background: #e3f2fd;
            border-left: 4px solid #2196F3;
            padding: 15px;
            margin: 15px 0;
            border-radius: 5px;
        }
        
        .what-it-does-title {
            font-weight: 700;
            color: #1976D2;
            margin-bottom: 8px;
            font-size: 1.1em;
        }
        
        .code-block {
            background: #1e1e1e;
            color: #d4d4d4;
            padding: 20px;
            border-radius: 8px;
            font-family: 'Fira Code', monospace;
            font-size: 0.95em;
            overflow-x: auto;
            margin: 15px 0;
            border: 2px solid #333;
        }
        
        .code-comment {
            color: #6a9955;
        }
        
        .code-keyword {
            color: #569cd6;
        }
        
        .code-string {
            color: #ce9178;
        }
        
        .code-function {
            color: #dcdcaa;
        }
        
        .code-number {
            color: #b5cea8;
        }
        
        .real-world {
            background: #fff3cd;
            border-left: 4px solid #ffc107;
            padding: 15px;
            margin: 15px 0;
            border-radius: 5px;
        }
        
        .real-world-title {
            font-weight: 700;
            color: #ff6f00;
            margin-bottom: 8px;
            font-size: 1.05em;
        }
        
        .practice {
            background: #f1f8e9;
            border-left: 4px solid #4caf50;
            padding: 15px;
            margin: 15px 0;
            border-radius: 5px;
        }
        
        .practice-title {
            font-weight: 700;
            color: #2e7d32;
            margin-bottom: 8px;
            font-size: 1.05em;
        }
        
        .tip-box {
            background: #fce4ec;
            border-left: 4px solid #e91e63;
            padding: 15px;
            margin: 15px 0;
            border-radius: 5px;
        }
        
        .tip-title {
            font-weight: 700;
            color: #c2185b;
            margin-bottom: 8px;
            font-size: 1.05em;
        }
        
        @media (max-width: 768px) {
            .container {
                padding: 20px;
            }
            
            .header h1 {
                font-size: 2em;
            }
            
            .code-block {
                font-size: 0.85em;
                padding: 15px;
            }
        }
    </style>
</head>
<body>
    <div class="container">
        <div class="header">
            <h1>🐍 First 10 Python Lessons</h1>
            <p>From Complete Zero to Writing Real Code</p>
        </div>

        <!-- LESSON 1 -->
        <div class="lesson">
            <div class="lesson-header">
                <div class="lesson-number">LESSON 1</div>
                <div class="lesson-title">Print & Output - Your First Code!</div>
            </div>
            
            <div class="lesson-content">
                <div class="what-it-does">
                    <div class="what-it-does-title">🎯 What It Does:</div>
                    Shows messages/results on your screen. Think of it like "speaking" to the user. Every program needs to communicate what it's doing!
                </div>
                
                <div class="code-block">
<span class="code-comment"># Your first Python code!</span>
<span class="code-function">print</span>(<span class="code-string">"Hello, World!"</span>)
<span class="code-function">print</span>(<span class="code-string">"My name is Khaled"</span>)
<span class="code-function">print</span>(<span class="code-string">"I'm learning Python!"</span>)

<span class="code-comment"># Print numbers</span>
<span class="code-function">print</span>(<span class="code-number">100</span>)
<span class="code-function">print</span>(<span class="code-number">2026</span>)

<span class="code-comment"># Print calculations</span>
<span class="code-function">print</span>(<span class="code-number">5 + 3</span>)  <span class="code-comment"># Shows: 8</span>
<span class="code-function">print</span>(<span class="code-number">10 * 2</span>)  <span class="code-comment"># Shows: 20</span>
                </div>
                
                <div class="real-world">
                    <div class="real-world-title">💼 Real-World Use:</div>
                    • Showing results to users (calculators, apps)<br>
                    • Debugging - see what your code is doing<br>
                    • Displaying data analysis results<br>
                    • Creating text-based interfaces
                </div>
                
                <div class="practice">
                    <div class="practice-title">✏️ Practice Exercise:</div>
                    Print your name, age, city, and your AI career goal!
                </div>
            </div>
        </div>

        <!-- LESSON 2 -->
        <div class="lesson">
            <div class="lesson-header">
                <div class="lesson-number">LESSON 2</div>
                <div class="lesson-title">Variables - Storing Information</div>
            </div>
            
            <div class="lesson-content">
                <div class="what-it-does">
                    <div class="what-it-does-title">🎯 What It Does:</div>
                    Variables are like labeled boxes that store data. Instead of typing "Khaled" everywhere, store it once in a variable and reuse it!
                </div>
                
                <div class="code-block">
<span class="code-comment"># Creating variables (like creating boxes with labels)</span>
name = <span class="code-string">"Khaled"</span>
age = <span class="code-number">21</span>
city = <span class="code-string">"Kajang"</span>
is_learning_ai = <span class="code-keyword">True</span>

<span class="code-comment"># Using variables</span>
<span class="code-function">print</span>(name)
<span class="code-function">print</span>(<span class="code-string">"I am"</span>, age, <span class="code-string">"years old"</span>)
<span class="code-function">print</span>(<span class="code-string">"I live in"</span>, city)

<span class="code-comment"># Variables can change!</span>
score = <span class="code-number">10</span>
<span class="code-function">print</span>(score)  <span class="code-comment"># Shows: 10</span>
score = <span class="code-number">20</span>
<span class="code-function">print</span>(score)  <span class="code-comment"># Shows: 20</span>

<span class="code-comment"># Math with variables</span>
hours_studied = <span class="code-number">100</span>
months = <span class="code-number">1</span>
hours_per_month = hours_studied / months
<span class="code-function">print</span>(<span class="code-string">"Hours per month:"</span>, hours_per_month)
                </div>
                
                <div class="real-world">
                    <div class="real-world-title">💼 Real-World Use:</div>
                    • Storing user information (username, email, password)<br>
                    • Keeping track of game scores, prices, quantities<br>
                    • Holding data for calculations and processing<br>
                    • AI: Storing model parameters, training data
                </div>
                
                <div class="practice">
                    <div class="practice-title">✏️ Practice Exercise:</div>
                    Create variables for: your favorite AI tool, hours you studied today, your dream salary, and print them in a sentence!
                </div>
            </div>
        </div>

        <!-- LESSON 3 -->
        <div class="lesson">
            <div class="lesson-header">
                <div class="lesson-number">LESSON 3</div>
                <div class="lesson-title">Data Types - Different Kinds of Data</div>
            </div>
            
            <div class="lesson-content">
                <div class="what-it-does">
                    <div class="what-it-does-title">🎯 What It Does:</div>
                    Different types of data need different handling. Text, numbers, true/false - each has its purpose!
                </div>
                
                <div class="code-block">
<span class="code-comment"># String (text) - use quotes</span>
name = <span class="code-string">"Khaled Ahmed"</span>
email = <span class="code-string">"khaled.ameen599@gmail.com"</span>

<span class="code-comment"># Integer (whole numbers)</span>
age = <span class="code-number">21</span>
certifications = <span class="code-number">7</span>
grade = <span class="code-number">100</span>

<span class="code-comment"># Float (decimal numbers)</span>
average_grade = <span class="code-number">99.5</span>
hours_studied = <span class="code-number">100.5</span>

<span class="code-comment"># Boolean (True or False)</span>
is_learning = <span class="code-keyword">True</span>
has_job = <span class="code-keyword">False</span>
knows_python = <span class="code-keyword">True</span>

<span class="code-comment"># Check what type something is</span>
<span class="code-function">print</span>(<span class="code-function">type</span>(name))        <span class="code-comment"># &lt;class 'str'&gt;</span>
<span class="code-function">print</span>(<span class="code-function">type</span>(age))         <span class="code-comment"># &lt;class 'int'&gt;</span>
<span class="code-function">print</span>(<span class="code-function">type</span>(is_learning)) <span class="code-comment"># &lt;class 'bool'&gt;</span>
                </div>
                
                <div class="real-world">
                    <div class="real-world-title">💼 Real-World Use:</div>
                    • Strings: Names, addresses, descriptions, AI prompts<br>
                    • Integers: Counts, IDs, quantities, age<br>
                    • Floats: Prices, measurements, percentages, AI model accuracy<br>
                    • Booleans: Settings on/off, user logged in?, feature enabled?
                </div>
                
                <div class="tip-box">
                    <div class="tip-title">💡 Common Mistake:</div>
                    <code>"100"</code> is text, but <code>100</code> is a number! You can't do math with text numbers until you convert them.
                </div>
            </div>
        </div>

        <!-- LESSON 4 -->
        <div class="lesson">
            <div class="lesson-header">
                <div class="lesson-number">LESSON 4</div>
                <div class="lesson-title">User Input - Getting Information</div>
            </div>
            
            <div class="lesson-content">
                <div class="what-it-does">
                    <div class="what-it-does-title">🎯 What It Does:</div>
                    Ask the user questions and store their answers. Makes your programs interactive!
                </div>
                
                <div class="code-block">
<span class="code-comment"># Ask for input</span>
name = <span class="code-function">input</span>(<span class="code-string">"What is your name? "</span>)
<span class="code-function">print</span>(<span class="code-string">"Hello,"</span>, name)

<span class="code-comment"># Get numbers (need to convert!)</span>
age_text = <span class="code-function">input</span>(<span class="code-string">"How old are you? "</span>)
age = <span class="code-function">int</span>(age_text)  <span class="code-comment"># Convert text to integer</span>
<span class="code-function">print</span>(<span class="code-string">"Next year you'll be"</span>, age + <span class="code-number">1</span>)

<span class="code-comment"># Shorter way (convert immediately)</span>
hours = <span class="code-function">int</span>(<span class="code-function">input</span>(<span class="code-string">"Hours studied today? "</span>))
<span class="code-function">print</span>(<span class="code-string">"Great! You studied"</span>, hours, <span class="code-string">"hours!"</span>)

<span class="code-comment"># Simple calculator</span>
num1 = <span class="code-function">float</span>(<span class="code-function">input</span>(<span class="code-string">"Enter first number: "</span>))
num2 = <span class="code-function">float</span>(<span class="code-function">input</span>(<span class="code-string">"Enter second number: "</span>))
result = num1 + num2
<span class="code-function">print</span>(<span class="code-string">"Sum:"</span>, result)
                </div>
                
                <div class="real-world">
                    <div class="real-world-title">💼 Real-World Use:</div>
                    • Login forms (username, password)<br>
                    • Calculators and tools<br>
                    • Chatbots asking questions<br>
                    • Data entry applications<br>
                    • AI: Collecting training data, user preferences
                </div>
                
                <div class="practice">
                    <div class="practice-title">✏️ Practice Exercise:</div>
                    Build a simple profile creator: Ask for name, age, city, favorite AI tool, and display a summary!
                </div>
            </div>
        </div>

        <!-- LESSON 5 -->
        <div class="lesson">
            <div class="lesson-header">
                <div class="lesson-number">LESSON 5</div>
                <div class="lesson-title">If Statements - Making Decisions</div>
            </div>
            
            <div class="lesson-content">
                <div class="what-it-does">
                    <div class="what-it-does-title">🎯 What It Does:</div>
                    Make your program do different things based on conditions. Like saying "IF this, THEN do that!"
                </div>
                
                <div class="code-block">
<span class="code-comment"># Simple if statement</span>
age = <span class="code-function">int</span>(<span class="code-function">input</span>(<span class="code-string">"Enter your age: "</span>))

<span class="code-keyword">if</span> age >= <span class="code-number">18</span>:
    <span class="code-function">print</span>(<span class="code-string">"You're an adult!"</span>)

<span class="code-comment"># If-else (two options)</span>
grade = <span class="code-function">int</span>(<span class="code-function">input</span>(<span class="code-string">"Enter your grade: "</span>))

<span class="code-keyword">if</span> grade >= <span class="code-number">90</span>:
    <span class="code-function">print</span>(<span class="code-string">"Excellent! A grade!"</span>)
<span class="code-keyword">else</span>:
    <span class="code-function">print</span>(<span class="code-string">"Keep studying!"</span>)

<span class="code-comment"># If-elif-else (multiple options)</span>
score = <span class="code-function">int</span>(<span class="code-function">input</span>(<span class="code-string">"Test score: "</span>))

<span class="code-keyword">if</span> score >= <span class="code-number">90</span>:
    <span class="code-function">print</span>(<span class="code-string">"Grade: A"</span>)
<span class="code-keyword">elif</span> score >= <span class="code-number">80</span>:
    <span class="code-function">print</span>(<span class="code-string">"Grade: B"</span>)
<span class="code-keyword">elif</span> score >= <span class="code-number">70</span>:
    <span class="code-function">print</span>(<span class="code-string">"Grade: C"</span>)
<span class="code-keyword">else</span>:
    <span class="code-function">print</span>(<span class="code-string">"Keep trying!"</span>)

<span class="code-comment"># Multiple conditions (and, or)</span>
hours_studied = <span class="code-number">5</span>
has_python = <span class="code-keyword">True</span>

<span class="code-keyword">if</span> hours_studied > <span class="code-number">3</span> <span class="code-keyword">and</span> has_python:
    <span class="code-function">print</span>(<span class="code-string">"You're making great progress!"</span>)
                </div>
                
                <div class="real-world">
                    <div class="real-world-title">💼 Real-World Use:</div>
                    • User authentication (if password correct, login)<br>
                    • E-commerce (if in stock, allow purchase)<br>
                    • AI: If accuracy > 90%, save model<br>
                    • Game logic (if health = 0, game over)<br>
                    • Form validation (if email valid, proceed)
                </div>
                
                <div class="practice">
                    <div class="practice-title">✏️ Practice Exercise:</div>
                    Build an AI readiness checker: Ask hours studied, certifications completed. If hours > 50 AND certs > 3, print "Job ready!", else give encouragement!
                </div>
            </div>
        </div>

        <!-- LESSON 6 -->
        <div class="lesson">
            <div class="lesson-header">
                <div class="lesson-number">LESSON 6</div>
                <div class="lesson-title">Lists - Storing Multiple Items</div>
            </div>
            
            <div class="lesson-content">
                <div class="what-it-does">
                    <div class="what-it-does-title">🎯 What It Does:</div>
                    Store multiple items in one variable. Like a shopping list or playlist!
                </div>
                
                <div class="code-block">
<span class="code-comment"># Create a list</span>
certifications = [<span class="code-string">"IBM AI"</span>, <span class="code-string">"Google AI"</span>, <span class="code-string">"NVIDIA"</span>]
grades = [<span class="code-number">100</span>, <span class="code-number">100</span>, <span class="code-number">92</span>, <span class="code-number">100</span>]

<span class="code-comment"># Access items (starts at 0!)</span>
<span class="code-function">print</span>(certifications[<span class="code-number">0</span>])  <span class="code-comment"># First item: "IBM AI"</span>
<span class="code-function">print</span>(grades[<span class="code-number">2</span>])          <span class="code-comment"># Third item: 92</span>

<span class="code-comment"># Add items</span>
ai_tools = [<span class="code-string">"ChatGPT"</span>, <span class="code-string">"Claude"</span>]
ai_tools.<span class="code-function">append</span>(<span class="code-string">"Gemini"</span>)
<span class="code-function">print</span>(ai_tools)  <span class="code-comment"># ["ChatGPT", "Claude", "Gemini"]</span>

<span class="code-comment"># Remove items</span>
ai_tools.<span class="code-function">remove</span>(<span class="code-string">"Claude"</span>)

<span class="code-comment"># How many items?</span>
<span class="code-function">print</span>(<span class="code-string">"Total certs:"</span>, <span class="code-function">len</span>(certifications))

<span class="code-comment"># Check if item exists</span>
<span class="code-keyword">if</span> <span class="code-string">"Python"</span> <span class="code-keyword">in</span> certifications:
    <span class="code-function">print</span>(<span class="code-string">"Has Python cert!"</span>)
<span class="code-keyword">else</span>:
    <span class="code-function">print</span>(<span class="code-string">"Need Python cert"</span>)
                </div>
                
                <div class="real-world">
                    <div class="real-world-title">💼 Real-World Use:</div>
                    • Shopping carts (list of products)<br>
                    • User contacts/friends list<br>
                    • AI: Training datasets, list of predictions<br>
                    • To-do lists, playlists, any collection<br>
                    • Social media: List of posts, comments, likes
                </div>
                
                <div class="practice">
                    <div class="practice-title">✏️ Practice Exercise:</div>
                    Create a list of your AI goals for this year. Add 3 goals, print them, add 2 more, then print the total count!
                </div>
            </div>
        </div>

        <!-- LESSON 7 -->
        <div class="lesson">
            <div class="lesson-header">
                <div class="lesson-number">LESSON 7</div>
                <div class="lesson-title">For Loops - Repeat Actions</div>
            </div>
            
            <div class="lesson-content">
                <div class="what-it-does">
                    <div class="what-it-does-title">🎯 What It Does:</div>
                    Repeat code multiple times. Instead of writing the same line 100 times, loop it!
                </div>
                
                <div class="code-block">
<span class="code-comment"># Loop through a list</span>
ai_tools = [<span class="code-string">"ChatGPT"</span>, <span class="code-string">"Claude"</span>, <span class="code-string">"Gemini"</span>]

<span class="code-keyword">for</span> tool <span class="code-keyword">in</span> ai_tools:
    <span class="code-function">print</span>(<span class="code-string">"I use"</span>, tool)

<span class="code-comment"># Loop with numbers (range)</span>
<span class="code-keyword">for</span> i <span class="code-keyword">in</span> <span class="code-function">range</span>(<span class="code-number">5</span>):
    <span class="code-function">print</span>(<span class="code-string">"Studying hour"</span>, i + <span class="code-number">1</span>)

<span class="code-comment"># Calculate total</span>
grades = [<span class="code-number">100</span>, <span class="code-number">100</span>, <span class="code-number">92</span>, <span class="code-number">100</span>, <span class="code-number">100</span>]
total = <span class="code-number">0</span>

<span class="code-keyword">for</span> grade <span class="code-keyword">in</span> grades:
    total = total + grade

average = total / <span class="code-function">len</span>(grades)
<span class="code-function">print</span>(<span class="code-string">"Average grade:"</span>, average)

<span class="code-comment"># Loop with conditions</span>
certifications = [<span class="code-string">"Python"</span>, <span class="code-string">"AI Basics"</span>, <span class="code-string">"ML"</span>]

<span class="code-keyword">for</span> cert <span class="code-keyword">in</span> certifications:
    <span class="code-keyword">if</span> <span class="code-string">"Python"</span> <span class="code-keyword">in</span> cert:
        <span class="code-function">print</span>(cert, <span class="code-string">"- Priority!"</span>)
    <span class="code-keyword">else</span>:
        <span class="code-function">print</span>(cert)
                </div>
                
                <div class="real-world">
                    <div class="real-world-title">💼 Real-World Use:</div>
                    • Processing all items in a database<br>
                    • Sending emails to all users<br>
                    • AI: Training model for multiple epochs<br>
                    • Calculating totals (sales, scores, hours)<br>
                    • Checking all files in a folder
                </div>
                
                <div class="practice">
                    <div class="practice-title">✏️ Practice Exercise:</div>
                    Create a list of 5 study hours (e.g., [3, 4, 5, 2, 6]). Use a loop to calculate total hours and print each day's hours with "Day 1: 3 hours"!
                </div>
            </div>
        </div>

        <!-- LESSON 8 -->
        <div class="lesson">
            <div class="lesson-header">
                <div class="lesson-number">LESSON 8</div>
                <div class="lesson-title">While Loops - Repeat Until Condition</div>
            </div>
            
            <div class="lesson-content">
                <div class="what-it-does">
                    <div class="what-it-does-title">🎯 What It Does:</div>
                    Keep repeating code UNTIL a condition becomes False. Like "keep asking until correct answer"!
                </div>
                
                <div class="code-block">
<span class="code-comment"># Basic while loop</span>
count = <span class="code-number">1</span>
<span class="code-keyword">while</span> count <= <span class="code-number">5</span>:
    <span class="code-function">print</span>(<span class="code-string">"Study session"</span>, count)
    count = count + <span class="code-number">1</span>

<span class="code-comment"># Keep asking until correct</span>
password = <span class="code-string">""</span>
<span class="code-keyword">while</span> password != <span class="code-string">"python123"</span>:
    password = <span class="code-function">input</span>(<span class="code-string">"Enter password: "</span>)
<span class="code-function">print</span>(<span class="code-string">"Access granted!"</span>)

<span class="code-comment"># Menu system</span>
choice = <span class="code-string">""</span>
<span class="code-keyword">while</span> choice != <span class="code-string">"quit"</span>:
    <span class="code-function">print</span>(<span class="code-string">"\n1. Study Python"</span>)
    <span class="code-function">print</span>(<span class="code-string">"2. Build Project"</span>)
    <span class="code-function">print</span>(<span class="code-string">"Type 'quit' to exit"</span>)
    choice = <span class="code-function">input</span>(<span class="code-string">"Choose: "</span>)
    
    <span class="code-keyword">if</span> choice == <span class="code-string">"1"</span>:
        <span class="code-function">print</span>(<span class="code-string">"Great! Let's study!"</span>)
    <span class="code-keyword">elif</span> choice == <span class="code-string">"2"</span>:
        <span class="code-function">print</span>(<span class="code-string">"Time to build!"</span>)

<span class="code-comment"># Progress tracker</span>
hours_studied = <span class="code-number">0</span>
goal = <span class="code-number">100</span>

<span class="code-keyword">while</span> hours_studied < goal:
    new_hours = <span class="code-function">int</span>(<span class="code-function">input</span>(<span class="code-string">"Hours studied today: "</span>))
    hours_studied += new_hours
    remaining = goal - hours_studied
    <span class="code-function">print</span>(<span class="code-string">f"Progress: {hours_studied}/{goal}. Remaining: {remaining}"</span>)

<span class="code-function">print</span>(<span class="code-string">"Goal achieved!"</span>)
                </div>
                
                <div class="real-world">
                    <div class="real-world-title">💼 Real-World Use:</div>
                    • Login systems (try until success or limit reached)<br>
                    • Games (play until game over)<br>
                    • AI: Training until accuracy reaches target<br>
                    • Chat systems (keep chatting until user exits)<br>
                    • Data processing (until end of file)
                </div>
                
                <div class="tip-box">
                    <div class="tip-title">⚠️ Warning:</div>
                    Make sure your while loop can END! If condition never becomes False, it runs forever (infinite loop)!
                </div>
            </div>
        </div>

        <!-- LESSON 9 -->
        <div class="lesson">
            <div class="lesson-header">
                <div class="lesson-number">LESSON 9</div>
                <div class="lesson-title">Functions - Reusable Code Blocks</div>
            </div>
            
            <div class="lesson-content">
                <div class="what-it-does">
                    <div class="what-it-does-title">🎯 What It Does:</div>
                    Create your own commands! Write code once, use it many times. Like creating your own print() or input()!
                </div>
                
                <div class="code-block">
<span class="code-comment"># Define a function</span>
<span class="code-keyword">def</span> <span class="code-function">greet</span>():
    <span class="code-function">print</span>(<span class="code-string">"Hello, AI learner!"</span>)

<span class="code-comment"># Call (use) the function</span>
<span class="code-function">greet</span>()
<span class="code-function">greet</span>()  <span class="code-comment"># Can use multiple times!</span>

<span class="code-comment"># Function with parameters (inputs)</span>
<span class="code-keyword">def</span> <span class="code-function">greet_person</span>(name):
    <span class="code-function">print</span>(<span class="code-string">f"Hello, {name}!"</span>)

<span class="code-function">greet_person</span>(<span class="code-string">"Khaled"</span>)
<span class="code-function">greet_person</span>(<span class="code-string">"Ahmed"</span>)

<span class="code-comment"># Function that returns a value</span>
<span class="code-keyword">def</span> <span class="code-function">calculate_average</span>(grades):
    total = <span class="code-function">sum</span>(grades)
    avg = total / <span class="code-function">len</span>(grades)
    <span class="code-keyword">return</span> avg

<span class="code-comment"># Use the return value</span>
my_grades = [<span class="code-number">100</span>, <span class="code-number">92</span>, <span class="code-number">100</span>]
result = <span class="code-function">calculate_average</span>(my_grades)
<span class="code-function">print</span>(<span class="code-string">"Average:"</span>, result)

<span class="code-comment"># Practical example</span>
<span class="code-keyword">def</span> <span class="code-function">study_tracker</span>(hours, goal):
    percentage = (hours / goal) * <span class="code-number">100</span>
    <span class="code-keyword">if</span> percentage >= <span class="code-number">100</span>:
        <span class="code-keyword">return</span> <span class="code-string">"Goal achieved!"</span>
    <span class="code-keyword">else</span>:
        <span class="code-keyword">return</span> <span class="code-string">f"{percentage:.1f}% complete"</span>

status = <span class="code-function">study_tracker</span>(<span class="code-number">75</span>, <span class="code-number">100</span>)
<span class="code-function">print</span>(status)
                </div>
                
                <div class="real-world">
                    <div class="real-world-title">💼 Real-World Use:</div>
                    • Breaking complex code into manageable pieces<br>
                    • Reusing code (write once, use everywhere)<br>
                    • AI: Functions for data preprocessing, model training<br>
                    • Building APIs (each function = one feature)<br>
                    • Creating libraries and tools
                </div>
                
                <div class="practice">
                    <div class="practice-title">✏️ Practice Exercise:</div>
                    Create a function called "ai_readiness_score" that takes hours_studied and certifications as parameters. Return "Ready" if hours > 100 AND certs > 5, else "Keep learning!"
                </div>
            </div>
        </div>

        <!-- LESSON 10 -->
        <div class="lesson">
            <div class="lesson-header">
                <div class="lesson-number">LESSON 10</div>
                <div class="lesson-title">Dictionaries - Key-Value Storage</div>
            </div>
            
            <div class="lesson-content">
                <div class="what-it-does">
                    <div class="what-it-does-title">🎯 What It Does:</div>
                    Store data with labels (keys). Like a real dictionary: word → definition. Or person → email, age, city!
                </div>
                
                <div class="code-block">
<span class="code-comment"># Create a dictionary</span>
student = {
    <span class="code-string">"name"</span>: <span class="code-string">"Khaled"</span>,
    <span class="code-string">"age"</span>: <span class="code-number">21</span>,
    <span class="code-string">"city"</span>: <span class="code-string">"Kajang"</span>,
    <span class="code-string">"certifications"</span>: <span class="code-number">7</span>
}

<span class="code-comment"># Access values by key</span>
<span class="code-function">print</span>(student[<span class="code-string">"name"</span>])           <span class="code-comment"># Khaled</span>
<span class="code-function">print</span>(student[<span class="code-string">"certifications"</span>])  <span class="code-comment"># 7</span>

<span class="code-comment"># Add or update values</span>
student[<span class="code-string">"email"</span>] = <span class="code-string">"khaled.ameen599@gmail.com"</span>
student[<span class="code-string">"certifications"</span>] = <span class="code-number">8</span>  <span class="code-comment"># Update existing</span>

<span class="code-comment"># Check if key exists</span>
<span class="code-keyword">if</span> <span class="code-string">"email"</span> <span class="code-keyword">in</span> student:
    <span class="code-function">print</span>(<span class="code-string">"Email:"</span>, student[<span class="code-string">"email"</span>])

<span class="code-comment"># Loop through dictionary</span>
<span class="code-keyword">for</span> key, value <span class="code-keyword">in</span> student.<span class="code-function">items</span>():
    <span class="code-function">print</span>(<span class="code-string">f"{key}: {value}"</span>)

<span class="code-comment"># List of dictionaries (common pattern!)</span>
ai_tools = [
    {<span class="code-string">"name"</span>: <span class="code-string">"ChatGPT"</span>, <span class="code-string">"type"</span>: <span class="code-string">"chatbot"</span>, <span class="code-string">"free"</span>: <span class="code-keyword">True</span>},
    {<span class="code-string">"name"</span>: <span class="code-string">"Claude"</span>, <span class="code-string">"type"</span>: <span class="code-string">"chatbot"</span>, <span class="code-string">"free"</span>: <span class="code-keyword">True</span>},
    {<span class="code-string">"name"</span>: <span class="code-string">"Midjourney"</span>, <span class="code-string">"type"</span>: <span class="code-string">"image"</span>, <span class="code-string">"free"</span>: <span class="code-keyword">False</span>}
]

<span class="code-keyword">for</span> tool <span class="code-keyword">in</span> ai_tools:
    <span class="code-keyword">if</span> tool[<span class="code-string">"free"</span>]:
        <span class="code-function">print</span>(<span class="code-string">f"{tool['name']} is free!"</span>)
                </div>
                
                <div class="real-world">
                    <div class="real-world-title">💼 Real-World Use:</div>
                    • User profiles (username, email, password, settings)<br>
                    • API responses (JSON data = dictionaries!)<br>
                    • AI: Model configurations, hyperparameters<br>
                    • Database records (each row = dictionary)<br>
                    • Settings and configurations
                </div>
                
                <div class="practice">
                    <div class="practice-title">✏️ Practice Exercise:</div>
                    Create your AI journey dictionary with: name, start_date, hours_studied, certifications, favorite_tool, goal. Print each item and calculate if you've reached 100 hours!
                </div>
                
                <div class="tip-box">
                    <div class="tip-title">🔥 Power Tip:</div>
                    Dictionaries are EVERYWHERE in real programming! APIs, databases, configurations - they all use this key-value pattern. Master this and you're halfway to being a real programmer!
                </div>
            </div>
        </div>

        <!-- FINAL SECTION -->
        <div style="background: linear-gradient(135deg, #11998e 0%, #38ef7d 100%); color: white; padding: 30px; border-radius: 12px; margin-top: 40px; text-align: center;">
            <h2 style="font-size: 2em; margin-bottom: 15px;">🎉 Congratulations!</h2>
            <p style="font-size: 1.2em; margin-bottom: 10px;">You now know the 10 core concepts of Python!</p>
            <p style="font-size: 1em;">These are the building blocks for EVERYTHING else - AI, web development, automation, data science!</p>
            <p style="font-size: 1em; margin-top: 15px; font-weight: 600;">Next Step: Practice DAILY and build small projects with these concepts!</p>
        </div>
    </div>
</body>
</html>
