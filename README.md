# Curso Intermedio de Python

## Modulo 1

1. Las listas son estructuras de datos ordenadas y mutables. Se pueden modificar, ordenar, recorrer y aplicar operaciones como slicing y comprensión de listas.

## Modulo 2

2. Las tuplas son similares a las listas, pero inmutables. Son útiles cuando se necesita garantizar que los datos no cambien, como coordenadas o registros constantes.

## Modulo 3

3. Los diccionarios permiten almacenar pares clave-valor. Son ideales para acceder rápidamente a datos asociados a una clave específica.

## Modulo 4

4. Los conjuntos (sets) son colecciones no ordenadas de elementos únicos. Permiten operaciones matemáticas como unión, intersección y diferencia.

## Modulo 5

5. El método de comprensión de listas (`list comprehensions`) ofrece una forma concisa de construir listas aplicando transformaciones o filtros a iterables.

## Modulo 6

6. Las funciones permiten encapsular lógica reutilizable. Pueden tener parámetros, retornar valores y usar valores por defecto.

## Modulo 7

7. `*args` y `**kwargs` permiten definir funciones que aceptan argumentos variables, posicionados y nombrados, respectivamente.

## Modulo 8

8. Las funciones lambda son funciones anónimas que se definen en una sola línea y se usan comúnmente en operaciones funcionales.

## Modulo 9

9. El concepto de ámbito (scope) en Python determina dónde son accesibles las variables. Incluye el ámbito local, global y no local.

## Modulo 10

10. Las funciones pueden anidarse, permitiendo la creación de closures, que conservan el contexto donde fueron definidas.

## Modulo 11

11. Las funciones `map`, `filter` y `reduce` permiten aplicar operaciones funcionales a secuencias, como transformar, filtrar o acumular datos.

## Modulo 12

12. Las funciones en Python son ciudadanos de primera clase, lo que significa que pueden ser asignadas a variables, pasadas como argumentos y retornadas.

## Modulo 13

13. El manejo de errores en Python se realiza mediante bloques `try`, `except`, `else` y `finally` para controlar y responder a excepciones.

## Modulo 14

14. Capturar excepciones específicas en lugar de usar `except:` mejora la claridad del código y evita errores ocultos.

## Modulo 15

15. Se pueden definir excepciones personalizadas heredando de la clase `Exception`, lo que facilita el control detallado de errores.

## Modulo 16

16. Python permite la POO, donde las clases definen atributos y métodos, y los objetos son instancias de estas clases.

## Modulo 17

17. El método `__init__` actúa como constructor de una clase e inicializa los atributos del objeto.

## Modulo 18

18. La herencia permite a una clase hija heredar métodos y atributos de una clase padre, promoviendo la reutilización de código.

## Modulo 19

19. La sobreescritura (override) de métodos permite redefinir el comportamiento heredado en una subclase.

## Modulo 20

20. Los métodos `@staticmethod` y `@classmethod` definen funciones asociadas a la clase que no dependen del estado del objeto.

## Modulo 21

21. Un módulo es un archivo `.py` que contiene funciones y clases reutilizables. Se importa con `import` o `from`.

## Modulo 22

22. Los paquetes son carpetas que agrupan módulos y contienen un archivo `__init__.py`. Permiten estructurar grandes proyectos.

## Modulo 23

23. Se pueden importar módulos completos o partes específicas, y también usar alias para acortar nombres de importación.

## Modulo 24

24. Python permite trabajar con archivos usando `open()`, junto con los métodos `read()`, `write()` y `close()`.

## Modulo 25

25. El uso del bloque `with open(...)` garantiza el cierre automático del archivo, incluso si ocurre una excepción.

## Modulo 26

26. Los iteradores son objetos que implementan los métodos `__iter__()` y `__next__()` y permiten recorrer estructuras secuenciales.

## Modulo 27

27. Los generadores permiten crear iteradores de forma sencilla usando `yield`, ideal para grandes volúmenes de datos.

## Modulo 28

28. El módulo `re` permite trabajar con expresiones regulares para buscar, extraer y manipular patrones en cadenas de texto.

## Modulo 29

29. Se pueden usar grupos en expresiones regulares con paréntesis `()` para capturar subpatrones específicos dentro del texto.

## Modulo 30

30. Los decoradores modifican el comportamiento de funciones envolviéndolas con otras funciones, y se usan comúnmente con `@decorador`.

## Modulo 31

31. Un closure es una función que recuerda el entorno donde fue creada, útil para mantener estados privados entre llamadas.

## Modulo 32

32. Las comprensiones de diccionarios permiten crear diccionarios en una sola línea a partir de otros iterables.

## Modulo 33

33. Las comprensiones de conjuntos permiten generar colecciones únicas de elementos usando condiciones y transformaciones.

## Modulo 34

34. Los context managers permiten controlar recursos de forma automática, como archivos o conexiones, usando `with`.

## Modulo 35

35. Python permite añadir anotaciones de tipo con `type hints`, mejorando la legibilidad y facilitando la detección de errores.

## Modulo 36

36. Python incluye el módulo `unittest` para escribir pruebas automatizadas que aseguren que las funciones se comportan como se espera.

## Modulo 37

37. El módulo `datetime` permite trabajar con fechas y horas, incluyendo cálculos y formateo personalizado.

## Modulo 38

38. El módulo `os` permite interactuar con el sistema operativo, como acceder a rutas de archivos, variables de entorno o procesos.

## Modulo 39

39. El módulo `sys` da acceso a variables y funciones que interactúan con el intérprete de Python.

## Modulo 40

40. El módulo `collections` ofrece estructuras de datos especializadas como `defaultdict`, `Counter` y `deque`.

## Modulo 41

41. El módulo `functools` proporciona herramientas para programación funcional, como `lru_cache`, `partial` y `wraps`.

## Modulo 42

42. El módulo `itertools` ofrece herramientas eficientes para trabajar con iteradores, como `product`, `permutations`, y `groupby`.

## Modulo 43

43. Python permite introspección, es decir, examinar objetos en tiempo de ejecución con funciones como `type()`, `dir()`, `getattr()` y `hasattr()`.

## Modulo 44

44. Las anotaciones de tipo pueden ser reforzadas usando herramientas como `mypy` para realizar verificación estática de tipos.

## Modulo 45

45. La serialización convierte estructuras en cadenas o bytes. Python ofrece `pickle`, `json` y `marshal` para este propósito.

## Modulo 46

46. El módulo `json` permite convertir objetos entre JSON y estructuras de Python como diccionarios o listas.

## Modulo 47

47. `pickle` permite serializar objetos de Python en binario, útil para guardar estados complejos pero no seguro con datos externos.

## Modulo 48

48. Python permite la ejecución dinámica de código con `eval()` y `exec()`, aunque deben usarse con precaución por razones de seguridad.

## Modulo 49

49. Los generadores pueden delegar a otros generadores con `yield from`, lo que facilita la composición de generadores complejos.

## Modulo 50

50. Un iterador personalizado puede implementarse definiendo una clase con los métodos `__iter__()` y `__next__()`.

## Modulo 51

51. Las expresiones generadoras (`(x for x in iterable)`) permiten crear iteradores sin usar memoria adicional para listas completas.

## Modulo 52

52. Las metaclases permiten modificar el comportamiento de clases al ser creadas, mediante la redefinición del método `__new__()` en la clase metaclase.

## Modulo 53

53. La función `super()` permite llamar métodos de la clase padre en una jerarquía de herencia, útil en herencia múltiple.

## Modulo 54

54. Python permite sobrecargar operadores implementando métodos especiales como `__add__`, `__len__`, `__getitem__`, etc.

## Modulo 55

55. El método `__call__()` permite a una instancia de clase comportarse como una función.

## Modulo 56

56. Los context managers personalizados se crean con clases que implementan `__enter__()` y `__exit__()` o usando el decorador `@contextmanager`.

## Modulo 57

57. Python incluye `argparse` para construir interfaces de línea de comandos robustas con argumentos posicionales y opcionales.

## Modulo 58

58. El módulo `logging` ofrece un sistema configurable para registrar mensajes, con distintos niveles como `debug`, `info`, `warning`, `error`, y `critical`.

## Modulo 59

59. Las excepciones pueden encadenarse explícitamente con `raise ... from ...` para mantener el contexto original del error.

## Modulo 60

60. Python soporta multiprocesamiento con el módulo `multiprocessing`, útil para aprovechar varios núcleos de CPU.

## Modulo 61

61. El módulo `threading` permite ejecutar código en múltiples hilos, útil para tareas I/O concurrentes.

## Modulo 62

62. Python gestiona memoria automáticamente con un recolector de basura que elimina objetos no referenciados.

## Modulo 63

63. El protocolo de datos de Python permite la implementación de objetos que se comportan como secuencias, iteradores o mapeos.

## Modulo 64

64. El método `__repr__()` proporciona una representación textual de un objeto para depuración, mientras que `__str__()` da una forma legible.

## Modulo 65

65. El protocolo de comparación se basa en métodos como `__eq__`, `__lt__`, `__gt__`, etc., usados por operadores como `==`, `<`, `>`.

## Modulo 66

66. Las propiedades con `@property` permiten acceder a métodos como si fueran atributos, habilitando lógica controlada en accesos y asignaciones.

## Modulo 67

67. Python soporta la orientación a eventos, común en interfaces gráficas o programación asincrónica.

## Modulo 68

68. Los módulos `time` y `datetime` permiten medir tiempos, convertir formatos y realizar cálculos con fechas.

## Modulo 69

69. Las clases abstractas se definen con `abc.ABC` y `@abstractmethod`, asegurando que subclases implementen ciertos métodos.

## Modulo 70

70. El módulo `enum` permite crear enumeraciones que agrupan constantes con nombres semánticos.

## Modulo 71

71. El módulo `pathlib` ofrece una interfaz orientada a objetos para trabajar con rutas y archivos.

## Modulo 72

72. El módulo `typing` introduce tipos genéricos como `List[str]`, `Dict[str, int]` y `Union[int, None]` para mejorar la claridad del código.

## Modulo 73

73. El método `__slots__` permite definir atributos fijos en una clase y reduce el consumo de memoria al evitar diccionarios de atributos.

## Modulo 74

74. El patrón singleton asegura que solo exista una instancia de una clase, útil en controladores o registros globales.

## Modulo 75

75. Los mixins son clases diseñadas para ser combinadas con otras clases, aportando funcionalidad sin herencia completa.

## Modulo 76

76. Python permite sobrecargar funciones usando módulos como `functools.singledispatch`, útil para cambiar comportamiento según el tipo de argumento.

## Modulo 77

77. El módulo `concurrent.futures` facilita la programación concurrente con `ThreadPoolExecutor` y `ProcessPoolExecutor`.

## Modulo 78

78. Python soporta programación asíncrona con `async def`, `await`, y el módulo `asyncio`, útil para tareas I/O concurrentes.

## Modulo 79

79. Un `event loop` ejecuta tareas asíncronas en Python, controlando su orden y esperando por operaciones no bloqueantes.

## Modulo 80

80. La palabra clave `await` suspende la ejecución de una función asíncrona hasta que se complete una tarea, sin bloquear el hilo.

## Modulo 81

81. Python permite trabajar con sockets para construir servidores y clientes TCP/IP de bajo nivel.

## Modulo 82

82. El módulo `requests` facilita el consumo de APIs REST y la gestión de peticiones HTTP.

## Modulo 83

83. `contextlib.suppress()` ignora ciertas excepciones dentro de un bloque, evitando múltiples `try-except` anidados.

## Modulo 84

84. Python permite extender tipos integrados creando subclases de `list`, `dict` u otros tipos para personalizar comportamiento.

## Modulo 85

85. El módulo `hashlib` permite calcular hashes seguros como SHA-256 o MD5, útiles para verificar integridad de datos.

## Modulo 86

86. El módulo `uuid` permite generar identificadores únicos universales (UUID), usados comúnmente como claves en sistemas distribuidos.

## Modulo 87

87. El módulo `secrets` ofrece funciones seguras para generar contraseñas o tokens aleatorios, preferido sobre `random` para propósitos criptográficos.

## Modulo 88

88. `heapq` proporciona una implementación eficiente de colas con prioridad (min-heaps), útil en algoritmos como Dijkstra.

## Modulo 89

89. Python soporta el patrón observer usando callbacks o bibliotecas como `Observable` para aplicaciones reactivas.

## Modulo 90

90. Los decoradores pueden aceptar argumentos si están definidos como funciones que retornan decoradores.

## Modulo 91

91. Las pruebas parametrizadas en `pytest` permiten ejecutar una misma prueba con diferentes entradas, aumentando la cobertura.

## Modulo 92

92. Las fixtures en `pytest` inicializan recursos reutilizables antes de ejecutar las pruebas, como conexiones o datos.

## Modulo 93

93. Python permite importar código dinámicamente con `__import__()` o `importlib`, útil para plugins o extensiones.

## Modulo 94

94. El patrón fábrica (`factory`) encapsula la lógica de creación de objetos, promoviendo la separación entre lógica y construcción.

## Modulo 95

95. El patrón decorador permite añadir comportamiento a objetos en tiempo de ejecución, útil en diseño flexible de aplicaciones.

## Modulo 96

96. El uso de `assert` en pruebas ayuda a validar condiciones que deben cumplirse durante la ejecución.
