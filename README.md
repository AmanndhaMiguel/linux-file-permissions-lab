# 🐧 Linux para Segurança

Labs práticos de **Linux aplicados à cibersegurança**, feitos durante o **Google Cybersecurity Professional Certificate**. Cada pasta traz o cenário, os comandos usados, prints do terminal e por que aquilo importa no dia a dia de um analista de SOC.

## 📂 Labs

| # | Lab | O que pratiquei |
|---|---|---|
| 01 | [Gerenciamento de permissões de arquivos](01-permissoes-de-arquivos/) | Auditoria e correção de permissões com `ls -la` e `chmod`, aplicando o princípio do menor privilégio |
| 02 | [Gerenciamento de usuários e grupos](02-gerenciamento-de-usuarios/) | Ciclo de vida de contas com `useradd`, `usermod`, `chown`, `userdel` e `groupdel` |
| 03 | [Ajuda na linha de comando](03-ajuda-na-linha-de-comando/) | Consulta de comandos e opções com `whatis`, `man` e `apropos` |

## 🔐 Conceitos de segurança trabalhados

- **Controle de acesso:** quem tem conta no sistema (usuários e grupos) e o que cada um pode acessar (permissões)
- **Princípio do menor privilégio**
- **Onboarding e offboarding seguros:** criação, alteração e remoção de contas sem deixar acessos órfãos
- **Auditoria:** validar cada alteração (`ls -l`, `id`) e conhecer os eventos que um SOC monitora

## 🛠️ Ferramentas

`Linux` · `Bash` · `sudo` · `chmod` · `chown` · `useradd` · `usermod` · `userdel` · `groupdel` · `man` · `whatis` · `apropos`

---

👩‍💻 **Amanndha De Sena Miguel**, em transição para cibersegurança (foco em SOC)
