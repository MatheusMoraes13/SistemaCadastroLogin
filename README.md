# Sistema de Cadastro e Login

## Descrição
Este projeto é um sistema de cadastro e login desenvolvido em C, utilizando a biblioteca GTK3 para a interface gráfica e a ferramenta Glade para facilitar a construção da UI.

## Tecnologias Utilizadas
- **C**: Linguagem de programação principal.
- **GTK3**: Biblioteca para interface gráfica.
- **Glade**: Ferramenta para construção da UI.
- **SQLlite3**: Ferramenta de banco de dados utilizada para armazenamento das informações dos logins.

## Funcionalidades
- Cadastro de novos logins.
- Atualização de um login já cadastrado
- Apagar um login cadastrado anteriormente
- Login de usuários cadastrados.
- Interface gráfica amigável.
- Armazenamento  nome/email/senha.

## Estrutura do Projeto
```
/SistemaCadastroLogin
├── src
│   ├── main.c
│   ├── interface.c
│   ├── database.db3
│   ├── UI.glade
|   ├── icons/
|   |   ├── imagens utilizadas
├── lib
|  ├── gdk-pixbuf-2.0
├── share
├── README.md
```

## Requisitos
- O programa pode ser executado em qualquer máquina.
   - É necessario que o usuário tenha as DLLs devidamente adicionadas em seu diretório


## Licença
Este projeto é distribuído sob a licença MIT.
