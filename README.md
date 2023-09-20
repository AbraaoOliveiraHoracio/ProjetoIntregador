# Briefing Sistema de Alocamento:

## Dores identificadas 
    - Dificuldade de Acesso às Informações: Os alunos e professores podem enfrentar dificuldades para acessar informações sobre seus horários de aulas e alocação de salas.
## Objetivo:
 -Desenvolver um sistema de agendamento de aulas que permita coordenadores, professores e alunos acessar informações sobre horários de aulas, alocação de salas e laboratórios, e detalhes das disciplinas e cursos.

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
    
####
