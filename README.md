### 1.Você consegue identificar alguma redundância nos códigos (dentro de uma mesma classe ou em classes diferentes)?
Nessas classes(Professor e estudantes) compartilham de atributos com o mesmo significado como por exemplo name e userId,
sendo estes compartilhados por ambas classes. Os metódos de get e set desses atributos também acabam por ser redundantes. Sendo mais
eficiente nesse caso o uso de herança.

### 2.O que aconteceria se fosse necessário armazenar outros atributos sobre estudantes e professores? (por exemplo, CPF, data de nascimento, telefone, etc?)
Seria necessário implementar mais funções de get e set para esses atributos em ambos as classes, isso acabaria em aumentar a redundância
de funções nas classes como também dimunuir a capacidade de otimização.

### 3.0 O que aconteceria na classe Laboratory se tivéssemos outras categorias de membros além de estudantes e professores (técnicos, administradores, etc.)?
Caso houver o aumento no número de categorias, seria necessário aumentar a quantidade de funções de addMember, além de implementar novos
laços dentro das demais funções para percorrer os demais ArrayList<Type> que seriam inseridos.
