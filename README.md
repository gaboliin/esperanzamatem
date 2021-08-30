# esperanzamatem
# fracasando como siempre
# esperanza matematica de resultados 
import math

x = {"2": 0.18, "5": 0.3, "6": 0.22, "8": 0.16, "9": 0.08, "10": 0.06}


#print(x.items())
print(x.keys())

#resultado = float(input("La esperanza matematica es:['0']*0.18 + ['1']*0.3 + ['2']* 0.22 + ['3']*0.16 + ['4']*0.08 + ['5']*0.06"))

#resultado = x['2']*0.18 + x['5']*0.3 + x['6']* 0.22 + x['8']*0.16 + x['9']*0.08 + x['10']*0.06 
#print(resultado)




#opcion 2

px = [0.18, 0.3, 0.22, 0.16, 0.08, 0.06]
x =  [2, 5, 6, 8, 9, 10]
X = {'x':x, 'px': px}
X = x * px
print(X)
