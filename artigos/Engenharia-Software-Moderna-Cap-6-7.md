# 📄 Título: Engenharia de Software Moderna – Capítulos 6 e 7

**Capítulos:** 6 – Padrões de Projeto / 7 – Arquitetura  
**Fonte:** Engenharia de Software Moderna  
**Link:** [https://engsoftmoderna.info/](https://engsoftmoderna.info/)

---

## 📝 Resumo

Os capítulos 6 e 7 do livro **Engenharia de Software Moderna** abordam dois pilares essenciais para o desenvolvimento de sistemas robustos e sustentáveis: **padrões de projeto** e **arquitetura de software**. Juntos, esses capítulos fornecem fundamentos teóricos e práticos para lidar com problemas recorrentes de forma organizada, reutilizável e escalável.

---

### 🔧 Capítulo 6: Padrões de Projeto

O capítulo introduz os *Design Patterns* como **soluções reutilizáveis para problemas recorrentes** no desenvolvimento de software. Eles promovem modularidade, legibilidade e facilitam a manutenção do sistema.

Os padrões são agrupados em três categorias:

- **Padrões Criacionais** – tratam da criação de objetos:
  - *Factory Method*
  - *Singleton*

- **Padrões Estruturais** – lidam com a composição de classes e objetos:
  - *Adapter*
  - *Composite*

- **Padrões Comportamentais** – focam na interação entre objetos:
  - *Observer*
  - *Strategy*

O capítulo reforça que os padrões devem ser utilizados com **moderação**, evitando o excesso de abstrações (*overengineering*), que pode tornar o sistema mais difícil de compreender e manter.

---

### 🏗️ Capítulo 7: Arquitetura

O capítulo 7 discute o impacto das **decisões arquiteturais** no sucesso e na evolução de sistemas de software. Ele apresenta diferentes estilos arquiteturais e seus trade-offs.

#### 🧱 Arquitetura em Camadas
Divide o sistema em camadas funcionais, com comunicação hierárquica entre elas:

- **Camada de Apresentação** (interface com o usuário)
- **Camada de Negócios** (regras e lógica)
- **Camada de Dados** (persistência)

Esse estilo facilita a manutenção e promove **separação de responsabilidades**, sendo comum em aplicações corporativas.

#### 🧩 Arquitetura MVC (Model-View-Controller)

Divide a aplicação em:

- **Modelo** – lógica e dados
- **Visão** – interface com o usuário
- **Controlador** – coordena as interações

O padrão **MVC** é valorizado por permitir **trabalho paralelo entre equipes**, reutilização e testabilidade, sendo amplamente adotado em aplicações web e desktop.

#### 🧠 Reflexão sobre Decisões Arquiteturais

O capítulo destaca que muitas decisões arquiteturais são de **longo prazo** e só mostram seus impactos com o tempo. Traz como exemplo o famoso debate entre **Tanenbaum (microkernel)** e **Torvalds (monolito)** para mostrar que não existe uma única resposta certa — as escolhas dependem do contexto técnico e organizacional.

---

## 🔑 Conceitos Principais

- Reutilização de soluções com *design patterns*
- Organização em camadas para escalabilidade e manutenção
- Modularidade e separação de responsabilidades com MVC
- Importância da simplicidade e clareza no design
- Impacto de decisões arquiteturais no ciclo de vida do software
- Escolher arquitetura e padrões com base no **contexto real**

---

## 💭 Reflexão Pessoal

Esses capítulos mostram como a engenharia de software é tanto técnica quanto estratégica. Padrões de projeto e arquitetura não são apenas ferramentas de organização — eles moldam a **forma como um sistema evolui** e como os times interagem com ele. Aplicar essas práticas de forma consciente ajuda a evitar armadilhas comuns e torna o software mais preparado para mudanças futuras.

---

✅ Leitura recomendada: [https://engsoftmoderna.info/](https://engsoftmoderna.info/)
