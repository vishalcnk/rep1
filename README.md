class Operation():
    def set_values(self,a,b):
        self.a = a
        self.b = b
    def add(self):
        print(self.a + self.b)
    def sub(self):
        print(self.a-self.b)
    def multi(self):
        print(self.a*self.b)
    def divd(self):
        print(self.a / self.b)
        # print(self.a%self.b)
op = Operation()
op.set_values(25, 75)
op.add()
