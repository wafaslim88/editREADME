# editREADME
ALGORITHM read_sentence
VAR
    nc:INTEGER:=0;// numbre of characters
    nw:INTEGER:=0;//numbre of words
    nv:INTEGER:=0;//numbre of vowels
WHILE (read_char <>".") DO
    nc=nc+1

IF (read_char <>" ") THEN
    nw=nw
ELSE
    nw=nw+1
END_IF
IF (read_char <>"a") THEN
    nv=nv
ELSE
    nv=nv+1
END_IF
IF (read_char <>"e") THEN
    nv=nv
ELSE
    nv=nv+1
END_IF
IF (read_char <>"i") THEN
    nv=nv
ELSE
    nv=nv+1
END_IF
IF (read_char <>"o") THEN
    nv=nv
ELSE
    nv=nv+1
END_IF
IF (read_char <>"u") THEN
    nv=nv
ELSE
    nv=nv+1
END_IF
IF (read_char <>"y") THEN
    nv=nv
ELSE
    nv=nv+1
END_IF
END_WHILE 
