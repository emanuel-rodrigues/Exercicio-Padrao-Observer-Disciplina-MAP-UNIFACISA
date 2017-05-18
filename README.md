# ExercicioObserver

Com relação ao código proposto em: https://sourcemaking.com/design_patterns/observer/java/1 uma das diferenças do exemplo apresentado em sala é que a classe Subject não é abstrata e ao criar um objeto do tipo Observer ele automaticamente já é adicionado a lista de Observers do Subject.
E com relação ao artigo de Event Aggregator eu entedi que seria um canal (Um Objeto) que agrega vários objetos observáveis em um único lugar com a intenção de evitar que observers tenham relação com mais de um subject já que os observáveis estariam em um único lugar.
