# ToDoList — gerenciador de tarefas em JavaScript

Lista de tarefas feita com **HTML, CSS e JavaScript puro**. As tarefas ficam salvas no navegador (`localStorage`), então não somem quando a página é recarregada.

![HTML5](https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=black)

## Funcionalidades

- Adicionar, **editar**, concluir e remover tarefas.
- Até 10 tarefas, com no máximo 70 caracteres cada (tem contador de caracteres).
- **Arrastar e soltar** pra reordenar as tarefas.
- Contadores de tarefas: total, pendentes e feitas.
- Confirmação antes de excluir e botão **desfazer** em uma notificação (toast).
- Opção de limpar todas as tarefas concluídas de uma vez.
- Tela própria pra quando a lista está vazia, layout responsivo e cuidados de acessibilidade (`aria-live`, rótulos para leitores de tela).

## Como executar

Não precisa instalar nada. É só abrir o `testeToDoList/index.html` no navegador, ou usar a extensão **Live Server** no VS Code.

## Estrutura

```
testeToDoList/
├── index.html   # estrutura da aplicação
├── style.css    # estilos e responsividade
└── script.js    # lógica: estado, persistência, drag and drop, modais e toasts
```

## Autor

**Jorge Gabriel**, estudante de Análise e Desenvolvimento de Sistemas na UNIFOR.
[GitHub](https://github.com/Eujorgyn) · jorgegabrielpinheirofrutuoso@gmail.com
