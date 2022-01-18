# Alura-Phyton1
CRIAR PERGUNTAS DENTRO DE CAIXAS

def saudacao ():
  nome = input('Qual é o seu nome? ')  
  Sobrenome = input('Qual é o seu sobrenome? ')  
  Idade = input('Qual a sua idade? ')  
  print(f"Olá, tudo bem? {nome} {Sobrenome}!")  
  saudacao () 

PARAMETROS

nome = 'Humberto'
def saudacao_com_parametros(nome_da_pessoa):
  print(f'Olá {nome_da_pessoa}')
  saudacao_com_parametros(nome)
  
 
 PARAMENTROS
  
  idade = 90

def verica_se_pode_dirigir(idade):
  if idade >= 18:
   print('Tem permissão para dirigir')
  else:
    print('Não tem permissão para dirigir')
    verica_se_pode_dirigir(idade)
    
    
    
    def verifica_se_pode_dirigir_sem_parametro():
  idade = input('Qual sua idade ')
  idade = int(idade)
  if idade >= 18:
    print('Tem permissão para dirigir')
  else:
    print('Não tem permissão para dirigir')
    verifica_se_pode_dirigir_sem_parametro()
    
   
   def velocidade(espaco, tempo):
 v = espaco / tempo
 print(f'Velocidade: {v} m/s')

velocidade(100, 20)
    
