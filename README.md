# 💻 [Nome do Módulo] - Projetos Práticos

**Projetos hands-on para consolidar o aprendizado do vaden-projects**

[![Dart](https://img.shields.io/badge/Dart-0175C2?style=flat&logo=dart&logoColor=white)](https://dart.dev)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

Este repositório contém todos os projetos práticos do **vaden-projects** da trilha [Dart Learning Hub](https://github.com/dart-learning-hub).

📚 **Para a teoria e explicações:** [Curriculum](https://github.com/dart-learning-hub/curriculum)

---

## 🎯 Sobre Este Repositório

Cada projeto aqui é desenhado para:
- ✅ Aplicar conceitos específicos do módulo
- ✅ Aumentar progressivamente em complexidade
- ✅ Fornecer experiência prática real
- ✅ Incluir testes automatizados para validação

---

## 📂 Projetos Disponíveis

### 🟢 Nível Básico

| Projeto | Descrição | Conceitos | Duração | Status |
|---------|-----------|-----------|---------|--------|
| [project-01-name](./project-01-name) | Descrição breve | conceito1, conceito2 | 2-3h | ✅ |
| [project-02-name](./project-02-name) | Descrição breve | conceito3, conceito4 | 3-4h | 🟡 |

### 🟡 Nível Intermediário

| Projeto | Descrição | Conceitos | Duração | Status |
|---------|-----------|-----------|---------|--------|
| [project-03-name](./project-03-name) | Descrição breve | conceito5, conceito6 | 4-6h | 🔴 |

### 🔴 Nível Avançado

| Projeto | Descrição | Conceitos | Duração | Status |
|---------|-----------|-----------|---------|--------|
| [project-04-name](./project-04-name) | Descrição breve | conceito7, conceito8 | 8-10h | 🔴 |

**Legenda:** ✅ Disponível | 🟡 Em desenvolvimento | 🔴 Planejado

---

## 🚀 Como Usar Este Repositório

### Pré-requisitos

- Dart SDK instalado ([instruções](https://dart.dev/get-dart))
- VS Code ou sua IDE preferida
- Ter concluído as lições teóricas do [Módulo X](https://github.com/dart-learning-hub/curriculum/tree/main/docs/module-X)

### Workflow Recomendado

1. **Clone o repositório**
   ```bash
   git clone https://github.com/dart-learning-hub/vaden-projects.git
   cd [repo-name]
   ```

2. **Escolha um projeto**
   ```bash
   cd project-01-name
   ```

3. **Leia o README do projeto**
   - Cada projeto tem instruções específicas
   - Entenda o problema antes de começar

4. **Comece pelo starter code**
   ```bash
   cd starter
   dart pub get
   ```

5. **Complete o desafio**
   - Implemente as funcionalidades solicitadas
   - Execute os testes frequentemente
   ```bash
   dart test
   ```

6. **Compare com a solução**
   - Somente após tentar por conta própria
   - Analise diferenças de abordagem
   ```bash
   cd ../solution
   ```

---

## 📁 Estrutura de Cada Projeto

```
project-name/
├── README.md              # Descrição, objetivos e instruções
├── starter/               # 🚀 Código inicial para você começar
│   ├── bin/
│   ├── lib/
│   ├── test/
│   ├── pubspec.yaml
│   └── README.md
├── solution/              # ✅ Solução completa (veja só depois!)
│   ├── bin/
│   ├── lib/
│   ├── test/
│   ├── pubspec.yaml
│   └── README.md
└── assets/                # Recursos adicionais (se necessário)
    ├── images/
    └── data/
```

---

## 🎓 Metodologia de Aprendizado

### Como Aproveitar ao Máximo

1. **Não pule projetos**: cada um ensina algo específico
2. **Tente primeiro, veja depois**: resista à tentação de olhar a solução imediatamente
3. **Use os testes**: eles guiam você para a solução correta
4. **Refatore seu código**: primeira versão funcionando ≠ melhor versão
5. **Compare abordagens**: sua solução vs. solução oficial

### Quando Consultar a Solução

✅ **Sim:**
- Após ter tentado genuinamente por 30+ minutos
- Quando completamente travado em um conceito específico
- Para comparar após ter sua própria solução funcionando

❌ **Não:**
- Como primeiro passo
- Sem tentar implementar primeiro
- Para copiar e colar diretamente

---

## 🧪 Executando os Testes

Cada projeto inclui testes automatizados.

```bash
# No diretório do projeto
cd project-name/starter

# Instalar dependências
dart pub get

# Executar todos os testes
dart test

# Executar testes específicos
dart test test/calculator_test.dart

# Executar com coverage
dart test --coverage=coverage
genhtml coverage/lcov.info -o coverage/html
```

---

## 🤝 Contribuindo

Quer adicionar um projeto ou melhorar um existente?

1. Fork este repositório
2. Crie uma branch (`git checkout -b feature/novo-projeto`)
3. Siga a estrutura padrão de projetos
4. Inclua starter code + solution + testes
5. Abra um Pull Request

Veja [CONTRIBUTING.md](./CONTRIBUTING.md) para detalhes.

---

## 💡 Dicas e Boas Práticas

### Para Iniciantes
- 📖 Leia a teoria no curriculum antes de começar
- 🐢 Não tenha pressa, qualidade > velocidade
- 🙋 Peça ajuda nas [Discussions](https://github.com/orgs/dart-learning-hub/discussions)

### Para Experientes
- 🚀 Desafio extra: implemente features além do solicitado
- 🧪 Aumente a cobertura de testes
- 📝 Documente seu código com dartdoc
- 🎨 Refatore usando padrões de design

---

## 🐛 Problemas e Suporte

Encontrou um bug ou erro no código?

1. Verifique se já existe uma [issue aberta](https://github.com/dart-learning-hub/[repo-name]/issues)
2. Se não, [crie uma nova issue](https://github.com/dart-learning-hub/[repo-name]/issues/new)
3. Para dúvidas gerais, use [Discussions](https://github.com/orgs/dart-learning-hub/discussions)

---

## 📚 Recursos Adicionais

- 📖 [Documentação do Módulo](https://github.com/dart-learning-hub/curriculum/tree/main/docs/module-X)
- 🎓 [Dart Documentation](https://dart.dev/guides)
- 💬 [Dart Learning Hub Discussions](https://github.com/orgs/dart-learning-hub/discussions)
- 🐦 [#DartLearningHub](https://twitter.com/hashtag/DartLearningHub) no Twitter

---

## 📄 Licença

Este projeto está sob a licença MIT. Veja [LICENSE](./LICENSE) para detalhes.

---

## 🎉 Conquistas

Compartilhe sua conclusão deste módulo!

```bash
# Depois de completar todos os projetos
echo "Completei o [Nome do Módulo] do Dart Learning Hub! 🎉" \
  | gh issue comment ISSUE_NUMBER --body-file -
```

---

**⭐ Se estes projetos te ajudaram, dê uma estrela no repositório!**

*Feito com ❤️ pela comunidade [Dart Learning Hub](https://github.com/dart-learning-hub)*
