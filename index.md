// variaveis
const mensagem = 'oi, tudo bem ?'
// tipos de dados 

// função
  alert(mensagem)

// objeto javascript
const participante = {
  nome: "FELIPE VELOSO",
  email: "felide@gmail.com",
  dataIncricao: new Date(2024, 2, 22, 19, 20),
  dataCheckin: new Date(2024, 2, 25, 22, 00)
} 
let participante =[
  {
  nome: "FELIPE VELOSO",
  email: "felide@gmail.com",
  dataIncricao: new Date(2024, 2, 22, 19, 20),
  dataCheckin: new Date(2024, 2, 25, 22, 00)
  },
]
// estrutura de repetição loop
 for(let participante of participantes){
  output = output + criarNovoParticipante(participante)
 }