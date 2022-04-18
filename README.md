# testes_spring

* Docker para criação de imagens e containers 
* Utilizando Java com Spring Boot.

## :hammer: O que foi visto

- `Proposta 1`: Deploy de aplicações Java com Spring
- `Proposta 2`: Ambiente Cloud
- `Proposta 3`: Criar Dockerfile no diretório raiz da aplicação

# Notas
- [x] Profiles 
> O @Profile indica ao Spring que determinada classe deve ser carregada apenas quando determinados profiles estiverem ativos.
- Dspring.profiles.active posibilita  alterar o profile ativo da aplicação por meio do parâmetro
- A anotação _@SpringBootTest_ deve ser utilizada nas classes de testes automatizados para que o Spring inicialize o servidor e disponibilize os beans da aplicação.
- Não esquecer de utilizar a anotação @DataJpaTest ao testar a interface Repository 
- @AutoConfigureTestDatabase(replace = AutoConfigureTestDatabase.Replace.NONE) - Para a escolha do banco de dados de teste automatizados
- Para escolher o profile especifico para os teste usar @ActiveProfiles
- @AutoConfigureMockMvc para injetar o `MockMvc`


