# IngSoft

#Software development life cicle
-Ciclo de vida del desarrollo de software (SDLC) conjunto de actividades y resultados asociados que producen un producto de software.
Tiene 5 fases: analisis de requerimientos, diseño, implementacion, testing y evolucion.

#Carta Gant no es para software#

-Metodo Cascada (solo a un lado)
-Modelo V (lo mismo del anterior, pero doble, se verifica cada etapa)
-Modelo Prototipado: Pequeñas versiones incompletas para discutir con el cliente (No es funcional, solamente para discucion), se puede meter en cualquier etapa de los modelos anteriores, es mejor para visualizar y extraer requisitos.
  ·Prototipo desechable: se descartan en cada reunión (uso comun de pototipo)
  ·prototipos evolutivos: se le agregan cosas a cada rato, mediante retroalimentacion de usuario
  ·Prototipo Incremental: de construyen prototipos separados y al final se juntan
  ·Prototipo Extremo (orientado a Web)
  
-Modelo Espiral: Mezcla de prototipo y cascada, cada parte tiene un analisis de riesgo(tienen puntajes de riesgo) y un prototipo; es ciclica. Uso habitual para grandes proyectos. 
-Modelo Iterativo e Incremental:avanza de a poco en el proyecto (cada parte debe ser funcional), no se entrega nada hasta que todo este listo.
Modelo Agil: Basado en el anterior, maximiza la colaboracion entre equipos inter-funcionales (desorden admitido y aceptado, generalmente al no tener modelo es agil)
Pasamos a
->Sistema de Informacion Hospitalaria.
Tipos de modelo en informacion hospitalaria
*Control para avanzar


**PATRON: MEDIATOR

-----------------------------------------

Toma de requerimientos **


-------------------------------------------

Casos de Uso

Es la representacion de un requerimiento, no tiene que ser simple**, debe tener un flujo dentro de el

el nombre requiere un VERBO en infinitivo (no analizar (Muy Ambiguo), en este caso seria Generar Reporte), una accion!
Tipos de escenarios en casos de uso: - normal:Selecciona un producto y paga (Simple y exitoso)
                                     - alternativo: ***, que pasa si* (relevante)
  
  Actores: personas o sistemas que interactuan con mi sistema (cajeros, personas, transbank, redes sociales)
          -Son roles, no nombres y en singular (Ejemplo:Administrador (No administradores o juan perez)
          
          (UML y patrones, Larman. Buscar casos de uso)
          
Usar voz activa, no pasiva (que sea mas directo)  


Include obligatorio, extend opcional

Include CU-> CU
extend CU<- CU

**Un caso de uso debe ser observable por el usuario!
        
