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
        self.dna = ''.join(random.choices(['A', 'C', 'T', 'G'], k=1024))

```
<div style="display: inline_block"><br>
  <img src="https://github.com/alexandresaints/alexandresaints/blob/main/Profile--GitHubAuxiliaryFiles/javascript-plain.svg" width="50" height="40" align="center"/>
  <img src="https://github.com/alexandresaints/alexandresaints/blob/main/Profile--GitHubAuxiliaryFiles/react-original.svg" width="50" height="40" align="center"/>
  <img src="https://github.com/alexandresaints/alexandresaints/blob/main/Profile--GitHubAuxiliaryFiles/nodejs-original.svg" width="50" height="40" align="center"/>
  <img src="https://github.com/alexandresaints/alexandresaints/blob/main/Profile--GitHubAuxiliaryFiles/git-plain.svg" width="50" height="40" align="center"/>
  <img src="https://github.com/alexandresaints/alexandresaints/blob/main/Profile--GitHubAuxiliaryFiles/mysql-plain.svg" width="50" height="40" align="center"/>
  <img src="https://github.com/alexandresaints/alexandresaints/blob/main/Profile--GitHubAuxiliaryFiles/mongodb-original.svg" width="50" height="40" align="center"/>
</div>
