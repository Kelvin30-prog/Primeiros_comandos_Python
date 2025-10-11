# Primeiros_comandos_Python
Colocando o python para ler e valores em variáveis

# Adicionando variáveis 
nome = ""
idade = ""
nascimento = ""
cidade = ""
profissao = ""
renda = ""
cpf = ""
civil = ""

#Adicionando perguntas
print ("Seja bem vindo ao seu app parceiro, somente aqui você terá as oportunidades que procura.")
print ("Antes de iniciarmos, precisamos das suas informações para realizar o seu cadastro.")
print ("Por favor, preencha os itens abaixo:")
print ("")
print ("Nome completo:")
nome = input()
print ("Idade?")
idade = input()
print ("Data de nascimento?")
nascimento = input()
print ("Estado civíl?")
civil = input()
print ("Cidade que você mora?")
cidade = input()
print ("Qual a sua atual profissão?")
profissao = input()
print ("Qual a sua atual renda?")
renda = input()
print ("Informe o seu CPF:")
cpf = input ()


#Realizando a apresentação
print ("")
print ("")
print ("Confirme as informações abaixo:")
print ("")
print ("Seu nome é: " + nome)
print ("Seu atual estado civíl é: " + civil)
print ("Atualmente você tem " + idade + " anos e nasceu no dia " + nascimento)
print ("Você mora na cidade de " + cidade)
print ("Sua profissão atual é: " + profissao)
print ("Sua renda bruta é: R$" + renda)
print ("Seu CPF é: " + cpf)