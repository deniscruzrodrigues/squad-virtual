# Squad Virtual

Um projeto de gerenciamento de squad virtual corporativo para coordenação de agentes de IA e delegação inteligente de tarefas.

## Sobre o Projeto

Squad Virtual é um sistema que facilita a organização e delegação de tarefas dentro de um ambiente corporativo virtual, permitindo que múltiplos agentes de IA trabalhem em conjunto de forma coordenada.

## Tecnologias

- Node.js
- Skills Framework
- JSON para configuração de tarefas

## Instalação

1. Clone o repositório:
```bash
git clone https://github.com/deniscruzrodrigues/squad-virtual.git
cd squad-virtual
```

2. Instale as dependências:
```bash
npm install
```

## Comandos Disponíveis

### Listar Skills Disponíveis
```bash
npx skills add ./ --list
```

### Adicionar Skills do Projeto
```bash
npx skills add ./
```

### Adicionar uma Skill Específica
```bash
npx skills add ./ --skill <nome-da-skill>
```

## Estrutura do Projeto

- `virtual-task-delegator/` - Skill para delegação de tarefas
- `squad-tech-lead/` - Skill para liderança técnica
- `squad-developer-fullstack/` - Skill para desenvolvimento full-stack
- `squad-data-engineer/` - Skill para engenharia de dados
- `evals/` - Testes de validação das skills

## Como Usar

1. **Delegação de Tarefas**: Use o task delegator para decompor objetivos de alto nível em tarefas específicas para cada agente.

2. **Validação Técnica**: O tech lead valida requisitos, DoR (Definition of Ready) e DoD (Definition of Done).

3. **Desenvolvimento**: Desenvolvedores fullstack implementam funcionalidades em Java e Angular.

4. **Dados**: Engenheiros de dados gerenciam SQL, NoSQL e análises.

## Contribuições

Este projeto nasceu de um fork e foi customizado para atender às necessidades específicas do squad virtual corporativo.

## Licença

MIT

---

Desenvolvido por [Denis Cruz Rodrigues](https://github.com/deniscruzrodrigues)