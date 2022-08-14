### Básico

| CAMPO                        | DESCRIÇÃO                                                                                            |
| ---------------------------- | ---------------------------------------------------------------------------------------------------- |
| ~HS\_CPF~                    | Valor MD5 do CPF em hexadecimal                                                                      |                                   |
| TEMPOCPF                     | Tempo (em anos) desde a emissão do CPF                                                               |
| DISTCENTROCIDADE             | Distância (em metros) do CEP informado ao centro da cidade                                           |
| ~ORIENTACAO\_SEXUAL~         | Orientação sexual presumida do proponente                                                            |
| ~RELIGIAO~                   | Religião do proponente.                                                                              |
| DISTZONARISCO                | Distância (em metros) da zona de risco mais próxima.                                                 |
| QTDENDERECO                  | Quantos endereços distintos o proponente possui na base                                              |
| QTDEMAIL                     | Quantos emails distintos o proponente possui na base                                                 |
| QTDCELULAR                   | Quantos telefones celulares distintos o proponente possui na base                                    |
| CELULARPROCON                | Proponente possui telefone celular incluido no procon                                                |
| QTDFONEFIXO                  | Quantos telefones fixos distintos o proponente possui na base                                        |
| TELFIXOPROCON                | Proponente possui telefone fixo incluido no procon                                                   |
| TARGET                       | Determinação se a proposta é inadimplente (1) ou não (0)                                             |                                                                                                      |


### Renda

| CAMPO                        | DESCRIÇÃO                                                                                            |
| ---------------------------- | ---------------------------------------------------------------------------------------------------- |
| ESTIMATIVARENDA              | Estimativa de renda                                                                                  |
| QTDDECLARACAOISENTA          | Quantas vezes o CPF declarou imposto de renda como isento nos últimos 10 anos                        |
| QTDDECLARACAO10              | Quantas vezes o CPF declarou IRPF nos últimos 10 anos                                                |
| QTDDECLARACAOREST10          | Quantas vezes o CPF declarou IRPF com imposto a restituir nos últimos 10 anos                        |
| QTDDECLARACAOPAGAR10         | Quantas vezes o CPF declarou IRPF com imposto a pagar nos últimos 10 anos                            |
| RESTITUICAOAGENCIAALTARENDA  | Flag se o CPF já restituiu alguma vez em agências classificada como alta renda                       |
| BOLSAFAMILIA                 | Flag indicativo se o CPF participa do programa bolsa familia do Governo Federal                      |
| ANOSULTIMARESTITUICAO        | Tempo (em anos) desde a última declaração de IRPF com imposto a restituir                            |
| ANOSULTIMADECLARACAO         | Tempo (em anos) desde a última declaração de IRPF                                                    |
| ANOSULTIMADECLARACAOPAGAR    | Tempo (em anos) desde a última declaração de IRPF com imposto a pagar                                |


### Empresarial

| CAMPO                        | DESCRIÇÃO                                                                                            |
| ---------------------------- | ---------------------------------------------------------------------------------------------------- |
| INDICEEMPREGO                | Indice de estabilidade do CPF no emprego                                                             |
| PORTEEMPREGADOR              | Porte da empresa em que o CPF trabalha                                                               |
| SOCIOEMPRESA                 | Flag indicativo se o CPF participa de alguma empresa                                                 |
| FUNCIONARIOPUBLICO           | Flag indicativo se o CPF é um funcionário público                                                    |
| SEGMENTACAO                  | Indice de segmentação total nos últimos 12 meses                                                     |
| SEGMENTACAOCOBRANCA          | Indice de segmentação de cobrança nos últimos 12 meses                                               |
| SEGMENTACAOECOM              | Indice de segmentação de E-commerce nos últimos 12 meses                                             |
| SEGMENTACAOFIN               | Indice de segmentação Financeira nos últimos 12 meses                                                |
| SEGMENTACAOTELECOM           | Indice de segmentação de Telecom nos últimos 12 meses                                                |


### Familiar

| CAMPO                        | DESCRIÇÃO                                                                                            |
| ---------------------------- | ---------------------------------------------------------------------------------------------------- |
| QTDPESSOASCASA               | Quantidade de pessoas no household                                                                   |
| MENORRENDACASA               | Renda Presumida mínima dos integrantes do HouseHold                                                  |
| MAIORRENDACASA               | Renda Presumida máxima dos integrantes do HouseHold                                                  |
| SOMARENDACASA                | Soma das Rendas Presumidas de todos os integrantes do Household                                      |
| MEDIARENDACASA               | Renda Presumida média dos integrantes do Household                                                   |
| MAIORIDADECASA               | Maior idade dos integrandes do Household                                                             |
| MENORIDADECASA               | Menor idade dos integrandes do Household                                                             |
| MEDIAIDADECASA               | Idade média dos integrantes do Household                                                             |
| INDICMENORDEIDADE            | Flag indicativo se no household tem alguma pessoa com idade entre 16 e 17 anos                       |
| COBRANCABAIXOCASA            | Flag indicativo se algum integrante do Household possui Indice de segmentação de cobrança baixo      |
| COBRANCAMEDIOCASA            | Flag indicativo se algum integrante do Household possui Indice de segmentação de cobrança medio      |
| COBRANCAALTACASA             | Flag indicativo se algum integrante do Household possui Indice de segmentação de cobrança medio alto |
| SEGMENTACAOFINBAIXACASA      | Flag indicativo se algum integrante do Household possui Indice de segmentação financeira baixo       |
| SEGMENTACAOFINMEDIACASA      | Flag indicativo se algum integrante do Household possui Indice de segmentação financeira medio       |
| SEGMENTACAOALTACASA          | Flag indicativo se algum integrante do Household possui Indice de segmentação financeira medio alto  |
| BOLSAFAMILIACASA             | Flag indicativo se algum integrante do Household participa do bolsa familia                          |
| FUNCIONARIOPUBLICOCASA       | Flag indicativo se algum integrante do Household é funcionário público                               |

### Regional

| CAMPO                        | DESCRIÇÃO                                                                                            |
| ---------------------------- | ---------------------------------------------------------------------------------------------------- |
| IDADEMEDIACEP                | Idade media das pessoas que vivem no mesmo CEP do proponente                                         |
| PERCENTMASCCEP               | Percentual de pessoas do sexo masculino que vivem no mesmo CEP do proponente                         |
| PERCENTFEMCEP                | Percentual de pessoas do sexo feminino que vivem no mesmo CEP do proponente                          |
| PERCENTANALFABETOCEP         | Percentual de pessoas com escolaridade ANALFABETO que vivem no mesmo CEP do proponente               |
| PERCENTPRIMARIOCEP           | Percentual de pessoas com escolaridade PRIMARIO INCOMPLETO que vivem no mesmo CEP do proponente      |
| PERCENTFUNDAMENTALCEP        | Percentual de pessoas com escolaridade FUNDAMENTAL INCOMPLETO que vivem no mesmo CEP do proponente   |
| PERCENTMEDIOCEP              | Percentual de pessoas com escolaridade MEDIO INCOMPLETO que vivem no mesmo CEP do proponente         |
| PERCENTSUPERIORCEP           | Percentual de pessoas com escolaridade SUPERIOR INCOMPLETO que vivem no mesmo CEP do proponente      |
| PERCENTMESTRADOCEP           | Percentual de pessoas com escolaridade MESTRADO COMPLETO que vivem no mesmo CEP do proponente        |
| PERCENTDOUTORADOCEP          | Percentual de pessoas com escolaridade DOUTORADO COMPLETO que vivem no mesmo CEP do proponente       |
| PERCENTBOLSAFAMILIACEP       | Percentual de pessoas inscritas no bolsa familia que vivem no mesmo CEP do proponente                |
| PERCENTFUNCIONARIOPUBLICOCEP | Percentual de pessoas que são funcionários públicos que vivem no mesmo CEP do proponente             |
| MEDIARENDACEP                | Renda presumida média das pessoas que vivem no mesmo CEP do proponente                               |
| PIBMUNICIPIO                 | PIB municipal per capito                                                                             |
| QTDUTILITARIOMUNICIPIO       | Quantidade de veículos tipo utilitário por 1.000 habitantes no municipio                             |
| QTDAUTOMOVELMUNICIPIO        | Quantidade de veículos tipo automoveis por 1.000 habitantes no municipio                             |
| QTDCAMINHAOMUNICIPIO         | Quantidade de veículos tipo caminhão por 1.000 habitantes no municipio                               |
| QTDCAMINHONETEMUNICIPIO      | Quantidade de veículos tipo caminhonete por 1.000 habitantes no municipio                            |
| QTDMOTOMUNICIPIO             | Quantidade de veículos tipo motocicleta por 1.000 habitantes no municipio                            |
| PERCENTPOPZONAURBANA         | Perecentual da população do municipio vive na zona urbana                                            |
| IDHMUNICIPIO                 | IDH do municipio                                                                                     |
