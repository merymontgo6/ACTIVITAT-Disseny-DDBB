# ACTIVITAT-Disseny-DDBB

![ddbb](https://github.com/user-attachments/assets/a7e4fd9b-7fb1-46db-8f05-82ba03cdf00c)

#### Festival - Recinte (Composició)
Es tracta d'una composició, ja que un Festival conté diversos Recintes, i si el Festival es cancel·la, tots els Recintes associats queden inactius per a aquest festival.

#### Festival - Carrer (Composició)
La zona d’acampada del Festival inclou diversos Carrers, que desapareixen si es cancel·la el festival.

#### Recinte - Concert (Associació)
Cada Recinte alberga múltiples Concerts, que es vinculen amb recintes específics per a la programació del festival.

#### Grup - Concert (Associació)
Un Concert és realitzat per un Grup, i la relació indica l'assignació específica per actuació.

#### Concert - Substitució (Dependència)
Cada Concert depèn de la disponibilitat de grups substituts, assegurant la continuïtat en cas de cancel·lació d'un grup.

#### Carrer - Parcel·la (Dependència)
Els Carrers agrupen diverses Parcel·les. La modificació o afegit d’una Parcel·la no afecta el Carrer.

#### Persona - Lloguer (Associació)
Cada Persona pot llogar una única Parcel·la a la zona d’acampada, amb la qual manté una relació d'ús exclusiva.

#### Persona - Accés (Dependència)
Els registres d’Accés registren els moviments de cada Persona, que tenen llibertat d'entrada i sortida.

#### Persona - Parcel·la (Dependència/Associació)
Les Parcel·les llogades depenen de l'existència d'una Persona com a responsable de l'ús.
