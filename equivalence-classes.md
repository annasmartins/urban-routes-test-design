# Classes de Equivalência - Urban Routes

## Campo: Nome

### Classes válidas
- Letras latinas, com ou sem espaço e hífen, entre 2 e 14 caracteres
- Letras latinas com espaço
- Letras latinas com hífen

### Exemplos válidos
- Anna
- João Silva
- Lais-Carla
- Anna Maria
- Luis-Paulo

### Classes inválidas
- Menos de 2 caracteres
- Mais de 14 caracteres
- Mais de um espaço
- Mais de um hífen
- Espaço e hífen juntos
- Contendo números
- Com caracteres especiais
- Campo vazio
- Letras não latinas

### Exemplos inválidos
- A
- MarcilliannoSouza
- João  Silva
- Anna--Maria
- Anna -Maria
- Anna1
- Ann@
- ぁあせぱばぱみ

---

## Campo: Sobrenome

### Classes válidas
- Letras latinas, com ou sem espaço e hífen, entre 2 e 14 caracteres
- Letras latinas com espaço
- Letras latinas com hífen

### Exemplos válidos
- Silva
- Santos Martins
- Santos-Martins
- Dias Neto
- Souza-Silva

### Classes inválidas
- Menos de 2 caracteres
- Mais de 14 caracteres
- Mais de um espaço
- Mais de um hífen
- Espaço e hífen juntos
- Contendo números
- Com caracteres especiais
- Campo vazio
- Letras não latinas

### Exemplos inválidos
- S
- SouzaSilvaBarreto
- Dias  Neto
- Dias--Neto
- Dias -Neto
- Di4s
- Di@s
- ぁあせぱばぱみ

---

## Campo: Data de nascimento

### Classes válidas
- Data no formato dd.mm.aaaa
- Dia entre 01 e 31
- Mês entre 01 e 12
- Ano entre 1880 e 2006
- Data válida em ano bissexto

### Exemplos válidos
- 15.03.1990
- 01.01.2000
- 31.12.1985
- 29.02.2004
- 29.02.2000

### Classes inválidas
- Dia menor que 01
- Dia maior que 31
- Mês menor que 01
- Mês maior que 12
- Ano menor que 1880
- Ano maior que 2006
- 29 de fevereiro em ano não bissexto
- Data com barras
- Data com letras ou símbolos
- Campo vazio

### Exemplos inválidos
- 00.03.1990
- 32.03.1990
- 15.00.1990
- 15.13.1990
- 15.03.1879
- 15.03.2007
- 29.02.2003
- 29.02.1901
- 15/03/1990
- 05.jan.1990
- 05@01#1990
