# MediMate Watch - Senior Sync Tech 

(![idoso](https://github.com/G3n4r00/MediMate-Watch/assets/126473193/82ebacb2-a3af-47eb-9837-208f303f9275))

>Status: Protótipo Digital ⚙️>
>

## Visão Geral

O MediMate Watch é uma solução designada principalmente aos idosos, nossa solução visa resolver um problema muito simples na vida da terceira idade mas que acaba por afetar muito o dia de todos desse grupo. Nossa solução irá alertar as pessoas sempre que for hora de tomar seu remédio e, não apenas lembrar no horário correto, como também indicará o nome e a dosagem que deve tomar, tudo isso em uma interface extremamente simples que não irá ser necessário nenhum esforço dos idosos.

## Objetivos do Projeto 🎯
Nosso princinapl objetivo é levar tranquilidade à vida dos idosos, pensando principalmente naqueles que estão solitários, seja por abandono dos filhos ou morte do parceiro. Queremos tirar ao menos uma preocupação da cabeça desses idosos e dar essa preocupação ao nosso dispositivo, ele leembrará o idoso quando e o que tomar, snedo possível ter uma maior tranquilidade durante o dia.

### Objetivos Específicos 

- Desenvolver uma Interface Intuitiva e Acessível: Garantir que a interface do MediMate Watch seja simples, com botões de fácil identificação e texto claro, para facilitar a operação por parte dos idosos que vivem sozinhos.

- Proporcionar Lembretes Precisos e Personalizados: Implementar um sistema de lembretes visuais e sonoros no horário correto para cada medicamento, permitindo personalização de doses e horários conforme as necessidades individuais de cada usuário.

- Estabelecer Conectividade Remota com Profissionais de Saúde: Desenvolver um sistema que permita a conexão remota entre o relógio e os sistemas de saúde, possibilitando que médicos atualizem prescrições ou horários de medicamentos de forma segura e conveniente.

- Assegurar Segurança e Proteção de Dados: Garantir que todos os dados médicos dos usuários estejam protegidos, utilizando medidas de segurança robustas para prevenir acesso não autorizado e criptografando as comunicações entre o relógio e os sistemas de saúde.

- Fornecer Suporte Eficiente e Material de Instrução Claro: Oferecer suporte técnico acessível e eficaz para solucionar dúvidas ou problemas relacionados ao uso do MediMate Watch, além de disponibilizar um manual de instruções detalhado e um FAQ para facilitar o entendimento das funcionalidades do dispositivo.

## Foto do Protótipo Digital 

(![image](https://github.com/G3n4r00/MediMate-Watch/assets/126473193/560b4db2-1ec2-4d24-954d-24de1b759b61))

## Equipamentos utilizados 🧰 : 

<table> 
  <tr>
    <td>Módulo ESP32</td>
    <td>Display LCD I2C</td>
    <td>Módulo Buzzer</td>
    <td>jumpers</td>
  </tr>
</table>

## Funcionamento 🛠️

O proejto funciona como um relógio comum para que os idosos possam consultar a hora e a data tranquilamente, esse horário e data estâo regulados por meio do método NTP.br sincronizando o horário perfeitamente com o horário oficial nrasileiro

Entretanto a parte especial do projeto é a conexão via Http utilizando FIWARE para registrar horários em que o alarme deve ser ativado, sendo possível adicionar medicamentos ou modificar horários, sendo possível os médicos controlarem e preescreverem os remédios à distância
O MediMate Watch visa essa conexão onde o médico pode adicionar novos medicamentos aos pacientes sem que o paciente tenha de se deslocar até a consulta, o alarme será ativada no horário correto exibindo o nome do remédio e sua dosagem, facilitando ao máximo a vida dos pacientes idosos 

## Website 🌐

O projeto também inclui um website dedicado. Este website contém informações soobre o projeto adicionais que permitem que mais pessoas conheçam o MediMate Watch, e ainda tem informações adicionais para aqueles que já connhecem nosso produto

## Requisitos do Sistema ⚠️

- Comunicação com a Internet para transmissão de dados.
- Utilização do Postman para envio de comandos e criação de entidades.
- Utilização do dispositivo ESP32 para controle e comunicação.
- Conexão com o sistema NTP.br para a exatidão do relógio.
- Utilização do Postaman para comunicação de métodos POST PATCH do método MqTT


## Instruções de Uso ❗

### Instruções de Uso para Pacientes 👥:
- Ativar o relógio
- Observar os horários
- Conferir se tudo está corretamente ligado
- Aguardar alarmes ativados pelos médicos


### Insntruções de Uso para Médicos 
- Entrar no Postman 

##Equipe 
- Gabriel Genaro - RM551986
- Paloma Mirela - RM551321
