# 🌍 Disaster Resource Management Platform (Abigo)

## 📌 Sobre o Projeto

Este projeto foi desenvolvido durante um hackathon realizado entre os dias **02/08 e 04/08**, com o desafio:

> **"Tecnologia Contra Crises Climáticas: Soluções para Cidades Resilientes"**

A solução proposta pela equipe foi a criação de uma **plataforma centralizada de gerenciamento de recursos em situações de catástrofes**, permitindo que comunidades organizem e acessem informações críticas de forma rápida e eficiente.

A aplicação conecta **pessoas que precisam de ajuda** com **voluntários e organizações que podem oferecer suporte**, reduzindo a desorganização e a falta de informação em momentos críticos.

---

## 🚨 Problema

Durante desastres naturais, há grande mobilização comunitária para oferecer:

* Abrigo
* Alimentação
* Assistência médica
* Doações

No entanto, a **falta de informação centralizada e acessível** dificulta o acesso a esses recursos.

Perguntas comuns incluem:

* Onde encontrar abrigo?
* Onde conseguir alimentos?
* Como ajudar outras pessoas?

---

## 🎯 Objetivo

Criar uma plataforma que:

* Centralize informações sobre recursos disponíveis
* Facilite o acesso para pessoas afetadas
* Incentive o voluntariado e a colaboração comunitária

---

## 💡 Solução

A plataforma permite que usuários autenticados registrem:

* 🏠 Abrigos
* 🍽️ Pontos de alimentação
* 🏥 Assistência médica
* 🎁 Pontos de doação

Enquanto isso:

> 🔓 **Usuários não autenticados podem visualizar todas as informações**, garantindo acesso rápido para quem precisa.

---

## 🧠 Arquitetura (Backend)

O backend foi desenvolvido utilizando:

* **.NET**
* **Arquitetura baseada em DDD (Domain-Driven Design)**
* **PostgreSQL**
* **Autenticação via JWT**

### Estrutura baseada em camadas:

* **Domain** → Regras de negócio
* **Application** → Casos de uso
* **Infrastructure** → Banco de dados e integrações
* **API** → Controllers e endpoints

---

## 🔐 Autenticação

* Implementada com **JWT (JSON Web Token)**
* Usuários autenticados podem:

  * Criar recursos
  * Gerenciar informações cadastradas
* Usuários não autenticados:

  * Apenas visualizam os dados

---

## ⚙️ Tecnologias Utilizadas

### Backend

* .NET
* PostgreSQL
* JWT Authentication
* DDD

### Frontend

* React.js
* Next.js
* TailwindCSS

---

## 🚀 Funcionalidades

* Cadastro de usuários
* Autenticação com JWT
* Cadastro de:

  * Abrigos
  * Pontos de alimentação
  * Assistência médica
  * Pontos de doação
* Listagem pública de recursos
* Busca de pontos de apoio
* Visualização detalhada das informações

---

## 🧪 Contexto de Desenvolvimento

* ⏱️ Tempo: **48 horas**
* 👥 Equipe: **4 desenvolvedores**
* 🎯 Foco: entrega funcional sob pressão, priorizando impacto social

---

## 🔗 Repositórios

* 🔙 Backend:
  https://github.com/BernardoSsilva/Hackathon-backend

* 🎨 Frontend:
  https://github.com/BernardoSsilva/Hackathon-FrontEnd

---

## 👨‍💻 Contribuição

Neste projeto, atuei principalmente em:

* Desenvolvimento do backend
* Estruturação da arquitetura (DDD)
* Implementação de autenticação com JWT
* Modelagem de dados e integração com PostgreSQL

---

## 🌍 Impacto Esperado

* Maior acesso à informação em momentos críticos
* Melhor organização de recursos durante desastres
* Incentivo à colaboração comunitária
* Redução do tempo de resposta em emergências

---

## 📈 Possíveis Melhorias

* Testes automatizados
* Deploy em ambiente cloud
* Geolocalização dos recursos
* Notificações em tempo real
* Sistema de validação/moderação de informações

---

## 🤝 Equipe

<ul>
    <li><strong>Bernardo Santos: </strong><a href="https://www.linkedin.com/in/bernardo-santos-96a70b268/">💼 LinkedIn</a> ou <a href="https://github.com/BernardoSsilva">🙀 GitHub</a></li>
    <li><strong>Carolina Stange: </strong><a href="https://www.linkedin.com/in/carolina-stange-0b39ba280/">💼 LinkedIn</a> ou <a href="https://github.com/CarolinaStange15">🙀 GitHub</a></li>
    <li><strong>Éric Dagostim: </strong><a href="https://www.linkedin.com/in/eric-dagostim-nascimento/">💼 LinkedIn</a> ou <a href="https://github.com/EricDagostim">🙀 GitHub</a></li>
    <li><strong>Laís Kaminski: </strong><a href="https://www.linkedin.com/in/la%C3%ADs-kaminski-casagrande-580b7a251/">💼 LinkedIn</a> ou <a href="https://github.com/laiscasagrande">🙀 GitHub</a></li>
</ul>

---

## 💬 Considerações Finais

Este projeto demonstra a capacidade de:

* Trabalhar sob pressão
* Construir soluções completas (frontend + backend)
* Aplicar boas práticas de arquitetura
* Resolver problemas reais com impacto social

---

## 🎉 Agradecimentos

Projeto desenvolvido durante o Hackathon da comunidade KipperDev.
Agradecimentos especiais à organização pela oportunidade.

<p><a href="https://github.com/Fernanda-Kipper/hackathon-2024">Hackaton Comunidade KipperDev 2024<a> 💘</p>



