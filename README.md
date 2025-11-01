#  Pipeline de Deploy de Aplicação com GitLab CI/CD, Docker e Kubernetes

##  Descrição

Este projeto tem como objetivo demonstrar a criação de um pipeline de deploy automatizado de uma aplicação **Node.js**, utilizando **GitLab CI/CD**.
O projeto contempla dois cenários principais:

* **Cenário 1:** Deploy da aplicação Node.js em um container Docker.
* **Cenário 2:** Deploy da aplicação Node.js em um cluster Kubernetes na nuvem, utilizando o **Google Cloud Platform (GCP)**.

O projeto foi estruturado para ser apresentado em **duas branches**:

* `docker-deploy`: contém o deploy da aplicação executando em um container Docker.
* `kubernetes-deploy`: contém o deploy da aplicação sendo executada em um cluster Kubernetes na nuvem GCP.

---

## 🏗️ Estrutura do Projeto

```
📦 gitlab-cicd-app-base
 ┣ 📂 src/                # Código-fonte da aplicação Node.js
 ┣ 📂 .gitlab-ci.yml      # Pipeline CI/CD
 ┣ 📂 Dockerfile          # Instruções para construção da imagem Docker
 ┣ 📂 k8s/                # Manifests do Kubernetes (deployment, service, etc.)
 ┗ 📜 README.md           # Documentação do projeto
```

---

## ⚙️ Tecnologias Utilizadas

* **GitLab CI/CD** – Automação do pipeline de integração e entrega contínua.
* **Docker** – Criação de containers para empacotamento da aplicação.
* **Kubernetes (GKE)** – Orquestração de containers na nuvem.
* **Node.js** – Linguagem da aplicação base.
* **Google Cloud Platform (GCP)** – Provedor de nuvem utilizado no projeto.

---

## 🧩 Etapas do Pipeline

O pipeline é composto por quatro estágios principais:

1. **Build:**
   Constrói a imagem Docker da aplicação Node.js.

2. **Test:**
   Executa testes automatizados para validar o funcionamento da aplicação.

3. **Deploy Docker:**
   Realiza o deploy da aplicação em um container local.

4. **Deploy Kubernetes:**
   Efetua o deploy da aplicação em um cluster Kubernetes hospedado no GCP.

---

##  Conceitos Aplicados

* **CI/CD:** Configuração de um pipeline automatizado no GitLab para build, test e deploy.
* **Dockerfile:** Empacotamento da aplicação Node.js em um container padronizado.
* **Kubernetes Manifests:** Automação do deployment, service e configuração da aplicação na nuvem.
* **Branches Diferenciadas:** Organização do código entre os ambientes Docker e Kubernetes.

---

## 📂 Repositório Base do Projeto

O projeto foi desenvolvido a partir do repositório base fornecido pelo instrutor:
🔗 [gitlab.com/denilsonbonatti/gitlab-cicd-app-base](https://gitlab.com/denilsonbonatti/gitlab-cicd-app-base/-/tree/main)

---

📚 Feito por Letícia Montenegro 🔗 Perfil DIO: https://web.dio.me/users/leehmontenegro 🔗 LinkedIn: https://www.linkedin.com/in/leehmontenegro/ 💻 Projeto conceitual desenvolvido para o desafio DIO

##  Conclusão

Mesmo sem a execução prática completa por limitações de hardware, este projeto demonstra domínio sobre os conceitos de **integração contínua**, **entrega contínua**, **containerização** e **orquestração em nuvem**, fundamentais no ciclo moderno de desenvolvimento DevOps.

---
