# Criar DB escola
use escola

# Show base de dados
show dbs

# Inserir aluno 

db.alunos.insert({
  "nome": "Antonio",
  "idade": 12, 
  "gostade":["maça","video","jogos"], 
  "matriculado": true, 
 
 "disciplinas": { 
    "Portugues" : 16.5, 
    "Matematica" : 18,
    "Historia" : 10
  }
  
})

# Se diggitarmos db 
output sera = escola

# Estamos na db escola que ja contem alunos
 para vermos o conteudo :
 
 db.alunos.find().pretty() //pretty() é um formatador

