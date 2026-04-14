# Sistema Acadêmico — Lista de Alunos

Aplicação React com Vite para gerenciamento de lista de alunos.

## Estrutura do Projeto

```
lista-alunos/
├── index.html
├── package.json
├── vite.config.js
└── src/
    ├── main.jsx              ← Entrada da aplicação
    ├── App.jsx               ← Componente principal (useState + useEffect)
    ├── index.css             ← Estilos globais
    ├── assets/
    │   └── educacao.svg      ← Imagem de educação
    └── components/
        ├── StatusBar.jsx     ← Barra de status com props
        ├── Footer.jsx        ← Rodapé com nome e ano
        ├── AlunoCard.jsx     ← Card de cada aluno (usado no .map())
        └── AlunoForm.jsx     ← Formulário para adicionar aluno
```

## Como executar

Acesse a pasta pelo terminal ou gitbash cd vite-project caso necessário
npm install
npm run dev
```

Acesse: http://localhost:5173

## Requisitos atendidos

| Requisito       | Implementação                                          |
|-----------------|--------------------------------------------------------|
| StatusBar       | `<StatusBar mensagem="Sistema Acadêmico" />`           |
| Footer          | Nome do aluno + ano via props                          |
| Imagem          | SVG de educação em `src/assets/educacao.svg`           |
| useState        | Estado `alunos` com `nome` e `curso`                   |
| map             | `alunos.map(aluno => <AlunoCard ... />)` em App.jsx    |
| useEffect       | Console ao montar e ao atualizar a lista               |
| Interação       | Botão "Adicionar Aluno" abre formulário                |
| Organização     | Componentes separados em `src/components/`             |
