### Olá! Me chamo Natan! 👋

<!--
**na7ank/na7ank** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->

```python
import random
from datetime import datetime


class People:
    def __init__(self, nome, altura, sex, nascimento):
        self.nome   = nome
        self.altura = altura
        self.sex    = sex
        self.nascimento = nascimento
        # Idade
        data_formatada = datetime.strptime(nascimento, "%Y-%m-%d")
        self.idade = datetime.now().year - data_formatada.year
        # DNA
        self.dna = ''.join(random.choices(['A', 'C', 'T', 'G'], k=100))
 
    def apresentar(self):
        txt = f"""Olá, meu nome é {self.nome} e eu tenho {self.idade} anos.\nMinha altura é de {self.altura} m.
        \nE sou {self.sex}
        """
        print(txt)
        
    def __str__(self):
        sex    = "Genero: " + self.sex
        nome   = "Nome: "   + self.nome
        idade  = "Idade: "  + str(self.idade)
        nascimento = "Aniver: " + str(self.nascimento)
        altura = "Altura: " + str(self.altura)
        
        txt = nome+"\n"+idade+"\n"+nascimento+"\n"+altura+"\n"+sex
        
        return txt
    
    def reverse_name(self):
        return self.nome[::-1]
    
    def __add__(self, other):
        if [str(type(other)), str(type(self))] != ["<class '__main__.Pessoa'>", "<class '__main__.Pessoa'>"]:
            return False
        else:
            if self.sex != other.sex:
                nome   = self.nome[:3] + other.nome[3:]
                altura = (self.altura + other.altura)/2
                sex    = random.choice(['M', 'F'])
                aniver = datetime.now().strftime('%Y-%m-%d')
                return People(nome, altura, sex, aniver)

```
