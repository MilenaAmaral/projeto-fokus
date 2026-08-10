# 🧘 Fokus

Aplicativo web de temporizador Pomodoro, feito para ajudar a organizar sessões de foco, pausas curtas e pausas longas, com uma lista de tarefas integrada.

> Projeto fictício e sem fins comerciais. Imagens geradas por IA no Adobe Firefly.

## ✨ Funcionalidades

- **Temporizador Pomodoro** com três contextos: Foco (25 min), Descanso curto (5 min) e Descanso longo (15 min).
- **Ciclo automático**: ao terminar uma sessão de foco, o app troca sozinho para o descanso (curto, ou longo a cada 4ª sessão) e, ao fim do descanso, volta para o foco automaticamente.
- **Lista de tarefas**: adicionar, editar, marcar como concluída (automaticamente ao finalizar um foco com a tarefa selecionada) e remover tarefas concluídas ou todas de uma vez.
- **Persistência local**: as tarefas ficam salvas no `localStorage` do navegador, mesmo após fechar a página.
- **Música de fundo** opcional, para acompanhar o foco.
- **Layout responsivo**, adaptado para desktop, tablet e celular.

## 🗂️ Estrutura do projeto

```
├── index.html        # Estrutura da página
├── style.css         # Estilos visuais
├── script.js         # Lógica do temporizador
├── script-crud.js    # Lógica da lista de tarefas (criar, ler, editar, remover)
├── imagens/          # Ícones e ilustrações
└── sons/              # Efeitos sonoros e música de fundo
```

## 🚀 Como usar

1. Clone ou baixe este repositório.
2. Abra o arquivo `index.html` em um navegador (ou sirva a pasta com um servidor local, como a extensão *Live Server* do VS Code).
3. Escolha um contexto (Foco, Descanso curto ou Descanso longo) e clique em **Começar**.
4. Adicione tarefas na lista, selecione a tarefa em que está trabalhando e ela será marcada como concluída automaticamente ao final de uma sessão de foco.

## 🛠️ Tecnologias

- HTML5
- CSS3 (variáveis CSS, media queries)
- JavaScript puro (Vanilla JS), sem frameworks ou build tools
- [Meyer Reset CSS](https://meyerweb.com/eric/tools/css/reset/) via CDN
- Fontes Montserrat, Prata e Unbounded via Google Fonts

## 👩‍💻 Autoria

Desenvolvido por **Milena Amaral**, baseado nos estudos da Alura.
