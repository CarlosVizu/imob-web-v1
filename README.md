#Premissas do projeto:

Será um projeto criado a partir do **Spring Framework**:

- Banco de Dados Relacional (Definir entre mySQL, PostgreSQL, MongoDB)
- Spring Data JPA
- Spring Security
- Spring MVC - Desenvolvimento de aplicativos web (Model-View-Controller)
- RESTful API
- Swagger

Front End 
- à definir 

Objetos serão enviados ao front-end com o modelo JSON para melhor escabilidade. 



Entidade: Imóvel
Atributos:
Atributos:
ID: identificador único do imóvel.
Tipo de imóvel: o tipo de imóvel, como casa, apartamento, terreno, sala comercial, etc.
Título: um título descritivo para o imóvel.
Descrição: uma descrição detalhada do imóvel, incluindo características, comodidades, localização, etc.
Endereço:
Logradouro: nome da rua/avenida do imóvel.
Número: número do imóvel.
Complemento: informações adicionais sobre o endereço.
Bairro: bairro onde o imóvel está localizado.
Cidade: cidade onde o imóvel está localizado.
Estado: estado onde o imóvel está localizado.
CEP: Código de Endereçamento Postal do imóvel.
Área total: a área total do imóvel em metros quadrados.
Área construída: a área construída do imóvel em metros quadrados.
Número de quartos: o número de quartos no imóvel.
Número de suítes: o número de suítes no imóvel.
Número de banheiros: o número de banheiros no imóvel.
Vagas de estacionamento: o número de vagas de estacionamento disponíveis.
Preço: o preço de venda ou aluguel do imóvel.
Status: o status atual do imóvel, como disponível, alugado, vendido, em negociação, etc.
Data de criação: a data de criação do registro do imóvel.
Data de atualização: a data mais recente em que o registro do imóvel foi atualizado.


Entidade: Cliente
Atributos:
ID: identificador único do cliente.
Nome: o nome completo do cliente.
Email: o endereço de e-mail do cliente.
Telefone: o número de telefone do cliente.
Data de nascimento: a data de nascimento do cliente.
Gênero: o gênero do cliente.
Nacionalidade: a nacionalidade do cliente.
Documento de identificação:
Tipo: o tipo de documento de identificação, como RG, CPF, passaporte, etc.
Número: o número do documento de identificação.
Órgão emissor: o órgão emissor do documento.
Data de emissão: a data de emissão do documento.
Endereço:
Logradouro: nome da rua ou avenida.
Número: número do imóvel.
Complemento: informações adicionais do endereço, como bloco, apartamento, etc.
Bairro: nome do bairro.
Cidade: nome da cidade.
Estado: estado onde está localizado o cliente.
CEP: código de endereçamento postal.
Data de criação: a data de criação do registro do cliente.
Data de atualização: a data mais recente em que o registro do cliente foi atualizado.


Entidade: Contrato
Atributos:
ID: identificador único do contrato.
Imóvel: uma referência ao imóvel associado a este contrato.
Cliente: uma referência ao cliente associado a este contrato.
Tipo de contrato: o tipo de contrato, como aluguel residencial, aluguel comercial, venda, etc.
Data de início: a data de início do contrato.
Data de término: a data de término do contrato (pode ser nula para contratos em andamento).
Valor do contrato: o valor total do contrato.
Condições especiais: condições especiais do contrato, se aplicável.
Forma de pagamento: a forma de pagamento acordada para o contrato, como boleto, cartão de crédito etc
Status: o status do contrato, como ativo, encerrado, etc.
Data de criação: a data de criação do registro do contrato.
Data de atualização: a data mais recente em que o registro do contrato foi atualizado.




Entidade: Corretor
Atributos:
ID: identificador único do corretor.
Nome: o nome completo do corretor.
Email: o endereço de e-mail do corretor.
Telefone: o número de telefone do corretor.
Data de nascimento: a data de nascimento do corretor.
Gênero: o gênero do corretor.
Registro profissional: o número de registro profissional do corretor.
Endereço:
Logradouro: nome da rua ou avenida.
Número: número do imóvel.
Complemento: informações adicionais do endereço, como bloco, apartamento, etc.
Bairro: nome do bairro.
Cidade: nome da cidade.
Estado: estado onde está localizado o corretor.
CEP: código de endereçamento postal.
Data de criação: a data de criação do registro do corretor.
Data de atualização: a data mais recente em que o registro do corretor foi atualizado.

Entidade: Visitante
Atributos:
ID: identificador único do visitante.
Nome: o nome completo do visitante.
Email: o endereço de e-mail do visitante.
Telefone: o número de telefone do visitante.
Data de visita: a data da visita ao imóvel.
Observações: quaisquer observações ou comentários sobre a visita.
Imóvel visitado: uma referência ao imóvel visitado.
Data de criação: a data de criação do registro do visitante.
Data de atualização: a data mais recente em que o registro do visitante foi atualizado.

Entidade: Proprietário
Atributos:
ID: identificador único do proprietário.
Nome: o nome completo do proprietário.
Email: o endereço de e-mail do proprietário.
Telefone: o número de telefone do proprietário.
Endereço:
Logradouro: nome da rua ou avenida.
Número: número do imóvel.
Complemento: informações adicionais do endereço, como bloco, apartamento, etc.
Bairro: nome do bairro.
Cidade: nome da cidade.
Estado: estado onde está localizado o proprietário.
CEP: código de endereçamento postal.
Imóveis de propriedade: uma lista de imóveis de propriedade do proprietário.
Data de criação: a data de criação do registro do proprietário.
Data de atualização: a data mais recente em que o registro do proprietário foi atualizado.


