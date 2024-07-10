### Olá! Me chamo Natan ! 👋

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
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/python/python-original.svg" width="50" height="40" align="center"/>
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/julia/julia-original.svg" width="50" height="40" align="center"/>      
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/docker/docker-original.svg" width="50" height="40" align="center"/>      
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/postgresql/postgresql-original.svg" width="50" height="40" align="center"/>
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/mysql/mysql-original.svg" width="50" height="40" align="center"/>      
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/mongodb/mongodb-original.svg" width="50" height="40" align="center"/>
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/nodejs/nodejs-original.svg" width="50" height="40" align="center"/>
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/react/react-original.svg" width="50" height="40" align="center"/>      
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/javascript/javascript-original.svg" width="50" height="40" align="center"/>
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/git/git-original.svg" width="50" height="40" align="center"/>
          

</div>
