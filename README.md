#1 - Somar dois números
#2 - Multiplicar dois números
#3 - Sair


versao = ("                              11                                   ").replace(" ", "")
pergunta = ("")
A = ("")
B = ("")
X = ("")


print(f"=======================VERSÃO {versao}============================")

def prints():

    print("digite o numero correspondente ao oque você quer fazer.")
    print("1 - soma")
    print("2 - multiplicar")
    print("3 - sair")

def coleta():
    print("digite o primeiro numero:")
    A == int(input(""))
    print("digite o segundo numero:")
    B == int(input(""))



def soma():

    try:
         X == A + B
         return X

    except:
        print("esse algarismo não é um numero, tente novamente.")


def vezes():
    try:
        X == A * B
        return X
    except:
        print("esse algarismo não é um numero, tente novamente.")



while True:
    prints()
    pergunta = input("")
    if pergunta == ("1"):
        coleta()
        soma()
    elif pergunta == ("2"):
        coleta()
        vezes()
    elif pergunta == ("3"):
        print("encerrando...")
        break
    else:
        print("escolha invalida.") 


