# 🐧 Usando Linux - Apps Recomendados

Documentação oficial de aplicativos recomendados pela comunidade **Usando Linux**.

## Início Rápido

### Pré-requisitos

- Node.js (versão 14 ou superior)
- npm ou yarn

### Instalação

```bash
# Clone o repositório
git clone https://github.com/usando-linux/apps-recomendados.git
cd apps-recomendados

# Instale as dependências
npm install

# Inicie o servidor de desenvolvimento
npm run dev
```

O site estará disponível em: http://localhost:3000

## Estrutura do Projeto

```
apps-recomendados/
├── docs/                   # Documentação do docsify
│   ├── index.html          # Configuração principal
│   ├── _sidebar.md         # Menu lateral
│   ├── README.md           # Página inicial
│   ├── apps/               # Seção de aplicativos
├── package.json            # Configuração do projeto
└── README.md               # Este arquivo
```

## Desenvolvimento

### Comandos Disponíveis

```bash
npm run dev     # Inicia o servidor de desenvolvimento
npm run start   # Alias para dev
```

### Adicionando Novos Aplicativos

1. Navegue até a categoria apropriada em `docs/apps/`
2. Crie ou edite o arquivo `.md` da categoria
3. Siga o padrão de documentação estabelecido
4. Teste localmente com `npm run dev`

### Padrões de Documentação

Cada aplicativo deve incluir:

- **Descrição**: O que o aplicativo faz
- **Características**: Lista de funcionalidades principais
- **Instalação**: Comandos para diferentes distribuições
- **Configuração**: Dicas de configuração (opcional)
- **Screenshots**: Imagens do aplicativo (opcional)

## Contribuindo

1. Faça um fork do projeto
2. Crie uma branch para sua feature (`git checkout -b feature/nova-feature`)
3. Commit suas mudanças (`git commit -am 'Adiciona nova feature'`)
4. Push para a branch (`git push origin feature/nova-feature`)
5. Abra um Pull Request

### Diretrizes de Contribuição

- Mantenha a documentação clara e objetiva
- Teste os comandos de instalação antes de documentar
- Siga o padrão de formatação estabelecido

## 📝 Licença

Este projeto está licenciado sob a licença MIT - veja o arquivo [LICENSE](LICENSE) para detalhes.

## 🔗 Links Úteis

- 📖 [Documentação do Docsify](https://docsify.js.org/)
- 💬 [Grupo da Comunidade](https://t.me/usandoolinux)

---

*Feito com ❤️ pela comunidade Usando Linux*