# App

Find a Street Market Api

## RFs (Requisitos Funcionais)

- [ ] Deve ser possível se cadastrar
- [ ] Deve ser possível se autenticar
- [ ] Deve ser possível obter o perfil de um usuário logado
- [ ] Deve ser possível o usuário realizar check-in em uma academia
- [ ] Deve ser possível favoritar as feiras livres
- [ ] Deve ser possível o usuário visualizar detalhes de uma feira livre
- [ ] Deve ser possível o usuário buscar feiras livre próximas (1OKm)
- [ ] Deve ser possível buscar barracas
- [ ] Deve ser possível seguir novidades das feiras livres
- [ ] Deve ser possível seguir novidades das barracas

# RNs (Regras de Negócio)

- [ ] Não deve ser possível cadastrar um usuário com email já existente
- [ ] A feira livre só pode ser cadastrada por administradores

## RNFs (Requisitos Não Funcionais)

- [ ] A senha do usuário precisa ser criptografada
- [ ] O dados da aplicação precisam estar persistido em um banco PostgreSQL
- [ ] Todas listas de dados precisam estar paginadas com 20 items por página
- [ ] O usuário deve ser identificado por um JWT (JSON Web Token)