

class Human:
    def __init__(self, name):
        self.name = name
        self.age = age
        self.say_info()

    def say_info(self):
        print(f'Привет, меня зовут{self, name}, мне{self, age}')
    def birthday(self):
        self.age += 1
        print(f'Уменя день рождения, мне теперь {self.age}')

    def __len__(self):
        return self.age
    
    def __del__(self):
        print(f'{self.name} ушёл')

den = Human(name, 'Денис', 22)
max = Human(name, 'Макс', 22)
max.birthday()
print(len(den))

# bug-free-goggles
