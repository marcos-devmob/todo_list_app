# Todo List App

Um aplicativo de lista de tarefas feito em **Flutter**, permitindo adicionar, remover e gerenciar tarefas de forma simples.

## Funcionalidades

- Adicionar tarefas com título e data/hora.
- Remover tarefas individualmente ou todas de uma vez.
- Desfazer exclusão de tarefas.
- Persistência de dados local usando **Shared Preferences**.
- Interface amigável e responsiva.

## Screenshots

![Tela Principal](![Home](https://github.com/user-attachments/assets/d7dea54f-874d-45f0-9d53-be268faf1c43)

![Botão de Delete](![Delete](https://github.com/user-attachments/assets/62652873-29f9-4000-bb6e-8e8abcd97ea0)

![Limpar tudo](![LimparTudo](https://github.com/user-attachments/assets/7c14864b-4216-4aea-a351-08c62a38a547)

![Tela de Tarefas](![TarefasAdicionadas](https://github.com/user-attachments/assets/af8e4549-9549-46c7-a01b-f2b6ee7a3d5a)


## Tecnologias e Pacotes Utilizados

- [Flutter](https://flutter.dev/)
- [Dart](https://dart.dev/)
- [Shared Preferences](https://pub.dev/packages/shared_preferences)
- [Flutter Slidable](https://pub.dev/packages/flutter_slidable)
- [Intl](https://pub.dev/packages/intl)


## Como Executar

1. Clone este repositório:
   ```bash
   git clone https://github.com/marcos-devmob/todo_list_app.git
   ```
2. Entre na pasta do projeto:
   ```bash
   cd todo_list_app
   ```
3. Instale as dependências:
   ```bash
   flutter pub get
   ```
4. Rode o aplicativo:
   ```bash
   flutter run
   ```
Certifique-se de ter o Flutter e o Android Studio configurados corretamente no seu ambiente de desenvolvimento.

---

## Como Contribuir

1. Fork este repositório.

2. Crie uma branch para sua feature: 
   ```bash
   git checkout -b minha-feature
3. Faça as alterações desejadas e commit:
    ```bash
    git commit -m "Descrição da feature"
4. Envie para o seu fork:
   ```bash
   git push origin minha-feature
5. Abra um Pull Request no repositório original.

---
   
## Estrutura do Projeto

- `lib/` – código fonte do app
  - `models/` – modelos de dados
  - `repositories/` – lógica de armazenamento
  - `pages/` – telas do app
  - `widgets/` – componentes reutilizáveis

---

MIT License

Copyright (c) 2025 Marcos Aurélio

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.

