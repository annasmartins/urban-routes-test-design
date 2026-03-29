# Valores-Limite - Urban Routes

## Campo: Nome
Regra: aceitar entre 2 e 14 caracteres.

### Limites válidos
- 2 caracteres: `Ab`
- 14 caracteres: `Marcillianno`

### Limites inválidos
- Abaixo do mínimo: `A`
- Acima do máximo: `MarcilliannoSouza`

### Observações
Também foram considerados cenários inválidos com:
- dois espaços
- dois hífens
- espaço e hífen juntos
- números
- caracteres especiais
- campo vazio
- letras não latinas

---

## Campo: Sobrenome
Regra: aceitar entre 2 e 14 caracteres.

### Limites válidos
- 2 caracteres: `Bi`
- 14 caracteres: `Maximilianos`

### Limites inválidos
- Abaixo do mínimo: `S`
- Acima do máximo: `SouzaSilvaBarreto`

### Observações
Também foram considerados cenários inválidos com:
- dois espaços
- dois hífens
- espaço e hífen juntos
- números
- caracteres especiais
- campo vazio
- letras não latinas

---

## Campo: Data de nascimento
Regra: aceitar datas válidas no formato dd.mm.aaaa, com ano entre 1880 e 2006.

### Limites válidos
- Menor ano permitido: `01.01.1880`
- Maior ano permitido: `31.12.2006`

### Limites inválidos
- Ano abaixo do mínimo: `15.03.1879`
- Ano acima do máximo: `15.03.2007`
- Dia abaixo do mínimo: `00.03.1990`
- Dia acima do máximo: `32.03.1990`
- Mês abaixo do mínimo: `15.00.1990`
- Mês acima do máximo: `15.13.1990`

### Casos especiais
- Data válida em ano bissexto: `29.02.2004`, `29.02.2000`
- Data inválida em ano não bissexto: `29.02.2003`, `29.02.1901`
