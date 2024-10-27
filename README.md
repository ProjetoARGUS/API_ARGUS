# API ARGUS: Gerenciamento de Condomínios
---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

Este repositório contém o código fonte da API RESTful para o backend da aplicação ARGUS, um sistema de gerenciamento de condomínios desenvolvido como projeto de conclusão de curso do programa START.

### Funcionalidades:

- Gerenciamento de Usuários: Cadastro, autenticação, atualização de dados, gerenciamento de permissões
- Gerenciamento de Condomínios: Cadastro, atualização, exclusão de dados
- Comunicação: Envio de comunicados, gerenciamento de mensagens, notificações
- Reservas: Realização de reservas de espaços comuns, aprovação e controle de reservas
- Ocorrências: Registro de ocorrências no condomínio, acompanhamento de status
- Votações: Criação de sessões de votação, registro de votos, visualização de resultados
- Gerenciamento de Áreas Comuns: Cadastro, atualização e exclusão de áreas comuns.

### Tecnologias:

- Spring Boot: Framework Java para desenvolvimento de aplicações web.

- Spring Data JPA: Framework para acesso a bancos de dados relacionais.

- Spring Security: Framework para segurança de aplicações web.

- JWT (JSON Web Token): Protocolo para autenticação e autorização

- AMQP (Advanced Message Queuing Protocol): Protocolo para comunicação assíncrona, com suporte a RabbitMQ.

- Java 17: Linguagem de programação Java, versão 17.

## Documentação:

A documentação da API está disponível no nosso Notion: [Notion da ARGUS](https://www.notion.so/ARGUS-Memorial-de-Desenvolvimento-1135144534ed804b81bcf1912b0613e7?pvs=4)


### Como Executar:

### Pré-requisitos:

- Ter o Java 17 instalado.
- Ter o Maven instalado.
- Ter um banco de dados relacional configurado.

### Clone este repositório:

          
    git clone https://github.com/seu-usuario/argus.git

        

Acesse o diretório do projeto:

```
cd argus
```


Configure o arquivo application.properties com as credenciais do banco de dados.

Execute o comando:

```
mvn spring-boot:run
```

Para iniciar a API.

-------------------------------------------------------------------------------------------------------------------------

### Como Contribuir

Agradecemos o seu interesse em contribuir com o projeto ARGUS! Se você deseja participar do desenvolvimento, siga os passos abaixo:

1. Fork do Projeto:

    Acesse o repositório do projeto no GitHub: [API-PROEJTO-ARGUS](https://github.com/ProjetoARGUS/API_ARGUS/).

    Clique no botão "Fork" no canto superior direito da página.

    Agora você possui uma cópia do repositório em sua própria conta do GitHub.

2. Clone do Projeto:

    Acesse o repositório do projeto em sua própria conta do GitHub.

    Clique no botão "Code" e copie a URL do repositório.

    Abra seu terminal e execute o comando:
   
```
    git clone [[URL do repositório]](https://github.com/ProjetoARGUS/API_ARGUS/)
```

Isso criará uma cópia local do projeto em seu computador.

4. Crie uma Nova Branch:

    Entre no diretório do projeto:

```
    cd [nome do diretório do projeto]
```

Crie uma nova branch para suas alterações:

```
git checkout -b [nome da branch]
```
    

Por exemplo, se você deseja adicionar um novo recurso, nomeie a branch como "feature-novo-recurso".

4. Faça o Commit de Mudanças:

    Edite os arquivos do projeto e faça as suas alterações.

    Adicione as alterações ao staging area:

```
    git add [nome dos arquivos alterados]
```

Ou então faça dessa forma para colocar todo os arquivos modificados na sessão de staged:

```
    git add .
```

Faça um commit das alterações:

```
git commit -m "[descrição concisa das suas alterações]"
```

   

5. Crie um Pull Request:

    Acesse o repositório do projeto em sua própria conta do GitHub.

    Vá até a branch onde você fez as alterações.

    Clique no botão "New pull request".

    Compare sua branch com a branch "main" do repositório original.

    Insira uma descrição detalhada de suas alterações no pull request.

    Clique em "Create pull request".

### Observações:

1. Revise seu código antes de enviar um pull request: Verifique se as alterações estão funcionando corretamente e se seguem os padrões de codificação do projeto.
2. Siga as diretrizes de contribuição: Se houver diretrizes específicas para o projeto, siga-as cuidadosamente.
3. Seja paciente: O processo de revisão de pull requests pode levar algum tempo.

---------------------------------------------------------------------------------------------------------------------------------------------------------------------------


Agradecemos a sua contribuição! 🎉

### Licença:

[GNU General Public License v3.0](./LICENSE.md)

Equipe de Desenvolvimento:

- Ailton Francisco da Silva Neto
- Breno do nascimento santos 
- Derick Germano de Oliveira
- Francisco Macedo de Santiago Neto
- Luan carlos wanderley da silva 
- Ronaldo Rodrigues de Moura Júnior

---------------------------------------------------------------------------

### Agradecimentos:

Agradecemos ao programa START pela oportunidade de desenvolver este projeto.
