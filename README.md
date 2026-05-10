# 🔐 Simulando Ataque de Brute Force com Medusa e Kali Linux

## 📌 Descrição do Projeto

Este projeto foi desenvolvido como parte do desafio da DIO com o objetivo de simular ataques de força bruta utilizando Kali Linux e a ferramenta Medusa em ambientes controlados e educacionais.

A atividade permitiu compreender técnicas de autenticação, testes de acesso e conceitos relacionados à segurança ofensiva e análise de vulnerabilidades.

---

# 🎯 Objetivos de Aprendizagem

- Compreender ataques de brute force
- Utilizar Kali Linux em laboratório
- Executar testes com Medusa
- Trabalhar com wordlists
- Entender riscos e medidas de mitigação

---

# 🛠️ Ferramentas Utilizadas

- Kali Linux
- Medusa
- Metasploitable 2
- DVWA
- VirtualBox

---

# 📂 Estrutura do Projeto

```text
📦 ataque-brute-force-kali-linux
 ┣ 📜 README.md
 ┣ 📂 imagem
 ┣ 📂 comandos
 ┗ 📂 evidências
```
---

# ⚙️ Etapas Realizadas

## 1️⃣ Configuração do Ambiente

Foi configurado um laboratório virtual utilizando Kali Linux e Metasploitable 2 no VirtualBox.

📸 <img width="1919" height="1079" alt="configuracao_do_ambiente " src="https://github.com/user-attachments/assets/e8ff791e-7c9f-4a83-94f1-dc7e497973d9" />



## 2️⃣ Testes de Conectividade

Foram realizados testes para validar comunicação entre as máquinas.

### Comandos utilizados

```bash
ping
ifconfig
```

📸 <img width="1727" height="794" alt="teste_de_conectividade" src="https://github.com/user-attachments/assets/4eb19c8d-830d-4734-9b44-31aa393a2079" />


---

## 3️⃣ Utilização do Medusa

Foi utilizada a ferramenta Medusa para simular tentativas de autenticação.

### Exemplo de comando

```bash
medusa -h IP -u usuario -P wordlist.txt -M serviço
```

📸 <img width="1383" height="748" alt="Executando_testes_e_validando_acesso_smbclient" src="https://github.com/user-attachments/assets/7b9c3d1a-ea3c-414a-ad81-3a2be4d9ee6c" />


---

## 4️⃣ Criação de Wordlists

Foram utilizadas listas de usuários e senhas para os testes.

📸 <img width="1917" height="813" alt="Criando_listas_usuario_senhas_e_teste_ftp" src="https://github.com/user-attachments/assets/a50ec566-93f5-4fea-8cd4-b769b4bcb5e0" />


---

## 5️⃣ Resultados Obtidos

Os testes demonstraram como ataques de força bruta podem explorar senhas fracas e serviços vulneráveis.

---

# 🧠 Aprendizados

- Importância de senhas fortes
- Funcionamento de autenticação
- Uso de ferramentas ofensivas em ambientes controlados
- Necessidade de monitoramento e mitigação

---

# 🚨 Observação

Este projeto possui finalidade exclusivamente educacional e foi executado em ambiente controlado para fins de estudo em cibersegurança.

---

# 👨‍💻 Autor

Projeto desenvolvido para a plataforma DIO.# Ataque-brute-force-kali-linux
Projeto DIO simulando ataque de força bruta com Kali Linux e Medusa
