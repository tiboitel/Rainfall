## Helpfull command.

ESP = Stack pointer.
EBP = Current stack frame.
mov met la valeur de droite dans la valeur de gauche.

### ASM Syntax

`mov %eax, %esp
mov %eax, (%esp)`

Le premier met eax dans esp.
Le second met eax a l'adresse pointe par esp.

C:
`esp = eax 
*esp = eax`

mov 0x4(%esp), %eax

Decale le pointeur esp de 4 puis stock %eax dedans.

Permet d'ajouter 0x4 au pointer de la stack pour le decaler.

pdisas <function_name>
b* address
telescope
