
# 🧰 Guia Completo do Git Bash e pip (Para Iniciantes e Intermediários)

---

## 📌 O que é o Git Bash?

O **Git Bash** é um terminal que permite usar comandos Git e Linux no Windows. Ele simula um shell Unix (bash) e é muito usado por desenvolvedores Python, web e de software em geral.

---

## 🛠️ Comandos Básicos do Git Bash

### 📂 Navegação

| Comando | Função |
|--------|--------|
| `pwd` | Mostra o diretório atual |
| `ls` | Lista arquivos/pastas |
| `cd pasta` | Entra numa pasta |
| `cd ..` | Volta uma pasta |
| `cd ~` | Vai para a pasta do usuário |
| `clear` | Limpa o terminal |

---

### 📝 Arquivos e Pastas

| Comando | Função |
|--------|--------|
| `touch nome.txt` | Cria arquivo vazio |
| `mkdir nome` | Cria pasta |
| `rm arquivo.txt` | Remove arquivo |
| `rm -rf pasta/` | Remove pasta e conteúdo (perigoso) |
| `mv origem destino` | Move ou renomeia |
| `cp origem destino` | Copia arquivo ou pasta |

---

### 📘 Outros comandos úteis

| Comando | Função |
|--------|--------|
| `cat arquivo` | Mostra conteúdo |
| `echo "texto"` | Imprime texto |
| `grep "palavra" arquivo.txt` | Busca texto no arquivo |
| `chmod +x script.sh` | Torna script executável |
| `./script.sh` | Executa script bash |

---

### 🌐 Internet (se instalados)

| Comando | Função |
|--------|--------|
| `ping site.com` | Testa conexão |
| `curl` | Faz requisições |
| `wget` | Baixa arquivos |

---

## ⚠️ Diferenças entre Git Bash e Linux

| Recurso | Git Bash | Linux |
|--------|----------|-------|
| `apt`, `yum` | ❌ | ✅ |
| `sudo`, `systemctl` | ❌ | ✅ |
| Bash scripts básicos | ✅ | ✅ |
| Comandos manuais (`man`) | Limitado | Completo |

---

## 🧪 Guia Completo do pip (Python)

O `pip` é o gerenciador de pacotes oficial do Python.

---

### 🔹 Instalar pacote

```bash
pip install flask
```

### 🔹 Instalar múltiplos (requirements.txt)

```bash
pip install -r requirements.txt
```

### 🔹 Atualizar pacote

```bash
pip install -U flask
```

### 🔹 Reinstalar forçado

```bash
pip install --force-reinstall flask
```

### 🔹 Mostrar pacotes instalados

```bash
pip list
```

### 🔹 Mostrar detalhes de um pacote

```bash
pip show numpy
```

### 🔹 Gerar requirements.txt com as versões

```bash
pip freeze > requirements.txt
```

---

### 🔹 Executar pip com segurança (modo módulo)

```bash
python -m pip install flask
```

---

## ✅ Boas práticas com pip e Git Bash

1. Sempre use `venv` para ambientes isolados.
2. Use `pip freeze > requirements.txt` para compartilhar dependências.
3. No Windows, use `Git Bash` com `python -m pip` para evitar conflitos.

---

### Exemplo completo de projeto Python com Git Bash

```bash
mkdir meu_projeto
cd meu_projeto
python -m venv venv
source venv/Scripts/activate
pip install flask
pip freeze > requirements.txt
```

---

## 📘 Fim do guia

Este guia é ideal para quem quer aprender a usar Git Bash + pip do jeito certo, com foco em boas práticas de desenvolvimento.
