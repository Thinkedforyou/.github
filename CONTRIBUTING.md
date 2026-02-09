# 🤝 Guia de Contribuição

Primeiramente, obrigado por considerar contribuir com a Thinked! 💜

## 📋 Índice

- [Código de Conduta](#código-de-conduta)
- [Como Posso Contribuir?](#como-posso-contribuir)
- [Configuração do Ambiente](#configuração-do-ambiente)
- [Fluxo de Desenvolvimento](#fluxo-de-desenvolvimento)
- [Padrões de Código](#padrões-de-código)
- [Commits e Pull Requests](#commits-e-pull-requests)

## 📜 Código de Conduta

Este projeto adota o [Código de Conduta](CODE_OF_CONDUCT.md). Ao participar, espera-se que você siga este código.

## 🚀 Como Posso Contribuir?

### 🐛 Reportando Bugs

- Use o template de Bug Report
- Descreva o bug claramente
- Inclua passos para reproduzir
- Adicione screenshots se possível

### 💡 Sugerindo Features

- Use o template de Feature Request
- Explique o problema que a feature resolve
- Descreva a solução ideal

### 💻 Contribuindo com Código

1. Procure issues com a label `good first issue` para começar
2. Comente na issue que você quer trabalhar nela
3. Siga o fluxo de desenvolvimento abaixo

## ⚙️ Configuração do Ambiente

```bash
# Clone o repositório
git clone https://github.com/Thinkedforyou/<repositorio>.git
cd <repositorio>

# Instale as dependências
npm install

# Configure as variáveis de ambiente
cp .env.example .env

# Rode os testes
npm test

# Inicie o servidor de desenvolvimento
npm run dev
```

## 🔄 Fluxo de Desenvolvimento

1. **Fork** o repositório
2. **Clone** seu fork localmente
3. **Crie uma branch** para sua feature/fix:
   ```bash
   git checkout -b feature/minha-feature
   # ou
   git checkout -b fix/meu-bugfix
   ```
4. **Faça suas mudanças** seguindo os padrões de código
5. **Commit** suas mudanças (veja padrão de commits abaixo)
6. **Push** para sua branch
7. **Abra um Pull Request**

## 📏 Padrões de Código

### Estilo

- Use TypeScript quando possível
- Siga o ESLint e Prettier configurados
- Mantenha funções pequenas e focadas
- Escreva comentários para código complexo
- Use nomes descritivos para variáveis e funções

### Testes

- Escreva testes para novas features
- Mantenha a cobertura de testes acima de 80%
- Use nomes descritivos para os testes

## 📝 Commits e Pull Requests

### Conventional Commits

Usamos [Conventional Commits](https://www.conventionalcommits.org/):

```
<tipo>[escopo opcional]: <descrição>

[corpo opcional]

[rodapé opcional]
```

**Tipos:**
- `feat`: Nova feature
- `fix`: Correção de bug
- `docs`: Documentação
- `style`: Formatação
- `refactor`: Refatoração
- `perf`: Performance
- `test`: Testes
- `chore`: Manutenção

**Exemplos:**
```
feat(auth): adiciona login com Google
fix(api): corrige timeout em requisições longas
docs: atualiza README com instruções de instalação
```

### Pull Requests

- Use o template de PR
- Vincule à issue relacionada
- Aguarde revisão antes de fazer merge
- Responda aos comentários de revisão

## 🏷️ Labels

| Label | Descrição |
|-------|-----------|
| `bug` | Algo não está funcionando |
| `enhancement` | Nova feature ou melhoria |
| `good first issue` | Boa para iniciantes |
| `help wanted` | Precisa de ajuda extra |
| `documentation` | Melhorias na documentação |
| `priority: high` | Prioridade alta |
| `priority: low` | Prioridade baixa |

## ❓ Dúvidas?

- Abra uma [Discussion](https://github.com/Thinkedforyou/discussions)
- Entre em contato: contato@thinked.com.br

---

**Obrigado por contribuir! 💜**
