Usado para organização interna do grupo

| tela | responsavel |status|acesso|
|-----:|-----------|----------|---|
|Inicio|Isadora| feita|[telainicial](https://github.com/isadora-yasmim/projeto-integrado-es/tree/f11f4e9285fe66c742d8d2fc60cbbba2669f677b/telainicial)|
|Fatores de Risco|Gabriel|Feita|https://github.com/GGabrielRodrigues/ip-2024-01/tree/master/projeto-integrador-es/telasproj/Filtro-Dashboard-ACS|
|Registro|Felipe|feita|[tela](https://github.com/Coto-nete/ip-2024-01/tree/46047ba964bf086b3f7ae58b5a1b7790b49c8130/projeto-integrado-es/TelaInicio)|
|Login| Hugo |feita|(https://github.com/HugoPBorges/projeto-integrado-es)|
|Pop up validação|Isadora|feita|(https://github.com/isadora-yasmim/projeto-integrado-es/tree/main/popup%20%20validacao)|
|Pop up Validação confirmada|Isadora|feita|(https://github.com/isadora-yasmim/projeto-integrado-es/tree/main/popup%20valida%C3%A7%C3%A3o)|
|Esqueceu senha | Hugo |feita|(https://github.com/HugoPBorges/projeto-integrado-es)|
|Token |Hugo|feita|https://github.com/HugoPBorges/projeto-integrado-es|
|Redefinir senha| Hugo|feita|(https://github.com/HugoPBorges/projeto-integrado-es)|
|ACS HOME|Felipe|feita|https://github.com/Coto-nete/ip-2024-01/tree/main/projeto-integrado-es/tela%201|
|Cadastro/ACS |Rafael|feita|(https://github.com/RafaelFernandes1112/projeto-inetgrado-es/tree/main/tela1)|
|Cadastro/Paciente|Rafael|feita|(https://github.com/RafaelFernandes1112/projeto-inetgrado-es/tree/main/tela2)|
|Perfil|Isadora|feita|[buscarpaciente](https://github.com/isadora-yasmim/projeto-integrado-es/tree/f11f4e9285fe66c742d8d2fc60cbbba2669f677b/buscapacientes)|
|Perfil / Paciente| Gabriel |feita|https://github.com/GGabrielRodrigues/ip-2024-01/tree/master/projeto-integrador-es/telasproj/Perfil-Pacientes|
|Perfil usuario| Gabriel |feita|https://github.com/GabrielRodrigues/ip-2024-01/tree/master/projeto-integrador-es/telasproj/Perfil-Usu%C3%A1rio|
|Dashboard ACS|Felipe|feita|https://github.com/Coto-nete/ip-2024-01/tree/main/projeto-integrado-es/tela%202|
|Validação de Cadastro| Gabriel | feita | https://github.com/GGabrielRodrigues/ip-2024-01/tree/master/projeto-integrador-es/telasproj |
|Declaração de óbito| Rafael | feita |(https://github.com/RafaelFernandes1112/projeto-inetgrado-es/tree/main/tela3)|



tabelas 


acs - tipo
|nome|tipo|
|---:|----|
|cbo (primary key)|int| 
|cpf|varchar(11)|
|nome|varchar(40)|
|nomemae|varchar(40)|
|sexo|varchar(12)|
|telefone|varchar(13)|
|email|varchar(50)|
|ine|int|
|cns|varchar(15)|
|cnes|varchar(10)|



acs- objeto
|cpf|nome|nomemae|sexo|telefone|email|ine|cbo|cns|cnes|
|--:|----|-------|----|--------|-----|---|---|---|----|
|12345678900|joao|maria|masculino|62 99999999|joao@gmail.com|1234567890|123456|2143 1243 1243 123|1234567|1234567|



paciente- tipo
|nome|tipo|
|---:|----|
|cpf(primary key)|varchar(11)| 
|nome|varchar(40)|
|nomemae|varchar(40)|
|sexo|varchar(12)|
|datanascimento|varchar(8)|
|telefone|varchar(13)|
|email|varchar(50)|
|uf|varchar(2)|
|bairro|varchar(20)|
|cep|varchar(8)|
|municipio|varchar(15)|
|complemento|varchar(15)|



paciente- objeto
|cpf|nome|nomemae|sexo|datanascimento|telefone|email|uf|bairro|cep|municipio|complemento|
|--:|----|-------|----|--------------|--------|-----|--|------|---|---------|-----------|
|12345678900|José da Silva|Fernanda da Silva|masculino|23/10/1985|62 99999999|jsilva@gmail.com|GO|Jardim américa|7498045|Goiânia|-----|

-----------------

Funções Backend

|Função|Nome de quem vai fazer|Status|
|-----:|----------------------|------|
|Buscar paciente pelo CPF | Isadora|Feito|
|Mostrar nome do paciente na home|---------------------- |------|
|Editar dados do paciente | Felipe |feito|
|Editar dados do ACS| Felipe |Pendente|
|Mostrar dados do paciente no perfil| Gabriel |Pendente|
|Mostrar dados do ACS no perfil| Gabriel |Pendente|
|Cadastrar paciente| Felipe |Feita|
|Cadastrar ACS|Felipe |Feita|
|Desativar o perfil de um paciente| Rafael |Pendente|
|Trocar senha de acesso| Hugo |Pendente|
|Ver senha| Hugo |Feita|
|Validar CPF| Hugo |Pendente|
