# 🎡 Roda da Carreira

> Uma aplicação web simples, visual e interativa inspirada na ferramenta de autocoaching e planejamento de carreira da **Roda da Carreira**.

O objetivo deste projeto é dar clareza estratégica ao seu momento profissional atual, permitindo avaliar 8 dimensões essenciais, identificar sua principal alavanca de crescimento e traçar ações práticas.

![Licença](https://img.shields.io/badge/license-MIT-blue)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black)
![Chart.js](https://img.shields.io/badge/Chart.js-FF6384?style=flat&logo=chartdotjs&logoColor=white)
![Google Gemini](https://img.shields.io/badge/Google%20Gemini-8E75B2?style=flat&logo=googlegemini&logoColor=white)

---

## 🎯 As 8 Dimensões Avaliadas

Para cada dimensão, você atribui uma nota de **1** ("Estagnação Total") a **10** ("Plenitude"):

1. **Competência Técnica**
2. **Habilidades Comportamentais**
3. **Networking e Relacionamentos**
4. **Equilíbrio Vida e Trabalho**
5. **Remuneração e Benefícios**
6. **Propósito e Satisfação**
7. **Visibilidade e Marca Pessoal**
8. **Perspectiva de Crescimento**

---

## 🚀 Funcionalidades

- 📊 **Visualização Dinâmica**: Alternância entre gráficos no formato **Radar** ou **Fatias Polares**.
- 📈 **Métricas Instantâneas**: Cálculo automático do *Índice de Plenitude Global* e destaque visual para a área com menor nota.
- 🤖 **Mentor IA (Google Gemini)**: Análise inteligente do seu perfil com geração de um plano de ação de 7 dias com base nas suas notas e reflexões.
- 🔑 **Segurança e Privacidade**: A chave da API do Gemini é salva exclusivamente no `localStorage` do seu navegador.
- 📝 **Plano de Ação Estratégico**: Define área foco, data limite e ação prática imediata.
- 🖨️ **Exportação PDF / Impressão**: Layout estilizado via `@media print` para salvar relatórios limpos e prontos para arquivamento ou mentoria.

---

## 🛠️ Tecnologias Utilizadas

- **HTML5** & **CSS3** (Tailwind CSS via CDN)
- **JavaScript (ES6+)**
- **Chart.js**: Renderização dos gráficos interativos.
- **Google Gemini API** (`gemini-2.5-flash`): Geração da análise preditiva e plano de ação.

---

## 💻 Como Executar o Projeto

Como o projeto é totalmente *client-side* (tudo roda direto no navegador):

1. Clone este repositório:
   ```bash
   git clone [https://github.com/seu-usuario/roda-da-carreira.git](https://github.com/seu-usuario/roda-da-carreira.git)
