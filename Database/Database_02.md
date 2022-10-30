## Extra Key? (外键)

in student table, students belong different class.
A classes has many students, it is one to multi in two tables with the realtionship.

## ono to one 
every studen have own contact, so we create a "contacts" table. 
But why do not directly add a column for original table. 
Because Some student possiblaly have no mobile contact, actually the conteacts table to student within one to one relationship.
The other point is separate two table to purpose figure out some often read or not often read.