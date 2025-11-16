# 🐾 PetCare Tips – Dicas de Cuidados

Aplicação web desenvolvida como parte do **Projeto 1 da disciplina Programação Web Fullstack (ES47B-ES71)**.  
O objetivo é fornecer dicas básicas de cuidados, expectativa de vida e informações sobre raças de cães e gatos, além de permitir que usuários cadastrados registrem seus próprios pets.  
A aplicação foi construída como uma **SPA (Single Page Application)** em React.js, com backend em Node.js.

---

## 🚀 Funcionalidades

### 🔍 Consulta de Raças  
- Seleção da espécie (**cachorro** ou **gato**)
- Busca por raças utilizando **APIs públicas** (The Dog API / The Cat API)
- Exibição de informações como:
  - Expectativa de vida  
  - Temperamento  
  - Cuidados gerais  
- Interface com **cards responsivos** (React-Bootstrap)
- Validação de **campos obrigatórios** (não é possível buscar sem selecionar espécie e raça)
- Uso de **useMemo** para cachear descrições e evitar recomputações desnecessárias

### 👤 Autenticação e Cadastro  
Na segunda parte do projeto foram implementadas:
- **Tela de login**
- **Tela de cadastro de usuários**
- Somente usuários autenticados podem acessar funcionalidades extras

### 🐶 Registro de Pets  
Após fazer login, o usuário pode:
- Cadastrar seu próprio pet
- Informar **nome**, **idade**, **descrição** e **espécie**
- Visualizar seus pets cadastrados em uma área dedicada
- Dados armazenados no backend

---

## 🛠️ Tecnologias Utilizadas

### **Frontend**
- React.js  
- Vite  
- React-Bootstrap  
- Hooks como useMemo  

### **Backend**
- Node.js  
- Express  
- Firebase (ou outra base utilizada no projeto)

### **APIs Externas**
- The Dog API  
- The Cat API  

---

## 📸 Imagens da Aplicação

<img width="1116" height="635" alt="image" src="https://github.com/user-attachments/assets/c50dca52-3775-4dac-aa3b-d97e0485d018" />
<img width="1145" height="636" alt="image" src="https://github.com/user-attachments/assets/b3430396-4eb2-4897-9058-03c4cde99389" />
<img width="1121" height="640" alt="image" src="https://github.com/user-attachments/assets/39241744-b0fc-4fb6-bdf2-de0f0d927464" />
<img width="1142" height="648" alt="image" src="https://github.com/user-attachments/assets/2cccf59f-e074-4b32-9669-dfda54affa7d" />

---

## 💡 Por que PetCare Tips?

Os desenvolvedores do projeto são **Bruna Naian** e **Vinicius Neia**.

Bruna é apaixonada por raças caninas e felinas e por suas funções. Estuda cinofilia por hobby há mais de 10 anos e já cursou Medicina Veterinária. Movida pelo desejo de unir conhecimento e inovação, busca revolucionar o mercado pet por meio da tecnologia.

Ao seu lado está Vinicius, grande amigo e incentivador, que acompanha de perto seus estudos cinófilos e compartilha desse propósito.

Juntos, criaram o PetCare Tips com a missão de tornar informações sobre cinofilia acessíveis, claras e úteis para qualquer pessoa interessada.

---

## ▶️ Como executar o projeto

### **Frontend**
```bash
npm run dev
