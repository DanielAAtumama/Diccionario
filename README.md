# Crear un diccionario vacío llamado perro
perro = {}

# Añadir nombre, color, raza, patas y edad al diccionario perro
perro['nombre'] = 'Jacobo'
perro['color'] = 'negro'
perro['raza'] = 'perro lobo'
perro['patas'] = 4
perro['edad'] = 5

# Crear un diccionario de estudiante y añadir las claves y valores
estudiante = {
    'nombre': 'Daniel',
    'apellido': 'Altahona',
    'sexo': 'Masculino',
    'edad': 19,
    'estado civil': 'Soltero',
    'habilidades': ['Programación', 'comer'],
    'país': 'Colombia',
    'ciudad': 'Cartagena',
    'dirección': 'Calle San Fernando'
}

# Obtener la longitud del diccionario del alumno
longitud_estudiante = len(estudiante)
print("Longitud del diccionario del estudiante:", longitud_estudiante)

# Obtener el valor de las habilidades y comprobar el tipo de datos
habilidades = estudiante['habilidades']
print("Habilidades del estudiante:", habilidades)
print("Tipo de datos de habilidades:", type(habilidades))

# Modificar los valores de las habilidades añadiendo una o dos habilidades
estudiante['habilidades'].extend(['correr', 'jugar'])

# Obtener las claves del diccionario como una lista
claves_estudiante = list(estudiante.keys())
print("Claves del diccionario del estudiante:", claves_estudiante)

# Obtener los valores del diccionario como una lista
valores_estudiante = list(estudiante.values())
print("Valores del diccionario del estudiante:", valores_estudiante)

# Cambiar el diccionario a una lista de tuplas utilizando el método items()
estudiante_tuplas = list(estudiante.items())
print("Diccionario de estudiante como lista de tuplas:")
print(estudiante_tuplas)

# Eliminar uno de los elementos del diccionario
del estudiante['dirección']

# Borrar uno de los diccionarios
del perro
