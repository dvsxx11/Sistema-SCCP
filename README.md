## 📌 Descrição
O **Sistema-SCCP** é uma aplicação web desenvolvido com **Lovable** e **Supabase** para gerenciar **torcedores e jogos do Corinthians**.  
O sistema permite o **cadastro, listagem, edição e exclusão ** de jogos e torcedores, além do **gerenciamento de inscrições** e da **contagem de torcedores por jogo**.

---

## 🚀 Tecnologias Utilizadas
- **Frontend:** Lovable (React + TailwindCSS)
- **Backend e Banco de Dados:** Supabase (PostgreSQL)
- **Integração:** API direta entre Lovable e Supabase
- **Deploy:** (https://alvinegro-tickets-51308.lovable.app)

---

## ⚙️ Funcionalidades Principais
- ⚽ **Cadastro de jogos do Corinthians** (data, adversário e local)
- 👥 **Cadastro de torcedores** (nome, e-mail e setor do estádio)
- 🧾 **Gerenciamento de inscrições** (torcedores confirmados em cada jogo)
- 📊 **Listagem de jogos com total de torcedores**

---

## 📹 Vídeo de Apresentação
🎥 https://drive.google.com/file/d/10DZQfKsP72kJp6P2ZZU6WwtEz_bdFmiE/view?usp=sharing

---

## 🖼️ Prints das Telas
| Tela | Descrição |
|------|------------|
| ![Dashboard](https://github.com/user-attachments/assets/8b464a93-ff91-480f-a8fe-3697779c3c6c) | **Dashboard**: Página inicial com resumo de informações | 
| ![Jogos](https://github.com/user-attachments/assets/97cfc9af-70e1-462f-a067-72fb6a989acf) | **Jogos**: Cadastro de Jogos |
| ![Torcedores](https://github.com/user-attachments/assets/e49052a9-bbcf-4b9b-b78d-3d1b3b5e64a1) | **Torcedores**: Cadastro de torcedores |
| ![Inscrições](https://github.com/user-attachments/assets/a936838d-2817-4ef9-8ce4-a85bc5dddd2e) | **Inscrições**: Gerenciamento de inscrições |

---


## 🗄️ Modelo Lógico do Banco de Dados
<img width="753" height="291" alt="image" src="https://github.com/user-attachments/assets/4f64f20a-e8fd-4aaf-bcd6-9a7570315a8e" />

### Tabelas
| Tabelas | Colunas |
|------|------------|
| ![jogos](<img width="1160" height="401" alt="jogos" src="https://github.com/user-attachments/assets/9aca011f-dd08-4372-bd3b-fc78c71b2faa" /> ) | **jogos**: id_jogo, adversario. data_jogo, local | 
| ![torcedores](<img width="1150" height="420" alt="torcedores" src="https://github.com/user-attachments/assets/a39af467-9b24-4cb3-b477-cd06c856cf5e" /> ) | **torcedores**: id_torcedor, nome, email, setor, jogo_id |











