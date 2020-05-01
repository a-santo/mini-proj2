# Tarefa 3.2: Mini-projeto - desenvolvimento do front-end
Tarefa 3.2 da unidade curricular Programação Web Avançada ano letivo 2019-2020. 

**Objetivo**: criar o front-end para duas novas entidades da API  http://fcawebbook.herokuapp.com/:
- Voluntários
- Membros do Comité

**Notas**
- Autênticação foi desativada propositadamente
- Como os end-points para as novas entidades não existem na API, optei por criar variáveis com entradas-exemplo para ambas as entidades. Todos com dados gerados aleatoriamente.
- O código para interagir com as end-points está comentado nos respetivos ficheiros .js (committee.js e volunteers.js)

**Voluntários**:
```json
[
    {
        "idVolunteer": 1,
        "nome": "Sofia Fernandes Cardoso",
        "telefone": "21 222 523 4360",
        "foto": "http://xxx.pt"
    },
    {
        "idVolunteer": 2,
        "nome": "Eduarda Rocha Pinto",
        "telefone": "21 265 261 2913",
        "foto": "http://xxx.pt"
    },
    {
        "idVolunteer": 3,
        "nome": "André Cavalcanti Gomes",
        "telefone": "21 253 987 6160",
        "foto": "http://xxx.pt"
    },
    {
        "idVolunteer": 4,
        "nome": "Carla Azevedo Oliveira",
        "telefone": "21 291 733 9480",
        "foto": "http://xxx.pt"
    },
    {
        "idVolunteer": 5,
        "nome": "Guilherme Castro Silva",
        "telefone": "21 215 388 4505",
        "foto": "http://xxx.pt"
    }
]
```
**Membros do comité**:
```json
[
    {
        "idMember": 1,
        "nome": "Victor Barros Dias",
        "email": "VictorBarrosDias@jourrapide.com",
        "telefone": "21 258 782 8541",
        "foto": "http://xxx.pt",
        "instituicao": "Universidade Aberta",
        "profissao": "Personnel clerk"
    },
    {
        "idMember": 2,
        "nome": "Melissa Pereira Silva",
        "email": "MelissaPereiraSilva@dayrep.com",
        "telefone": "21 227 519 8683",
        "foto": "http://xxx.pt",
        "instituicao": "Universidade da Beira Interior",
        "profissao": "Mail processor"
    },
    {
        "idMember": 3,
        "nome": "Livia Oliveira Fernandes",
        "email": "LiviaOliveiraFernandes@jourrapide.com",
        "telefone": "21 219 398 3188",
        "foto": "http://xxx.pt",
        "instituicao": "Universidade Nova",
        "profissao": "Travel guide"
    },
    {
        "idMember": 4,
        "nome": "Emily Rocha Pinto",
        "email": "EmilyRochaPinto@dayrep.com",
        "telefone": "21 271 636 3675",
        "foto": "http://xxx.pt",
        "instituicao": "Universidade Aberta",
        "profissao": "Radiation protection technician"
    },
    {
        "idMember": 5,
        "nome": "Rodrigo Silva Correia",
        "email": "RodrigoSilvaCorreia@dayrep.com",
        "telefone": "21 253 347 1383",
        "foto": "http://xxx.pt",
        "instituicao": "Universidade do Algarve",
        "profissao": "Natural sciences manager"
    }
]
```

Elaborado por: André Santo

Professor: Ricardo Baptista