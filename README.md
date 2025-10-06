# 🧩 Script de Criação de Usuários, Grupos e Diretórios

## 📄 Descrição
Este script automatiza a criação de **diretórios**, **grupos de usuários**, **usuários** e a **configuração de permissões** no Linux.

## ⚙️ O que o script faz
1. Cria os diretórios:
/publico
/adm
/ven
/sec

2. Cria os grupos:
GRP_ADM
GRP_VEN
GRP_SEC

3. Cria os usuários e os adiciona aos respectivos grupos.  
Senha padrão: `123`

4. Define permissões:
- Diretórios de grupo: acesso total apenas ao grupo (`770`)
- Diretório público: acesso total a todos os usuários (`777`)

## 💻 Como usar
```bash
chmod +x criar_usuarios.sh
sudo ./criar_usuarios.sh
