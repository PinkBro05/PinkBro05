```python
class Me():
    def __init__(self):
        self.name = 'Nguyễn Hồng Anh aka Pink'
        self.dob = '10-11-2005'
        self.hobbies = ['Reading', 'Coding', 'Gym', 'Social activities', 'Investing']
        self.location = 'Melbourne, Australia'
        self.languages = ['Vietnamese', 'English']
        self.study = 'Swinburne University of Technology / Bachelor of Data Science'
        self.interests = ['Data Science', "Artificial Intelligence", 'Finance/Economy']

class Training():
    def __init__(self):
        self.method = ["Self Study", "University", "Personal Projects", "Books"]
        self.knowledges = ["Data Science", "Machine Learning", "Mathematics", "Programming", "Economics", "Finance", "Business"]

    def study(self, new_knowledge):
        while True:
            self.knowledges.append(new_knowledge)
