# virussimulation
(this is my term project )
In this Project You will simulate a laboratory experiment as a life game. You have a habitat that
contains randomly distributed entities. In our experiment our habitat will be a NxN square place.
Each entity has 5 different gates which can be named from { A,B,C,D,E,F,G,H } set.
The Spreading V can infect an entity if the entity has A or B gate. If the entity has 3 gates which are
named as A,B,C,D than this entity will die after 14 turns otherwise it will recover and get immune to
Spreading V. after 30 turns. Dead entities stay in habitat for five turns and be infectious. They can not
move.
Spreading V can infect from one entity to other if they are closer than 3 units (in square form). An
entity becomes infectious after 3 turn.
Your simulation will take the start information from input.txt file which will be on the same file with
you executable. This file include information about habitat constants, entities and their movements
in turns.
Your simulation will write an output.txt file which will show the infected and died entities and last
situation of the habitat. Also, after each turn you will fill another file “turns.txt”. This file shows a
brief outcome for each turn.
An example of the input and output files are below: We have a 5x5 habitat and includes 3 entity in
this example. İt is a short description so the movements are made just for three steps. Test case
should be made for more turns. Since our habitat is to small and each entity is close to each other
infected entity can easily infect the others. But the infection will occur after 3 turns so we do not see
any infection in three turns. “X” shows infected entities, “O” for healthy entities, “D” for dead ones.
Your application must not include any console input command. Your app directly read the input file,
generate output.txt and turns.txt files and close itself silently. 
