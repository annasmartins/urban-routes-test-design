# Casos de Teste - Campo "Nome"

## TC-01 - O campo "Nome" deve aceitar nomes com letras latinas
**Pré-condição:** O formulário para solicitar um serviço de compartilhamento de carro está aberto.  
**Passos:**
1. Clique no botão "Adicionar carteira de motorista".
2. Preencha o campo "Nome" com o valor "Anna".
3. Remova o foco do campo "Nome" clicando fora dele.

**Resultado esperado:** Não deve haver mensagem de erro no campo "Nome".

---

## TC-02 - O campo "Nome" deve aceitar nomes com um espaço
**Pré-condição:** O formulário para solicitar um serviço de compartilhamento de carro está aberto.  
**Passos:**
1. Clique no botão "Adicionar carteira de motorista".
2. Preencha o campo "Nome" com o valor "João Silva".
3. Remova o foco do campo "Nome" clicando fora dele.

**Resultado esperado:** Não deve haver mensagem de erro no campo "Nome".

---

## TC-03 - O campo "Nome" deve aceitar nomes com um hífen
**Pré-condição:** O formulário para solicitar um serviço de compartilhamento de carro está aberto.  
**Passos:**
1. Clique no botão "Adicionar carteira de motorista".
2. Preencha o campo "Nome" com o valor "Lais-Carla".
3. Remova o foco do campo "Nome" clicando fora dele.

**Resultado esperado:** Não deve haver mensagem de erro no campo "Nome".

---

## TC-04 - O campo "Nome" deve aceitar nomes com 2 caracteres
**Pré-condição:** O formulário para solicitar um serviço de compartilhamento de carro está aberto.  
**Passos:**
1. Clique no botão "Adicionar carteira de motorista".
2. Preencha o campo "Nome" com o valor "Ab".
3. Remova o foco do campo "Nome" clicando fora dele.

**Resultado esperado:** Não deve haver mensagem de erro no campo "Nome".

---

## TC-05 - O campo "Nome" deve aceitar nomes com 14 caracteres
**Pré-condição:** O formulário para solicitar um serviço de compartilhamento de carro está aberto.  
**Passos:**
1. Clique no botão "Adicionar carteira de motorista".
2. Preencha o campo "Nome" com o valor "Marcillianno".
3. Remova o foco do campo "Nome" clicando fora dele.

**Resultado esperado:** Não deve haver mensagem de erro no campo "Nome".

---

## TC-06 - O campo "Nome" não deve aceitar nomes com menos de 2 caracteres
**Pré-condição:** O formulário para solicitar um serviço de compartilhamento de carro está aberto.  
**Passos:**
1. Clique no botão "Adicionar carteira de motorista".
2. Preencha o campo "Nome" com o valor "A".
3. Remova o foco do campo "Nome" clicando fora dele.

**Resultado esperado:** O campo deve ficar marcado em vermelho e a mensagem "Insira um nome correto" deve aparecer.

---

## TC-07 - O campo "Nome" não deve aceitar nomes com mais de 14 caracteres
**Pré-condição:** O formulário para solicitar um serviço de compartilhamento de carro está aberto.  
**Passos:**
1. Clique no botão "Adicionar carteira de motorista".
2. Preencha o campo "Nome" com o valor "MarcilliannoSouza".
3. Remova o foco do campo "Nome" clicando fora dele.

**Resultado esperado:** O campo deve ficar marcado em vermelho e a mensagem "Insira um nome correto" deve aparecer.

---

## TC-08 - O campo "Nome" não deve aceitar nomes com dois espaços
**Pré-condição:** O formulário para solicitar um serviço de compartilhamento de carro está aberto.  
**Passos:**
1. Clique no botão "Adicionar carteira de motorista".
2. Preencha o campo "Nome" com o valor "João  Silva".
3. Remova o foco do campo "Nome" clicando fora dele.

**Resultado esperado:** O campo deve ficar marcado em vermelho e a mensagem "Insira um nome correto" deve aparecer.

---

## TC-09 - O campo "Nome" não deve aceitar nomes com dois hífens
**Pré-condição:** O formulário para solicitar um serviço de compartilhamento de carro está aberto.  
**Passos:**
1. Clique no botão "Adicionar carteira de motorista".
2. Preencha o campo "Nome" com o valor "Anna--Maria".
3. Remova o foco do campo "Nome" clicando fora dele.

**Resultado esperado:** O campo deve ficar marcado em vermelho e a mensagem "Insira um nome correto" deve aparecer.

---

## TC-10 - O campo "Nome" não deve aceitar nomes com espaço e hífen juntos
**Pré-condição:** O formulário para solicitar um serviço de compartilhamento de carro está aberto.  
**Passos:**
1. Clique no botão "Adicionar carteira de motorista".
2. Preencha o campo "Nome" com o valor "Anna -Maria".
3. Remova o foco do campo "Nome" clicando fora dele.

**Resultado esperado:** O campo deve ficar marcado em vermelho e a mensagem "Insira um nome correto" deve aparecer.

---

## TC-11 - O campo "Nome" não deve aceitar nomes contendo números
**Pré-condição:** O formulário para solicitar um serviço de compartilhamento de carro está aberto.  
**Passos:**
1. Clique no botão "Adicionar carteira de motorista".
2. Preencha o campo "Nome" com o valor "Anna1".
3. Remova o foco do campo "Nome" clicando fora dele.

**Resultado esperado:** O campo deve ficar marcado em vermelho e a mensagem "Insira um nome correto" deve aparecer.

---

## TC-12 - O campo "Nome" não deve aceitar nomes com caracteres especiais
**Pré-condição:** O formulário para solicitar um serviço de compartilhamento de carro está aberto.  
**Passos:**
1. Clique no botão "Adicionar carteira de motorista".
2. Preencha o campo "Nome" com o valor "Ann@".
3. Remova o foco do campo "Nome" clicando fora dele.

**Resultado esperado:** O campo deve ficar marcado em vermelho e a mensagem "Insira um nome correto" deve aparecer.

---

## TC-13 - O campo "Nome" não pode estar em branco
**Pré-condição:** O formulário para solicitar um serviço de compartilhamento de carro está aberto.  
**Passos:**
1. Clique no botão "Adicionar carteira de motorista".
2. Deixe o campo "Nome" vazio.
3. Remova o foco do campo "Nome" clicando fora dele.

**Resultado esperado:** O campo deve ficar marcado em vermelho e a mensagem "Insira um nome correto" deve aparecer.

---

## TC-14 - O campo "Nome" não deve aceitar nomes com letras não latinas
**Pré-condição:** O formulário para solicitar um serviço de compartilhamento de carro está aberto.  
**Passos:**
1. Clique no botão "Adicionar carteira de motorista".
2. Preencha o campo "Nome" com o valor "ぁあせぱばぱみ".
3. Remova o foco do campo "Nome" clicando fora dele.

**Resultado esperado:** O campo deve ficar marcado em vermelho e a mensagem "Insira um nome correto" deve aparecer.
