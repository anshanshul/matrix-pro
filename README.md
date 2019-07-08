# matrix-pro
import numpy as np
"""
listb = [13,79,50]
lista = [[1,1,1],[2,1,4],[8,3,9]]
arr1 = np.mat(np.array(listb))
arr2= np.mat(np.array(lista))
print(type(arr1))
print(type(arr2))
x= (arr1)*(arr2.I)
print(x)
"""
listb = [13,79,50,109]
lista = [[1,1,1,1],[2,1,4,2],[8,3,9,7],[5,6,10,5]]
arr1=np.mat(np.array(listb))
arr2=np.mat(np.array(lista))
                     
print(type(arr1))
print(type(arr2))
x=(arr1)*(arr2.I)
print(x)


