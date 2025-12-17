# 🤖 Bot Discord em Python (discord.py)

Bot para Discord desenvolvido em **Python** usando a biblioteca **discord.py**, com estrutura organizada em **Cogs** para facilitar manutenção e escalabilidade.

---

## 📁 Estrutura do Projeto
```
bot/
│
├── main.py # Arquivo principal do bot
├── config.py # Configurações (token, prefixo, etc)
│
├── cogs/ # Comandos e eventos separados por módulos
│ ├── init.py
│ ├── geral.py
│ ├── moderacao.py
│ └── eventos.py
│
└── utils/ # Funções auxiliares
├── init.py
└── embeds.py
```

---

## ⚙️ Requisitos

- Python **3.10+**
- discord.py **2.x**
