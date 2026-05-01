# 💰 Sistema de Gestão Financeira Familiar

Um sistema web completo e moderno para controle financeiro familiar, desenvolvido com HTML, CSS e JavaScript puro. Interface intuitiva, responsiva e com recursos avançados de gerenciamento.

![Status](https://img.shields.io/badge/status-ativo-success.svg)
![Versão](https://img.shields.io/badge/versão-1.0-blue.svg)
![Licença](https://img.shields.io/badge/licença-MIT-green.svg)

## 🚀 Demonstração

[**Acesse a demonstração ao vivo**](https://seu-usuario.github.io/gestao-financeira-familiar/)

> **Credenciais de teste:**
> - Usuário: `admin`
> - Senha: `123`

## ✨ Funcionalidades

### 📊 Dashboard Interativo
- **Visão Geral Financeira**: Saldo atual, receitas, despesas e dívidas futuras
- **Gráficos Dinâmicos**: 
  - Evolução mensal (linha)
  - Distribuição por categoria (pizza)
  - Comparativo receitas vs despesas (barras)
- **Cards Informativos**: Estatísticas em tempo real com indicadores visuais

### 💳 Gestão de Lançamentos
- **Registro Completo**: Data, descrição, categoria, valor e responsável
- **Tipos de Transação**: Receitas e despesas com identificação visual
- **Parcelamento Inteligente**: Suporte a compras parceladas com controle individual
- **Histórico Detalhado**: Tabela completa com todos os lançamentos

### 🔍 Filtros e Busca
- Busca em tempo real por descrição, categoria ou pessoa
- Filtros por:
  - Data (mês/ano)
  - Membro da família
  - Categoria
  - Tipo (receita/despesa)
- Combinação múltipla de filtros

### 👥 Multiusuário
- Sistema de login seguro
- Suporte a múltiplos membros da família
- Identificação visual por cores para cada membro
- Gestão de usuários e senhas

### 🎨 Personalização
- **Temas Customizáveis**: Escolha sua cor principal
- **Categorias Editáveis**: Crie e gerencie suas próprias categorias
- **Configurações Flexíveis**: Adapte o sistema às suas necessidades

### 📄 Relatórios
- **Exportação em PDF**: Relatório profissional com:
  - Cabeçalho personalizado
  - Resumo financeiro
  - Tabela completa de lançamentos
  - Formatação empresarial

### 💾 Armazenamento
- Dados salvos localmente no navegador (LocalStorage)
- Sem necessidade de servidor ou banco de dados externo
- Acesso offline total

## 🛠️ Tecnologias Utilizadas

- **HTML5**: Estrutura semântica moderna
- **CSS3**: 
  - Tailwind CSS (via CDN)
  - Custom properties para temas
  - Animations e transitions
  - Design responsivo
- **JavaScript ES6+**:
  - Vanilla JS (sem frameworks)
  - LocalStorage API
  - Manipulação avançada do DOM
- **Bibliotecas**:
  - [Chart.js](https://www.chartjs.org/) - Gráficos interativos
  - [jsPDF](https://github.com/parallax/jsPDF) - Geração de PDFs
  - [Font Awesome](https://fontawesome.com/) - Ícones
  - [Google Fonts](https://fonts.google.com/) - Tipografia (Inter)

## 📋 Pré-requisitos

- Navegador web moderno (Chrome, Firefox, Safari, Edge)
- JavaScript habilitado
- Nenhuma instalação adicional necessária

## 🚀 Como Usar

### Opção 1: Acesso Direto
1. Faça download do arquivo `index.html`
2. Abra o arquivo no seu navegador
3. Pronto! O sistema está funcionando

### Opção 2: Deploy no GitHub Pages
1. Faça fork deste repositório
2. Vá em Settings > Pages
3. Selecione a branch `main` como fonte
4. Seu site estará disponível em poucos minutos

### Opção 3: Servidor Local
```bash
# Com Python 3
python -m http.server 8000

# Com Node.js (http-server)
npx http-server

# Acesse http://localhost:8000
```

## 📖 Guia de Uso

### Primeiro Acesso
1. Use as credenciais padrão (admin/123)
2. Acesse as Configurações (ícone de engrenagem)
3. Altere sua senha
4. Adicione membros da família
5. Personalize categorias e tema

### Adicionando Lançamentos
1. Clique em "+ Lançamento" no topo
2. Preencha os dados:
   - Data da transação
   - Tipo (receita ou despesa)
   - Descrição
   - Categoria
   - Valor
   - Responsável
3. Para parcelamentos, marque a opção e informe o número de parcelas
4. Confirme o lançamento

### Visualizando Dados
- **Dashboard**: Acesse para ver visão geral e gráficos
- **Lançamentos**: Veja histórico completo com filtros
- Use a busca para encontrar transações específicas
- Combine filtros para análises detalhadas

### Gerando Relatórios
- Clique no ícone de PDF no topo
- O relatório será baixado automaticamente
- Contém todos os dados atuais do sistema

## 🎯 Estrutura do Projeto

```
gestao-financeira-familiar/
│
├── index.html          # Arquivo principal do sistema
├── README.md           # Este arquivo
└── LICENSE             # Licença MIT
```

## 🔒 Segurança

- **Dados Locais**: Todas as informações ficam no seu navegador
- **Sem Servidor**: Nenhum dado é enviado para servidores externos
- **Privacidade Total**: Você tem controle completo dos seus dados
- **Senhas**: Armazenadas localmente (recomenda-se não usar senhas reais)

> ⚠️ **Nota de Segurança**: Este é um projeto para demonstração e uso pessoal. Para ambientes de produção com dados sensíveis, implemente criptografia e autenticação mais robustas.

## 🤝 Contribuindo

Contribuições são bem-vindas! Para contribuir:

1. Faça fork do projeto
2. Crie uma branch para sua feature (`git checkout -b feature/MinhaFeature`)
3. Commit suas mudanças (`git commit -m 'Adiciona MinhaFeature'`)
4. Push para a branch (`git push origin feature/MinhaFeature`)
5. Abra um Pull Request

## 🐛 Reportando Bugs

Encontrou um bug? Abra uma [issue](../../issues) descrevendo:
- O que aconteceu
- O que era esperado
- Passos para reproduzir
- Screenshots (se aplicável)

## 📝 Roadmap

- [ ] Modo escuro
- [ ] Exportação para Excel
- [ ] Metas financeiras
- [ ] Notificações de vencimento
- [ ] Gráfico de evolução patrimonial
- [ ] Categorias com ícones
- [ ] Backup e restauração de dados
- [ ] PWA (Progressive Web App)

## 📄 Licença

Este projeto está sob a licença MIT. Veja o arquivo [LICENSE](LICENSE) para mais detalhes.

## 👨‍💻 Autor

**Matheus**
- Projeto desenvolvido como parte do portfólio pessoal

## 🙏 Agradecimentos

- Chart.js pela biblioteca de gráficos
- Tailwind CSS pelo framework CSS
- Font Awesome pelos ícones
- Comunidade open source

---

⭐ **Se este projeto foi útil, deixe uma estrela!** ⭐

📧 **Dúvidas?** Abra uma issue ou entre em contato!
