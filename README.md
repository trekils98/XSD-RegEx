# XSD-RegEx
Validación de XML con XSD y Expresiones Regulares

Explicacion restricciones: 

email: [a-zA-Z0-9._%+-]{1,64}@[a-zA-Z0-9.-]+\.[a-zA-Z]{2,63}
en la parte delante del @ se pueden poner letras en minusculam mayuscula,numeros y %+-, minimo un caracter, maximo 64 caracteres
despues del @ puedes poner letras en minusculam mayuscula,numeros y ._ ; sin limite de espacio. despues obligatoriamente un punto
y despues del . letras en minuscula y mayuscula como maximo de 63 caracteres

telefono: \+34\s\d{3}[-\s]\d{3}[-\s]\d{3}
al principio +34 obligatorio, 9 numeros separados por un espacio o por -

codigoPostal: [0-5][0-9]\d{3}
los dos primeros numeros van del 0-59 que son los españoles y despues 3 digitos mas dependiendo de la zona

nombreUsuario: [a-z][a-zA-Z0-9_\-]{4,29}
el primer caracter es una letra en minuscula y el resto una letras miniscula o mayuscula, un numero o un simbolo basico(_-)
minimo 5 caracteres, maximo 30

contrasena: [A-Za-z0-9 !#$%()*+,\-.:;=?@\[\]^_`{|}~]{8,}
la contraseña puede tener una letra, un numero o cualquier simbolo; minimo 8 caracteres, sin limite maximo

