<pre>learning_python = True
python_certificate = True
machine_learning_certificate = False
intro = "Hello World! I'm here to "

while learning_python:
    goals = ["create projects", "stay healthy", "have fun"]
    if python_certificate is True:
        goals.append("study machine learning")
    else:
        continue
    for goal in goals:
        if goal is goals[-1]:
            intro += f"and {goal}!"
        else:
            intro += f"{goal}, "
    break
print(intro)

> Hello World! I'm here to create projects, stay healthy, have fun, and study machine learning!<pre>
