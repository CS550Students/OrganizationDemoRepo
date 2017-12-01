### Zhi Class


```python

class Zhi:
    #constructor
    def __init__(self, name):
        self.name = name
        self.hunger = 50
        self.thirst = 50
        self.energy = 50

    def stats(self):
        print("Zhi stats:")
        print("Name: " + str(self.name))
        print("Hunger: " + str(self.hunger))
        print("Thirst: " + str(self.thirst))
        print("Energy: " + str(self.energy), end = "\n\n")

    def read(self):
        if self.energy <= 0:
            print("Can't read. Too tired.")
        elif self.energy < 20:
            print("Look out! Zhi is tired.")
            self.energy -= 5
            self.hunger += 5
            self.thirst += 10
        else:
            self.energy -= 5
            self.hunger += 5
            self.thirst += 10

```
