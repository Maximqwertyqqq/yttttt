# yttttt


#описание класса Rectangle
class Rectangle:
    def __init__(self, length, height):
        self.length = length
        self.height = height
    
    def print_info(self):
        print('Дан прямоугольник с длиной' , self.length , 'и шириной' , self.height)
    
    def perim(self):
        self.perimetr = (self.length + self.height) * 2
        return self.perimetr

    def plosh(self):
        self.plosh = self.length * self.height
        return self.plosh

a = int(input("Введите длину:"))
b = int(input("Введите ширину:"))


rect = Rectangle(a, b)
rect.print_info()
print("Его периметр:" , rect.perim())
print("Его площадь:" , rect.plosh())





#ввод длины и ширины и создание экземпляра класса

#печать информации о прямоугольнике

#подсчёт и печать периметра

#подсчёт и печать площади
