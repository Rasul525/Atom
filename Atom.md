# Atom
class Atom:
    def __init__(self, kutle, sira_num):
        self.kutle=kutle
        self.sira_num=sira_num
        self.neytron=kutle - sira_num


class BirAtomlu(Atom):
    def __init__(self, el1, in1):
        self.el1 = el1
        self.in1 = in1
    def Mr(self):
        return self.el1 * self.in1 
    
    
class IkiAtomlu(Atom):
    def __init__(self, el1, in1, el2, in2):
        self.el1 = el1
        self.in1 = in1
        self.el2 = el2
        self.in2 = 
    def Mr(self):
        return self.el1 * self.in1 + self.el2 * self.in2

class UcAtomlu:
    def __init__(self, el1, in1, el2, in2, el3, in3):
        self.el1 = el1
        self.in1 = in1
        self.el2 = el2
        self.in2 = in2
        self.el3 = el3
        self.in3 = in3
    




H = Atom(1, 1)
He = Atom(4, 2)
N = Atom(14,7)
O = Atom(16, 8)


N2 = BirAtomlu(N,2)
