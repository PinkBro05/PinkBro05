<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Code Display</title>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/highlight.js/11.5.1/styles/default.min.css">
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f0f0f0;
            padding: 20px;
        }
        pre {
            background-color: #2d2d2d;
            color: #f8f8f2;
            padding: 20px;
            border-radius: 5px;
            overflow: auto;
        }
    </style>
</head>
<body>
    <pre><code class="python">
        class Me():
            def __init__(self):
                self.name = 'Nguyễn Hồng Anh aka Pink'
                self.dob = '10-11-2005'
                self.hobbies = ['reading', 'coding', 'gym', 'social activities', 'investing (long-term)']
                self.location = 'Melbourne, Australia'
                self.languages = ['Vietnamese', 'English']
                self.study = 'Swinburne University of Technology / Bachelor of Data Science'
                self.interests = ['Data Science', "Artifical Intelligent",'Finance/Economy']
                
            def __str__(self):
                return f"Hi, I'm {self.name}. I was born on {self.dob}. I'm currently studying at {self.study}. My hobbies are {', '.join(self.hobbies)}. I can speak {', '.join(self.languages)}. My interests are {', '.join(self.interests)}."
            
            def cook(self, food):
                return f"I can cook {food}."
            
            def play_game(self, game):
                return f"I can play {game}. But now I'm focusing on my study."
            
        class Training():
            def __init__(self):
                self.method = ["Self Study", "University", "Personal Projects", "Books"]
                self.knowledges = ["Data Science", "Machine Learning", "Deep Learning", "Statistics", "Mathematics", "Programming", "Economics", "Finance", "Business", "History"]
            
            def study(self, new_knowledge):
                while (True):
                    self.knowledges.append(new_knowledge)
    </code></pre>
    <script src="https://cdnjs.cloudflare.com/ajax/libs/highlight.js/11.5.1/highlight.min.js"></script>
    <script>hljs.highlightAll();</script>
</body>
</html>
