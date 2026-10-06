
## Sorriso Metálico

### Introdução
O Sorriso Metálico é um consultório odontológico. O objetivo do sistema é facilitar o agendamento de consultas, o cadastro de pacientes e dentistas e o controle dos horários disponíveis.


## Entidades

-> Paciente
-> Dentista
-> Agendamento

## Atributos

-> paciente:

• ID_Paciente
• Nome_Paciente
• Telefone_Paciente
• Categoria (Comum ou VIP)

-> Dentista:

• ID_Dentista
• Nome_Dentista
• Registro Profissional

-> Agendamento

• ID_Agendamento
• ID_Cliente
• ID_Dentista
• Data_Agendamento
• Horário_Consulta


## Relacionamento

• O realacionamento é de 1:N, pois um paciente e um dentista podem ter diversos agendamentos.

## DER 
![alt text](<Captura de tela 2026-10-06 161908.png>)



**Cliente:** Doutor Roberto - Sorriso Metálico.
