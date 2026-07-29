--- Registro de Bugs ---

## BUG001 - Imagens de produtos incorretas (problem_user)
**Usuário utilizado:** problem_user

**Passos para reproduzir:**
1. Fazer login com problem_user / secret_sauce
2. Observar a lista de produtos

**Resultado esperado:** Cada produto deve exibir sua imagem correta (RF006).

**Resultado atual:** Todos os produtos exibem a mesma imagem (foto de um cachorro).

---

## BUG002 - Página "About" retorna erro 404 (problem_user)
**Usuário utilizado:** problem_user

**Passos para reproduzir:**
1. Fazer login com problem_user / secret_sauce
2. Abrir menu lateral (hambúrguer)
3. Clicar em "About"

**Resultado esperado:** Deve abrir a página institucional do site (RF005).

**Resultado atual:** Retorna erro 404 "Página não encontrada".

---

## BUG003 - Página de finalização de compra nao retorna a mensagem "Thank you for your order!" e se mantem branca (problem_user)
**Usuário utlizado:** problem_user

**Passos para reproduzir:**
1. Fazer login com problem_user / secret_sauce
2. Adicionar um produto ao carrinho
3. Clicar no "carrinho"
4. Clicar em "confira"
5. Adicionar as informações pessoais
6. Clicar em "Continuar"

**Resultado esperado:** Retorna mensagem "Thank you for your order!" confirmando a compra (RF004).

**Resultado atual:** Retorna página em branco e não finaliza a compra.

---

## BUG004 - Página de finalização de compra não retorna a mensagem "Thank you for your order!" e se mantém branca (error_user)
**Usuário utilizado:** error_user

**Passos para reproduzir:**
1. Fazer login com error_user / secret_sauce
2. Adicionar um produto ao carrinho
3. Clicar no "carrinho"
4. Clicar em "confira"
5. Adicionar as informações pessoais
6. Clicar em "Continuar"

**Resultado esperado:** Retorna mensagem "Thank you for your order!" confirmando a compra (RF004).

**Resultado atual:** Retorna página em branco e não finaliza a compra.

**Observação:** Mesmo comportamento identificado no problem_user (BUG003),
sugerindo que a falha pode estar relacionada a uma validação compartilhada no fluxo
de checkout, e não a um usuário específico.
