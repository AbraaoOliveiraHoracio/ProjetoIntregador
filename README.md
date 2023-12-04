# Briefing Sistema de Alocamento:

## Dores identificadas: 
    - Dificuldade de Acesso às Informações:
    - Os alunos e professores podem enfrentar dificuldades para acessar informações sobre seus horários de aulas e alocação de salas.
## Objetivo:
    - Desenvolver um sistema de agendamento de aulas que permita coordenadores 
    - Professores e alunos acessar informações sobre horários de aulas, alocação de salas e laboratórios
    - E detalhes das disciplinas e cursos.

## Atores do Sistema:
  ### Professor:
      - Funções: Visualizar seus próprios horários e salas alocadas. 
      - Faz login no sistema.  
  ### Alunos:
      - Funções: 
      - Cadastrar-se no sistema.
      - Visualizar horários de aulas relacionados ao seu curso.
  
  ### Restrições: 
          - Não podem editar informações, apenas visualizar (tanto aluno, quanto professores).

  ### Coordenadores:
        - Alocar disciplinas a professores, salas e laboratórios.
        - Visualizar qual professor está alocado em uma sala ou laboratório.
        - Cadastrar professores e cursos no sistema.


## Caso De Uso

![image](https://github.com/AbraaoOliveiraHoracio/ProjetoIntregador/assets/127244271/fa01909b-3307-49f2-affb-485d4df0e701)


 ## End Points

![image](https://github.com/AbraaoOliveiraHoracio/ProjetoIntregador/assets/127244271/541f6454-5e3b-46c6-bff9-80ea97f61834)

## Modelo Conceitual

![image](https://github.com/AbraaoOliveiraHoracio/ProjetoIntregador/assets/127892758/cb979226-e3ea-48a1-a16b-28c1ff3e9e81)


 ## Diagrama UML
  
 ![image](https://github.com/AbraaoOliveiraHoracio/ProjetoIntregador/assets/127244271/03d5da85-97c4-42b2-b62c-4a23ef4c61f6)



## Principais funções do sistema:

1. **Alocação de Disciplinas:**
   - Permite aos coordenadores associar disciplinas a professores, cursos e salas/laboratórios.
   - Permite a edição e atualização dessas alocações.

2. **Visualização de Horários:**
   - Professores e alunos podem visualizar seus próprios horários.

3. **Reserva de Salas/Laboratórios:**
   - Coordenadores podem alocar salas e laboratórios para disciplinas específicas.

4. **Históricos passados:**
   - Mantém um registro de todas as mudanças feitas nos horários para referência futura.
      *Exemplo: em 2024, será possivel visualizar histórico do ano de 2023. 

5. **Cadastro de Usuários:**
   - Permite que coordenador cadastre professores.
   - Alunos autocadastram no sistema.

6. **Foco de Alunos:**
   - Permite que os alunos escolham uma disciplina específica e visualiza horários relacionados a ela.

7. **Impressão de Horários:**
   - Oferece a opção de imprimir horários para referência física.  

## Observações: 

  - Cada disciplina pode alocar 1 sala e 1 laboratório.
  - No sistema não será possível reservar uma sala/laboratório quando estiver ocupado.
  - Juntar apenas disciplina com sala. 

## Protótipo de nosso projeto
    - https://www.figma.com/file/fZJ5PUqW5jFBTOpXC2aEOo/Trabalho-de-PI?type=design&node-id=0%3A1&mode=design&t=HoMrfE9NK7ys8yTh-1
####
