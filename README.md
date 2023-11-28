# RES-514 Python Pour la cyber


## built-in fonction


**`__init__()`**

- Toutes les classes ont une fonction appelée __init__(), qui est toujours exécutée lors du lancement de la classe.

- Permet d'attribuer des valeurs aux propriétés de l'objet ou à d'autres opérations nécessaires à effectuer lors de la création de l'objet :

### Exemple

```python
class Person:
  def __init__(self, name, age):
    self.name = name
    self.age = age

p1 = Person("John", 36)

print(p1.name)
print(p1.age) 

#John
# 36
```
