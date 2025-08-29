# 🚛 Sistema de Controle de Prazos - Agenciamento de Cargas

[![HTML5](https://img.shields.io/badge/HTML5-%23E34F26.svg?style=for-the-badge&logo=html5&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/HTML)
[![CSS3](https://img.shields.io/badge/CSS3-%231572B6.svg?style=for-the-badge&logo=css3&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/CSS)
[![JavaScript](https://img.shields.io/badge/JavaScript-%23323330.svg?style=for-the-badge&logo=javascript&logoColor=%23F7DF1E)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)

Sistema web moderno e elegante para cálculo e controle de prazos no agenciamento de cargas com timeline visual interativa e calculadora automática de dias corridos.

## ✨ Funcionalidades

### 📅 **Controle de Datas Flexível**
- **Data inicial**: Emissão do HAWB como marco de referência
- **Dupla opção para cada etapa**:
  - 🔄 Seleção automática por período (10, 30, 60, 90 dias)
  - 📅 Escolha manual através de calendário
- **Cálculo inteligente**: Soma automática dos períodos ou cálculo baseado em datas específicas

### 📊 **Timeline Visual Interativa**
- Linha do tempo horizontal com todos os marcos do processo
- Indicadores visuais dos períodos entre cada etapa
- Exibição clara do número de dias entre marcos
- Atualização em tempo real conforme as seleções

### 🧮 **Calculadora Automática**
- Soma total de dias do processo completo
- Cálculo da data final de repasse
- Atualização instantânea dos resultados
- Validação automática de datas

### 📱 **Design Responsivo**
- Interface moderna com cores equilibradas e tenues
- Layout adaptável para desktop e mobile
- Tema profissional adequado ao setor logístico
- Experiência de usuário intuitiva

## 🚀 Como Usar

### **Passo 1: Data Inicial**
1. Insira a **data de emissão do HAWB** no primeiro campo
2. Esta será a data base para todos os cálculos

### **Passo 2: Configurar Etapas**
Para cada etapa do processo, você tem duas opções:

**Opção A - Período Automático:**
1. Selecione o período desejado (10, 30, 60 ou 90 dias)
2. O sistema calculará automaticamente a próxima data

**Opção B - Data Específica:**
1. Clique no campo de calendário
2. Escolha a data desejada
3. O sistema calculará os dias decorridos automaticamente

### **Passo 3: Acompanhar Resultados**
- Visualize o progresso na timeline
- Confira o total de dias acumulados
- Veja a data final prevista para o repasse

## 💼 Etapas do Processo

| Ordem | Etapa | Descrição |
|-------|-------|-----------|
| 1 | **Emissão do HAWB** | Marco inicial do processo |
| 2 | **Chegada** | Data de chegada da carga |
| 3 | **Validação do RA** | Validação do Registro de Armazenagem |
| 4 | **Envio do Faturamento** | Emissão e envio da fatura |
| 5 | **Escrituração** | Processo de escrituração contábil |
| 6 | **Risco Sacado** | Data do saque do risco |
| 7 | **Repasse** | Data final de repasse |

## 🛠️ Tecnologias Utilizadas

- **HTML5**: Estrutura semântica e moderna
- **CSS3**: Estilização avançada com flexbox e grid
- **JavaScript**: Lógica de cálculos e interatividade
- **Design Responsivo**: Compatível com todos os dispositivos

## 📋 Requisitos

- **Navegador**: Qualquer navegador moderno (Chrome, Firefox, Safari, Edge)
- **JavaScript**: Habilitado
- **Resolução**: Otimizado para desktop e mobile

## 📁 Estrutura do Projeto

```
cargo-timeline-system/
├── index.html          # Arquivo principal do sistema
├── README.md          # Documentação do projeto
└── screenshots/       # Capturas de tela (opcional)
```

## 🚀 Instalação e Uso

1. **Clone ou baixe** este repositório
2. **Abra** o arquivo `index.html` em qualquer navegador
3. **Comece a usar** o sistema imediatamente!

Não há necessidade de instalação de dependências ou configuração adicional.

## 📸 Screenshots

*Adicione aqui capturas de tela do sistema em funcionamento*

## 💡 Exemplos de Uso

### Exemplo 1: Usando Períodos Automáticos
- **HAWB**: 01/06/2025
- **Chegada**: +30 dias = 01/07/2025
- **Validação RA**: +10 dias = 11/07/2025
- **Total**: 40 dias corridos

### Exemplo 2: Usando Datas Específicas
- **HAWB**: 01/06/2025
- **Chegada**: 15/07/2025 (44 dias calculados automaticamente)
- **Validação RA**: 20/07/2025 (5 dias adicionais)
- **Total**: 49 dias corridos

## 🤝 Como Contribuir

1. Faça um fork do projeto
2. Crie uma branch para sua feature (`git checkout -b feature/NovaFuncionalidade`)
3. Commit suas mudanças (`git commit -m 'Adiciona nova funcionalidade'`)
4. Push para a branch (`git push origin feature/NovaFuncionalidade`)
5. Abra um Pull Request

## 📄 Licença

Este projeto está sob a licença MIT. Veja o arquivo [LICENSE](LICENSE) para mais detalhes.

## 💡 Melhorias Futuras

- [ ] Exportação de relatórios em PDF
- [ ] Salvamento de configurações no localStorage
- [ ] Notificações de prazos próximos ao vencimento
- [ ] Integração com APIs de transportadoras
- [ ] Histórico de processos
- [ ] Múltiplos processos simultâneos
- [ ] Dashboard executivo

## 🔧 Personalização

O sistema pode ser facilmente personalizado:
- **Cores**: Modifique as variáveis CSS no cabeçalho
- **Períodos**: Altere os valores dos seletores no JavaScript
- **Etapas**: Adicione ou remova etapas conforme necessário
- **Validações**: Implemente regras de negócio específicas

## 📞 Suporte

Para dúvidas, sugestões ou problemas:
- Abra uma [issue](../../issues) no GitHub
- Entre em contato através do seu canal preferido

## 🏆 Características Técnicas

- **Zero dependências**: Funciona sem bibliotecas externas
- **Offline-first**: Funciona sem conexão com internet
- **Mobile-friendly**: Interface adaptada para dispositivos móveis
- **Acessibilidade**: Seguindo padrões de acessibilidade web
- **Performance**: Carregamento rápido e responsivo

---

**Desenvolvido com ❤️ para o setor logístico brasileiro** 🇧🇷

*Sistema criado especificamente para profissionais do agenciamento de cargas, facilitando o controle de prazos e otimizando processos logísticos.*
