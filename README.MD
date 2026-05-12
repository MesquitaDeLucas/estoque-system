# Sistema de Controle de Estoque

Sistema web de controle de estoque desenvolvido com Python, Flask e SQLite.

O projeto permite realizar controle de entrada e saída de produtos, gerenciamento automático de estoque, geração de relatórios e exportação de dados para Excel.

---

# Funcionalidades

- Login de usuário
- Cadastro de produtos
- Entrada de produtos
- Saída de produtos
- Atualização automática de estoque
- Dashboard administrativo
- Relatório de movimentações
- Registro de datas
- Exportação para Excel
- Interface responsiva

---

# Tecnologias Utilizadas

- Python
- Flask
- SQLite
- HTML5
- CSS3
- OpenPyXL

---

# Dashboard do Sistema

O sistema possui um dashboard com:

- Total de produtos cadastrados
- Quantidade total em estoque
- Total de entradas
- Total de saídas

---

# Relatórios

O sistema gera relatórios contendo:

- Data da movimentação
- Produto movimentado
- Tipo da movimentação
- Quantidade
- Estoque atual

Também é possível exportar os relatórios em formato `.xlsx`.

---

# Estrutura do Projeto

```bash
ESTOQUE-SYSTEM/
│
├── static/
│   └── style.css
│
├── templates/
│
├── app.py
├── requirements.txt
├── database.db
└── README.md
```

---

# Como Executar

## 1. Clonar o repositório

```bash
git clone LINK_DO_REPOSITORIO
```

---

## 2. Entrar na pasta

```bash
cd ESTOQUE-SYSTEM
```

---

## 3. Criar ambiente virtual

```bash
python -m venv venv
```

---

## 4. Ativar ambiente virtual

### Windows

```bash
venv\Scripts\activate
```

---

## 5. Instalar dependências

```bash
pip install -r requirements.txt
```

---

## 6. Executar projeto

```bash
python app.py
```

---

# Login do Sistema

```txt
Usuário: admin
Senha: 123
```

---

# Melhorias Futuras

- Cadastro de múltiplos usuários
- Upload de imagem dos produtos
- Gráficos no dashboard
- API REST
- Deploy online
- Docker
- Controle de permissões
- Recuperação de senha

---

# Autor

Lucas de Mesquita Soares

Desenvolvido para estudos e prática de desenvolvimento backend com Python.