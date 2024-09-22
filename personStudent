class Person:
    def __init__(self,ad,yas):
        self.ad=ad
        self.yas=yas
    def bilgi(self):
        print(f"Ad: {self.ad}, Yaş:{self.yas}")
class Student(Person):
    def __init__(self,ad,yas,okulNumarasi):
        super().__init__(ad,yas)
        self.okulNumarasi=okulNumarasi
    def ogrenciBilgisi(self):
        self.bilgi()
        print(f"Okul numarası:{self.okulNumarasi}")
ogrenci=Student("Ali",15,243)
ogrenci.ogrenciBilgisi()
