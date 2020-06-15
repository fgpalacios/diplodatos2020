# diplodatos2020
En este repositorio vamos a dejar toda la información necesaria para llevar adelante todos los trabajos de la mentoría.

![](https://github.com/fgpalacios/diplodatos2020/blob/master/graph.png)

## Dataset
El dataset provisto posee dos archivos.
### nodes.csv
Posee los siguientes campos:
* n.id: identificador del nodo	
* name_node_a: nombre del nodo
* n.type: tipo del nodo pueden ser:
	* person: indica que la informacion del nodo es una persona. Los datos vinculados a una persona son:
		* gender: sexo de la persona
		* age: edad de la persona
		* category: nivel de experiencia
		* experience: años de experiencia
	* technologies: indica que la informacion del nodo es una tecnologia (o grupo de tecnologías)
	* skill: indica que la informacion del nodo es un perfil de trabajo
	* team: indica que la informacion del nodo es equipo que está compuesto por personas.
* n.category: nivel de experiencia
* n.gender: sexo de la persona
* n.age: edad de la persona
* n.experience: años de experiencia

### relationships.csv
Posee los siguientes campos:
* id_node_a: identificador del nodo de origen
* name_node_a: nombre del nodo de origen
* id_node_b: identificador del nodo de destino
* name_node_b: nombre del nodo de destino
* id_relationship: identificador de la relación
