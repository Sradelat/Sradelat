<pre>learning_python = True
python_certificate = True
data_analysis_certificate = True
machine_learning_certificate = False
intro = "Hello World! I'm here to "

while learning_python:
    goals = ["create projects", "stay healthy", "have fun"]
    if python_certificate and data_analysis_certificate is True:
        goals.append("study machine learning")
    for goal in goals:
        if goal is goals[-1]:
            intro += f"and {goal}!"
        else:
            intro += f"{goal}, "
    break
    
print(intro)

> Hello World! I'm here to create projects, stay healthy, have fun, and study machine learning!

error C2065: 'learning_python': undeclared identifier</pre>
