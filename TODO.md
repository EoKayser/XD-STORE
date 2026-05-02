# TODO - Melhorias Funcionais XD Store (Aprovado)

## ✅ Status: Em Andamento
**Foco**: Refatorar funcionalidades (carrinho, busca, UX) sem quebrar design

## 1. Criar TODO.md [✅ CONCLUÍDO]
- [x] Arquivo criado com plano detalhado

## 2. Refatorar js/store.js [✅ CONCLUÍDO]
- [x] Expandir API (coupons expiração, getProductPrice)
- [x] Validação robusta (stock, disabled)
- [x] Eventos dispatchCartUpdate()
- [x] Teste: addToCart com promo real-time
- [ ] Expandir API (coupons, validação disabled)
- [ ] Export types/autocomplete  
- [ ] Teste unitário addToCart/updateQuantity

## 3. Melhorar js/ui.js [✅ CONCLUÍDO]
- [x] ESC fecha carrinho ✅
- [x] Persistir busca/filtro localStorage ✅
- [x] Loading skeletons ✅
- [ ] Mobile swipe (próxima)
- [ ] Disabled states melhor
- [ ] ESC fecha carrinho
- [ ] Persistir busca/filtro localStorage
- [ ] Loading skeletons produtos
- [ ] Mobile swipe gestures carrinho
- [ ] Better disabled states

## 4. Refatorar templates produtos [✅ CONCLUÍDO]
- [x] Remover JS inline (3 templates principais)
- [x] data-product-id auto-detect
- [x] setupProductPage() com variações support
- [x] Related products centralizado
- [ ] Remover JS inline (discord-nitro.html, valorant-mista.html, etc.)
- [ ] Usar window.setupProductPage(productId)
- [ ] Related products únicos

## 5. pages/checkout.html [✅ CONCLUÍDO]
- [x] Validação carrinho vazio (gera mensagem de erro)
- [x] QR Code com valor do carrinho (drawQr mostra valor abaixo do QR)
- [x] Cores forçadas no QR (tema claro/escuro não afeta)
- [x] Copy buttons UX melhor

## Testes Finais [PENDENTE]
- [ ] Teste carrinho completo mobile/desktop
- [ ] Lighthouse Performance antes/depois
- [ ] Deploy local teste

**Próximo: js/store.js → js/ui.js → templates**

