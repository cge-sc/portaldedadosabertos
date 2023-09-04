---
description: >-
  Define quais os passos e como criar um novo usuário no Portal de Dados
  Abertos.
---

# 👨🏭 Criação de Usuário

O Portal de Dados Abertos possibilita a criação de usuários de forma independente, por qualquer pessoa que deseje. Entretanto a funcionalidade foi desabilitada porque no passado essa funcionalidade foi usada por pessoas para realizar pichação.&#x20;

O método para criação de usuários novos é por meio de terminal, usando o seguinte comando abaixo:

```sh
curl -X POST --insecure -H "Content-Type: multipart/form-data"  -H "Authorization: token-do-administrador"  -F "name=Fulano da Silva" -F "email=email_do_fulano@orgao.sc.gov.br" -F "fullname=Fulano da Silva" -F "password=SENHA" https://dados.sc.gov.br/api/3/action/user_create
```
