# App

GymPass app.

## RFs (Requisitos funcionais)

- [ ] Possível se cadastrar;
- [ ] Possível se autenticar;
- [ ] Possível obter o perfil de um usuário logado;
- [ ] Possível obter o número de check-ins realizados pelo usuário logado;
- [ ] Possível o usuário obter o seu histórico de check-ins;
- [ ] Possível o usuário buscar academias próximas;
- [ ] Possível o usuário buscar academias pelo nome;
- [ ] Possível o usuário realizar check-in em uma academia;
- [ ] Possível validar o check-in de um usuário;
- [ ] Possível cadastrar uma academia;

## RNs (Regras de negócio)

- [ ] O usuário não deve poder se cadastrar com um e-mail duplicado;
- [ ] O usuário não pode fazer 2 check-ins no mesmo dia;
- [ ] O usuário não pode fazer check-in se não estiver perto (100m) da academia;
- [ ] O check-in só pode ser validado até 20 minutos após ser criado;
- [ ] O check-in só pode ser validado por administradores;
- [ ] A academia só pode ser cadastrada por administradores;

## RNFs (Requisitos não-funcionais)

- [ ] A senha do usuário precisa estar criptografada;
- [ ] Os dados da aplicação precisam estar persistidos em um banco PostgreSQL;
- [ ] Todas listas de dados precisam estar paginadas com 20 itens por página;
- [ ] O usuário deve ser identificado por um JWT (JSON Web Token);