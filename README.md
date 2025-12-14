# POO

## Integrantes da equipe: 
Jose railson leite da silva == fico responsavel pelas classes e ajudar na interface
Jose junio de souza mathias == fico responsavel por salvar as coisas no banco de dados
Marcos felipe ferreira duarte == fico responsavel pela interface

## Principais classes dos projeto
Class: Animais
Atributos: espécie, raça, nome, sexo, idade em meses, porte (P/M/G), estado,status( disponivel , reservado , adotado, devolvido , quarentena, inadotavel)
Metodo:cadastrar , editar, remover, adotar

Class: Histórico de eventos
Atributos: animal, eventos
Metodo: adicionar, remover, listar

Class: Eventos
Atributos:status(entrada, vacina, adoção, devolução),descricao, data
Metodo:mudaca de status, cadastrar , editar, remover

Class: Triagem
Atributos: adotantes (nome, idade, moradia: [casa/apto], área útil, experiência, crianças, [sim/não], outros animais), animal, pontuacao, elegivel, observacoes
Metodo:cadastrar, avaliar, calcular compatibilidade, validar politicas

Class: Usuario
Atributos:nome, idade, moradia: [casa/apto], área útil, experiência, crianças, [sim/não], outros animais
Metodo:cadastrar , editar

Class: Reserva
Atributos:animal, adotante, data de inicio, data de expiracao, ativo
Metodo:cadastrar, expirar, cancelar

Class: Adoção
Atributos: animal, adotante, data,taxa
Metodo:cadastrar, finalizar, cancelar, gerar contrato

Class: Lista de espera
Atributos:animal, reserva tempo limite, Adoção efetiva, prioridade
Metodo:adicionar, remover, proximo

Class: Devolução
Atributos:animal, data, motivo, status,
Metodo:cadastrar, reavaliacao

Class: Relatórios
Atributos:data de inicio, data fim, tipo(mais adotados, taxa de adocao, tempo medio, devolucoes motivo)
Metodo:gerar relatorio




