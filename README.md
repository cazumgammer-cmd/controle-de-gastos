# 💰 Controle de Gastos

Uma aplicação web moderna e intuitiva para gerenciar suas receitas e despesas pessoais.

## ✨ Características

- 📊 **Dashboard completo** com resumo de receitas, despesas e saldo
- 💹 **Gráficos interativos** (Pizza, Barras e Linhas)
- 🏷️ **Categorização** de lançamentos
- 🗂️ **Filtros avançados** por categoria, tipo e ordem
- 📅 **Navegação por mês** com indicador de data
- 💳 **Múltiplas formas de pagamento** (Dinheiro, Débito, Crédito, Pix, Transferência)
- 🌙 **Tema claro/escuro** automático
- 📱 **Responsivo** para desktop e mobile
- 💾 **Dados salvos localmente** no navegador (sem necessidade de backend)
- ⚡ **100% offline** - funciona sem conexão com internet

## 🚀 Como Usar

### Online (GitHub Pages)
Acesse diretamente: [https://cazumgammer-cmd.github.io/controle-de-gastos/](https://cazumgammer-cmd.github.io/controle-de-gastos/)

### Localmente
1. Clone o repositório:
```bash
git clone https://github.com/cazumgammer-cmd/controle-de-gastos.git
cd controle-de-gastos
```

2. Abra `index.html` no navegador:
```bash
open index.html
# ou use um servidor local:
python -m http.server 8000
```

## 📝 Como Funciona

### Adicionando Lançamentos
1. Escolha entre **Despesa** ou **Receita**
2. Preencha a descrição (ex: "Aluguel", "Salário")
3. Insira o valor
4. Selecione a data
5. Escolha a categoria
6. Defina a forma de pagamento
7. Adicione observações (opcional)
8. Clique em "Adicionar lançamento"

### Abas Disponíveis

**📋 Lançamentos**
- Lista completa de transações do mês
- Filtros por categoria, tipo e ordem
- Opção de remover lançamentos

**📊 Gráficos**
- Pizza: distribuição de despesas por categoria
- Barras: comparação receitas vs despesas (6 meses)
- Linha: evolução do saldo (6 meses)

**🏷️ Categorias**
- Resumo de despesas por categoria com barras visuais
- Resumo de receitas por categoria

## 📊 Categorias Disponíveis

### Despesas
- Moradia
- Alimentação
- Transporte
- Saúde
- Lazer
- Educação
- Vestuário
- Assinaturas
- Outros

### Receitas
- Salário
- Freelance
- Investimentos
- Presente
- Outros

## 💾 Armazenamento

Os dados são salvos automaticamente no `localStorage` do navegador:
- Cada lançamento inclui: descrição, valor, data, categoria, forma de pagamento e observações
- Os dados persistem entre sessões
- Para fazer backup: copie os dados de `localStorage` ou exporte em JSON

## 🎨 Tema

A aplicação detecta automaticamente a preferência do sistema:
- 🌞 **Tema claro**: perfeito para uso diurno
- 🌙 **Tema escuro**: confortável à noite

## 🛠️ Tecnologias

- **HTML5** - Estrutura
- **CSS3** - Estilos responsivos
- **JavaScript vanilla** - Lógica da aplicação
- **Chart.js** - Gráficos interativos
- **Tabler Icons** - Ícones
- **LocalStorage** - Persistência de dados

## 📱 Compatibilidade

- Chrome/Edge 90+
- Firefox 88+
- Safari 14+
- Opera 76+
- Navegadores móveis (iOS Safari, Chrome Mobile)

## 🔐 Privacidade

- Todos os dados são salvos **localmente** no seu navegador
- Nenhuma informação é enviada a servidores externos
- Você tem controle total sobre seus dados

## 📄 Licença

Este projeto é de código aberto e disponível para uso pessoal e comercial.

## 👨‍💻 Autor

Desenvolvido com ❤️ por **cazumgammer-cmd**

---

**Dica:** Use a barra de orçamento para acompanhar o comprometimento da sua renda com despesas!