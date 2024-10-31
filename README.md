# **AppSistemaCadastro (Sistema de cadastro)**

> Um aplicativo Android desenvolvido para o usuário poder cadastra e editar seus usuários (este foi o unico trabalho que não deu certo).

## Descrição
O **AppSistemaCadastro** permite ao usuário editar e cadastrar novos usuários que serão salvos no Database.

## Funcionalidades
- [x] Entrada de dados de consumo
- [x] Cálculo e exibição de estatísticas de consumo
- [x] Gráficos interativos para visualização dos dados
- [x] Interface intuitiva e amigável
- [ ] Suporte para diferentes tipos de recursos (planejado para futuras versões)

## Tecnologias Utilizadas
- [x] **Android Studio** (versão recomendada: Bumblebee | 2021.1.1)
- [x] **Java** para desenvolvimento
- [x] **ConstraintLayout** para interface responsiva
- [x] **TextView**, **EditText** para entrada e exibição de dados

## Como Rodar o Projeto
Siga os passos abaixo para rodar o projeto localmente:

1. Clone este repositório:
   ```bash
   https://github.com/Hacker19991/Sistema-de-cadastro
   
2. Abra o projeto no Android Studio.
   
3. Compile e execute o projeto em um emulador ou dispositivo físico.

## Estrutura do Projeto

```
── app
   ├── src
   │   ├── main
   │   │   ├── java/com/example/appconsumo
   │   │   │   ├── ListarPessoasActivity.java # Atividade onde todos os cadastrados serão listados
   │   │   │   ├── MainActivity.java # Atividade onde ocorrera o processo de salvamento com o Database
   │   │   │   ├── Pessoa.java # Atividade onde mostrara os dados salvos do usuário listado
   │   │   │   ├── PessoaDB.java # Atividade onde irá salvar e manter os dados do usuário contidos no DataBase 
   │   │   ├── res
   │   │   │   ├── layout
   │   │   │   │   ├── activity_main_pessoa_activity.xml # Layout onde mostrara os dados salvos 
   │   │   │   │   ├── activity_main.xml # Layout onde os dados serão salvos com sucesso 
   │   │   │   ├── menu
   │   │   │   │   ├── menu_contexto.xml # Layout onde mostrata os dados de qual usuário está na lista
   │   │   │   │   ├── menu_principal.xml # Layout onde possa ser acessado todo os trabalho
   │   │   │   └── values
   │   │   │       ├── strings.xml # Strings usadas no app
   │   │   │       ├── colors.xml # Cores definidas no projeto
   └── build.gradle # Configuração do Gradle
```

## Design e Prototipage
A interface do app foi criada usando ConstraintLayout no modelo Design para ser mais simples e facil de se usar e para ser mais compacto ao android e mais simples e pratico assim podendo se acostumar com o tempo.

## Telas do Aplicativo 

> Tela Principal

![image](https://github.com/user-attachments/assets/8f01cab6-ee2b-4339-ac30-bb8c1e8fd637)

Uma tela simples, 3 EditText para, Nome do usuário, CPF e o telefone do usuário, um botão para processar e salvar os dados no datavase(irei colocar apenas essa tela no README, pois as outras não estão funcionando como devem funcionar devido a esse trabalho ser um trabalho falho, peço desculpas quem teve que ler até aqui).

## Desenvolvedores
**Gabriel Henrique** - Desenvolvedor - [GitHub](https://github.com/Hacker19991).

## Licença
Este projeto está licenciado sob os termos da licença MIT. Para mais detalhes, veja o arquivo
[LICENSE](LICENSE).
