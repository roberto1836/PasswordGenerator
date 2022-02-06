from random import randint
def contrasenna():
    numero = randint(14,18)
    caracteres = "abcdefghijklmnopqrstuvwxyz"
    caracteresM = caracteres.upper()
    numeros = "123456789"
    caracteresEspeciales = "()/!?&$}{][;:.,-+*"
    contrasenna = ""
    for i in range(numero):
        j = randint(1,4)
        if j == 1:
            contrasenna += caracteres[randint(1,len(caracteres)-1)]
        elif j == 2:
            contrasenna += caracteresM[randint(1,len(caracteresM)-1)]
        elif j == 3:
            contrasenna += numeros[randint(1,len(numeros)-1)]
        else:
            contrasenna += caracteresEspeciales[randint(1,len(caracteresEspeciales)-1)]
    return contrasenna
print(contrasenna())
