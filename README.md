```html
class Me():
    def __init__(self):
        self.name = '<span style="color:#ff79c6">Nguyễn Hồng Anh aka Pink</span>'
        self.dob = '<span style="color:#f1fa8c">10-11-2005</span>'
        self.hobbies = ['<span style="color:#50fa7b">reading</span>', '<span style="color:#8be9fd">coding</span>', '<span style="color:#ffb86c">gym</span>', '<span style="color:#bd93f9">social activities</span>', '<span style="color:#ff5555">investing (long-term)</span>']
        self.location = '<span style="color:#6272a4">Melbourne, Australia</span>'
        self.languages = ['<span style="color:#8be9fd">Vietnamese</span>', '<span style="color:#50fa7b">English</span>']
        self.study = '<span style="color:#bd93f9">Swinburne University of Technology / Bachelor of Data Science</span>'
        self.interests = ['<span style="color:#ff79c6">Data Science</span>', '<span style="color:#ffb86c">Artificial Intelligence</span>', '<span style="color:#f1fa8c">Finance/Economy</span>']

    def __str__(self):
        return f"Hi, I'm {self.name}. I was born on {self.dob}. I'm currently studying at {self.study}. My hobbies are {', '.join(self.hobbies)}. I can speak {', '.join(self.languages)}. My interests are {', '.join(self.interests)}."

    def cook(self, food):
        return f"I can cook {food}."

    def play_game(self, game):
        return f"I can play {game}. But now I'm focusing on my study."

class Training():
    def __init__(self):
        self.method = ["<span style='color:#50fa7b'>Self Study</span>", "<span style='color:#8be9fd'>University</span>", "<span style='color:#ffb86c'>Personal Projects</span>", "<span style='color:#bd93f9'>Books</span>"]
        self.knowledges = ["<span style='color:#ff79c6'>Data Science</span>", "<span style='color:#ffb86c'>Machine Learning</span>", "<span style='color:#50fa7b'>Deep Learning</span>", "<span style='color:#8be9fd'>Statistics</span>", "<span style='color:#bd93f9'>Mathematics</span>", "<span style='color:#ff5555'>Programming</span>", "<span style='color:#f1fa8c'>Economics</span>", "<span style='color:#6272a4'>Finance</span>", "<span style='color:#ff79c6'>Business</span>", "<span style='color:#ffb86c'>History</span>"]

    def study(self, new_knowledge):
        while True:
            self.knowledges.append(new_knowledge)
