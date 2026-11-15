# JobMatch AI 🚀
### Encontre oportunidades compatíveis e prepare seu currículo para cada vaga.

O **JobMatch AI** é uma aplicação web que tem como objetivo ajudar profissionais a encontrar oportunidades de emprego compatíveis com seus perfis e preparar currículos personalizados, otimizados para sistemas ATS (*Applicant Tracking Systems*).

A proposta é utilizar inteligência artificial para comparar as informações de um currículo com os requisitos de uma vaga, identificar pontos fortes e lacunas de compatibilidade e auxiliar na criação de uma versão direcionada do currículo.

> **Nosso princípio:** melhorar a forma como o candidato apresenta suas experiências reais, sem inventar competências, qualificações ou resultados que não possui.

---

## 📸 Demonstração visual

### Página inicial

A página inicial apresenta a proposta do JobMatch AI, destacando a utilização de inteligência artificial para conectar candidatos a oportunidades profissionais e personalizar currículos.

<img width="1277" height="505" alt="image" src="https://github.com/user-attachments/assets/7644694d-7d5d-448f-a119-c57419fb1a8a" />

### Funcionalidades

A plataforma foi idealizada em torno de três funcionalidades principais: encontrar oportunidades compatíveis, identificar lacunas no perfil profissional e gerar currículos personalizados para cada vaga.

<img width="1275" height="509" alt="image" src="https://github.com/user-attachments/assets/348b64e4-6655-4001-aa40-9e5a5ca1075f" />

### Como funciona

O fluxo proposto para utilização da plataforma é dividido em três etapas:

<img width="1270" height="514" alt="image" src="https://github.com/user-attachments/assets/33fa708f-a289-4449-8a8d-060dfd91dec7" />

### Final da página

Sua próxima oportunidade começa com um bom match

<img width="1277" height="496" alt="image" src="https://github.com/user-attachments/assets/bdb4750d-7c7f-4f10-831e-513be26dab4c" />

---

## 🎯 Problema que o projeto resolve

Durante processos seletivos, muitas empresas utilizam sistemas ATS para organizar, filtrar e classificar currículos antes de encaminhá-los aos recrutadores.

Isso significa que um candidato pode possuir experiências e qualificações relevantes para uma oportunidade, mas não apresentar essas informações de maneira suficientemente clara ou alinhada aos requisitos da vaga.

O JobMatch AI busca ajudar a resolver esse problema, permitindo que o candidato:

- Entenda o quanto seu perfil está alinhado a uma oportunidade.
- Identifique competências e palavras-chave relevantes.
- Descubra requisitos que não estão evidenciados em seu currículo.
- Receba recomendações de melhoria.
- Personalize seu currículo para diferentes oportunidades.
- Apresente suas experiências de maneira mais clara e organizada.

## ✨ Funcionalidades propostas

O projeto foi concebido com as seguintes funcionalidades:

| Funcionalidade | Descrição |
|---|---|
| Perfil profissional | Cadastro de experiências, formação, competências e certificações. |
| Cadastro de vagas | Inserção da descrição de oportunidades profissionais. |
| Match Score | Indicador de compatibilidade entre currículo e vaga. |
| Análise de palavras-chave | Identificação de competências encontradas, parciais e ausentes. |
| Recomendações | Sugestões para melhorar a apresentação profissional. |
| Gerador de currículo | Criação de versões direcionadas para cada oportunidade. |
| Exportação em PDF | Geração de currículo com estrutura simples e compatível com a leitura ATS. |
| Histórico | Organização das oportunidades analisadas e dos currículos gerados. |

**Observação:** esta lista representa o escopo planejado do produto. A disponibilidade efetiva de cada funcionalidade depende da implementação e validação da versão publicada.

## 🧠 Como funciona a análise

O fluxo principal idealizado para o JobMatch AI é:

**1. Entrada das informações**

O candidato fornece seu currículo e a descrição da vaga desejada.

**2. Interpretação dos dados**

A aplicação identifica informações profissionais, experiências, formação acadêmica, competências e requisitos apresentados na oportunidade.

**3. Comparação e compatibilidade**

As informações são comparadas para identificar correspondências entre o perfil do candidato e as exigências da vaga.

**4. Identificação de palavras-chave**

São identificadas competências encontradas, parcialmente identificadas e não evidenciadas no currículo.

**5. Recomendações de melhoria**

A aplicação apresenta sugestões para melhorar a organização e a descrição das experiências profissionais.

**6. Geração do currículo personalizado**

A partir das informações reais do candidato, é proposta uma versão direcionada à oportunidade, priorizando experiências e competências relevantes.

**7. Exportação**

O documento final poderá ser exportado em PDF, com estrutura simples, texto selecionável e organização adequada à leitura por sistemas ATS.

## 🎨 Design e identidade visual

A interface foi desenvolvida com uma proposta visual moderna, minimalista e tecnológica.

O design utiliza uma identidade baseada em:

- Azul profissional: `#2563EB`
- Azul-claro: `#38BDF8`
- Branco: `#FFFFFF`
- Fundo claro: `#F8FAFC`
- Texto principal: `#0F172A`
- Verde para indicadores positivos: `#16A34A`

O design system escolhido para o projeto foi **shadcn/ui**, com a proposta de utilizar componentes reutilizáveis, consistentes e responsivos.

Também foram considerados ícones Lucide e elementos visuais para apresentar indicadores de compatibilidade.

## 🛠️ Tecnologias e ferramentas

| Ferramenta | Utilização |
|---|---|
| Lovable | Desenvolvimento da aplicação por meio de inteligência artificial. |
| shadcn/ui | Design system e componentes da interface. |
| Lucide Icons | Identidade visual dos ícones. |
| Inteligência Artificial | Conceito central para análise e personalização de currículos. |

*As tecnologias de backend, banco de dados e serviços externos serão documentadas conforme sua efetiva implementação no projeto.*

## 🤖 Desenvolvimento com IA: o Mega Prompt

O desenvolvimento começou a partir de um prompt único em Markdown, elaborado antes da primeira geração da aplicação no Lovable.

O objetivo foi fornecer uma visão completa do produto, descrevendo sua proposta, identidade visual, estrutura de navegação e funcionalidades desejadas.

O prompt contemplou:

- Conceito e identidade do JobMatch AI.
- Definição do design system shadcn/ui.
- Paleta de cores e diretrizes visuais.
- Estrutura das páginas e navegação.
- Cadastro e gerenciamento do perfil profissional.
- Comparação entre currículos e vagas.
- Critérios para o Match Score.
- Identificação de palavras-chave.
- Geração e edição de currículos personalizados.
- Regras de integridade para impedir informações inventadas.
- Exportação de documentos em PDF.
- Arquitetura planejada para armazenamento e integrações com IA.

### Evolução do desenvolvimento

**Versão inicial — Mega Prompt**

Foi elaborado um prompt abrangente para orientar a construção de uma plataforma de empregabilidade, indo além de um simples gerador de currículos.

**Primeira geração — Lovable**

O prompt foi utilizado no Lovable para gerar a primeira versão da aplicação, incluindo a identidade visual, a página inicial, a apresentação das funcionalidades e a seção explicativa sobre o funcionamento do produto.

**Refinamentos**

A primeira geração apresentou alguns pontos que precisariam de correção e aprimoramento. A etapa de refinamento foi planejada para corrigir esses problemas, validar os fluxos e evoluir as funcionalidades.

O desenvolvimento foi realizado dentro das limitações de créditos disponíveis na versão gratuita da ferramenta.

## 🔒 Integridade das informações profissionais

Um dos princípios fundamentais do JobMatch AI é preservar a autenticidade das informações do candidato.

A personalização do currículo deve melhorar a apresentação das experiências existentes, sem criar informações falsas para aumentar artificialmente a compatibilidade com uma vaga.

A ferramenta deve respeitar os conhecimentos, experiências, formação e resultados efetivamente apresentados pelo usuário.

## 🚀 Aplicação

Acesse a aplicação: 

**[JobMatch AI — Acessar plataforma](https://76a32aba-6cc7-4b11-97d1-2a99dcbf7761.lovableproject.com/cadastro)**

## 📚 Contexto do projeto

Este projeto foi desenvolvido como parte de um desafio prático do bootcamp Santander em parceria com a DIO.

O desafio propõe a utilização do Lovable para desenvolver uma aplicação que compare currículos com descrições de vagas, identifique palavras-chave e gere versões de currículos otimizadas para sistemas ATS.

Além da construção da aplicação, o projeto busca explorar o desenvolvimento assistido por inteligência artificial, a elaboração de prompts, a evolução de produtos digitais e a documentação de projetos utilizando GitHub.

---

**Desenvolvido por Leonardo Vicente Bueno Camargo**

Projeto de estudo e desenvolvimento prático — Santander & DIO.
