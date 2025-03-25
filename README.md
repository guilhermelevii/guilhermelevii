<h1 align="center">👋 Olá, eu sou o Guilherme! 🐍  </h1>

```python
class DevPython:
    def __init__(self):
        self.name = "Guilherme"
        self.role = "Desenvolvedor Python"
        self.skills = ["Automação Bancária", "APIs", "Web Scraping", "Bots", "Integração com WhatsApp"]

    def apresentar(self):
        return f"Olá, eu sou {self.name}, um {self.role} apaixonado por automação e soluções eficientes."

eu = DevPython()
print(eu.apresentar())
