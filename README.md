# agente-de-vendas
Sistema inteligente de vendas que usa IA da Anthropic para qualificar leads, gerar estratégias personalizadas e automatizar conversas de vendas.
# 🤖 Agente de Vendas IA 

<div align="center">

![Logo](https://img.shields.io/badge/AI-Claude_4-purple?style=for-the-badge&logo=anthropic)
![React](https://img.shields.io/badge/React-18.2-61DAFB?style=for-the-badge&logo=react)
![License](https://img.shields.io/badge/License-MIT-green?style=for-the-badge)

**Sistema inteligente de vendas que usa IA da Anthropic para qualificar leads, gerar estratégias personalizadas e automatizar conversas de vendas.**

[🚀 Demo ao Vivo](https://seu-agente.vercel.app) • [📖 Documentação](#-funcionalidades) • [🐛 Reportar Bug](https://github.com/seuusuario/seurepo/issues)

![Screenshot do Dashboard](https://via.placeholder.com/800x400/1e293b/a855f7?text=Dashboard+do+Agente+de+Vendas+IA)

</div>

---

## ✨ Funcionalidades

### 🎯 **Gestão Inteligente de Leads**
- **Score automático** (0-100) baseado em comportamento e interesse
- **Classificação por temperatura**: Leads quentes 🔥, mornos 🌤️ e frios ❄️
- **Histórico completo** de interações e engajamento
- **Dashboard visual** com métricas em tempo real

### 🧠 **Análise com IA Claude**
- **Análise de perfil** detalhada de cada lead
- **Sugestões de abordagem** personalizadas e testadas
- **Scripts de vendas** gerados automaticamente
- **Previsão de objeções** e contrapontos eficazes
- **Estimativa de conversão** baseada em dados

### 💬 **Chat Inteligente**
- **Modo automático**: IA simula respostas do cliente para treinamento
- **Modo manual**: Sugestões de resposta em tempo real
- **Histórico de conversas** completo e pesquisável
- **Gatilhos mentais** aplicados automaticamente

### 📊 **Métricas e Relatórios**
- Taxa de conversão em tempo real
- Score médio dos leads
- Leads quentes prioritários
- Tempo de resposta médio

---

## 🎥 Demonstração

<div align="center">

### Dashboard Principal
![Dashboard](https://via.placeholder.com/600x300/1e293b/a855f7?text=Dashboard+com+M%C3%A9tricas)

### Análise de Lead com IA
![Análise](https://via.placeholder.com/600x300/1e293b/ec4899?text=An%C3%A1lise+Inteligente)

### Chat com Sugestões
![Chat](https://via.placeholder.com/600x300/1e293b/8b5cf6?text=Chat+Inteligente)

</div>

---

## 🚀 Como Usar

### **Pré-requisitos**

Antes de começar, você precisa ter instalado:

- [Node.js](https://nodejs.org/) (versão 16 ou superior)
- [Git](https://git-scm.com/)
- Conta na [Anthropic](https://www.anthropic.com/) (para API Key do Claude)

### **Instalação**

1️⃣ **Clone o repositório**
```bash
git clone https://github.com/seuusuario/agente-vendas-ia.git
cd agente-vendas-ia
```

2️⃣ **Instale as dependências**
```bash
npm install
```

3️⃣ **Configure as variáveis de ambiente**

Crie um arquivo `.env` na raiz do projeto:

```env
VITE_ANTHROPIC_API_KEY=sua_chave_api_aqui
```

> 💡 **Como obter sua API Key:**
> 1. Acesse [console.anthropic.com](https://console.anthropic.com/)
> 2. Faça login ou crie uma conta
> 3. Vá em "API Keys"
> 4. Clique em "Create Key"
> 5. Copie e cole no arquivo `.env`

4️⃣ **Inicie o servidor de desenvolvimento**
```bash
npm run dev
```

5️⃣ **Abra no navegador**
```
http://localhost:5173
```

---

## 📦 Estrutura do Projeto

```
agente-vendas-ia/
├── public/              # Arquivos estáticos
├── src/
│   ├── components/      # Componentes React
│   │   └── AISalesAgent.jsx
│   ├── utils/          # Funções auxiliares
│   ├── App.jsx         # Componente principal
│   └── main.jsx        # Entry point
├── .env                # Variáveis de ambiente (não commitar!)
├── .gitignore          # Arquivos ignorados pelo Git
├── package.json        # Dependências do projeto
├── vite.config.js      # Configuração do Vite
└── README.md           # Este arquivo
```

---

## 🛠️ Tecnologias

<table>
  <tr>
    <td align="center" width="96">
      <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/react/react-original.svg" width="48" height="48" alt="React" />
      <br>React
    </td>
    <td align="center" width="96">
      <img src="https://vitejs.dev/logo.svg" width="48" height="48" alt="Vite" />
      <br>Vite
    </td>
    <td align="center" width="96">
      <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/tailwindcss/tailwindcss-plain.svg" width="48" height="48" alt="Tailwind" />
      <br>Tailwind
    </td>
    <td align="center" width="96">
      <img src="https://www.anthropic.com/images/icons/safari-pinned-tab.svg" width="48" height="48" alt="Claude" />
      <br>Claude AI
    </td>
    <td align="center" width="96">
      <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/javascript/javascript-original.svg" width="48" height="48" alt="JavaScript" />
      <br>JavaScript
    </td>
  </tr>
</table>

### **Stack Principal**

- **Frontend**: React 18.2 + Vite
- **Estilização**: Tailwind CSS
- **Ícones**: Lucide React
- **IA**: Claude Sonnet 4 (Anthropic API)
- **Deploy**: Vercel

---

## 🎯 Roadmap

### ✅ Versão 1.0 (Atual)
- [x] Dashboard com métricas
- [x] Análise de leads com IA
- [x] Chat inteligente
- [x] Sugestões automáticas
- [x] Score de leads

### 🚧 Versão 2.0 (Em desenvolvimento)
- [ ] Integração com WhatsApp
- [ ] Integração com CRMs (Pipedrive, HubSpot)
- [ ] Relatórios em PDF
- [ ] Sistema de notificações
- [ ] Modo escuro
- [ ] Multi-idioma

### 🔮 Versão 3.0 (Planejado)
- [ ] Voice AI para ligações
- [ ] Análise de sentimento
- [ ] A/B testing de scripts
- [ ] Treinamento personalizado da IA
- [ ] App mobile

---

## 🤝 Como Contribuir

Contribuições são sempre bem-vindas! Veja como você pode ajudar:

1. **Fork** o projeto
2. Crie uma **branch** para sua feature (`git checkout -b feature/MinhaFeature`)
3. **Commit** suas mudanças (`git commit -m 'Adiciona nova feature'`)
4. **Push** para a branch (`git push origin feature/MinhaFeature`)
5. Abra um **Pull Request**

### **Encontrou um bug?**
Abra uma [issue](https://github.com/marianacamurcaoliveira-cmyk/agente-de-vendas ) descrevendo:
- O que aconteceu
- O que você esperava
- Passos para reproduzir
- Capturas de tela (se aplicável)

---

## 📄 Licença

Este projeto está sob a licença MIT. Veja o arquivo [LICENSE](LICENSE) para mais detalhes.

---

## 👨‍💻 Autor

<table>
  <tr>
    <td align="center">
      <a href="https://github.com/seuusuario">
        <img src="https://github.com/seuusuario.png" width="100px;" alt="Foto do Autor"/><br>
        <sub>
          <b>Mari Ayres </b>
        </sub>
      </a>
      <br>
      <a href="https://linkedin.com/in/seuperfil" title="LinkedIn">
        <img src="https://img.shields.io/badge/-LinkedIn-0077B5?style=flat&logo=linkedin&logoColor=white"/>
      </a>
      <a href="mailto:marianacamurcaoliveira@gmail.com" title="Email">
        <img src="https://img.shields.io/badge/-Email-D14836?style=flat&logo=gmail&logoColor=white"/>
      </a>
    </td>
  </tr>
</table>

---

## 🙏 Agradecimentos

- [Anthropic](https://www.anthropic.com/) - Pela incrível API do Claude
- [Lucide](https://lucide.dev/) - Pelos ícones lindos
- [Tailwind CSS](https://tailwindcss.com/) - Pelo framework CSS
- [Vercel](https://vercel.com/) - Pelo hosting gratuito

---

## 📞 Suporte

Precisa de ajuda? Entre em contato:

- 📧 Email: comercial@seuvital.com.br
- 💬 WhatsApp: (85) 992078191


---

<div align="center">

**⭐ Se este projeto te ajudou, deixe uma estrela!**

![Stars](https://github.com/marianacamurcaoliveira-cmyk/agente-de-vendas)




</div>
git add README.md
git commit -m "docs: adiciona README completo"
git push
