# mongo

## Instalando atlas CLI
https://www.mongodb.com/pt-br/docs/atlas/cli/current/install-atlas-cli/

    atlas auth login

    atlas config init

## Trabalhando com projeto

### [create](https://www.mongodb.com/pt-br/docs/atlas/cli/current/command/atlas-projects-create/)

    atlas projects create <projectName>

### [list](https://www.mongodb.com/pt-br/docs/atlas/cli/current/command/atlas-projects-list/)

    atlas projects list

### [delete](https://www.mongodb.com/pt-br/docs/atlas/cli/current/command/atlas-projects-delete/)

    atlas projects delete <ID>

### [describe](https://www.mongodb.com/pt-br/docs/atlas/cli/current/command/atlas-projects-describe/)

    atlas projects describe <ID>

## Trabalhando com cluster

### [create](https://www.mongodb.com/pt-br/docs/atlas/cli/current/command/atlas-clusters-create/)

    atlas clusters create c-01

### Conectando ao cluster criado
- **_url_**: mongodb+srv://mongo-user-01:<db_password>@c-01.0jbgm.mongodb.net/?retryWrites=true&w=majority&appName=c-01