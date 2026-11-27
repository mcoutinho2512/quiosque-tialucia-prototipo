# Quiosque Tia Lúcia — protótipo de site

Proposta de site novo feita pela MC Consultoria em TI. O quiosque não tem site hoje; a presença online é só o Instagram (@quiosque_tialucia) e a ficha do Google.

Protótipo: https://mcoutinho2512.github.io/quiosque-tialucia-prototipo/

## Arquivos

- `index.html` — site completo (HTML, CSS e JS no mesmo arquivo, sem framework)
- `img/` — fotos do protótipo, tiradas do Instagram do próprio quiosque
- `robots.txt` — bloqueia indexação (é protótipo)

## Antes de publicar de verdade

1. Remover `<meta name="robots" content="noindex, nofollow">`, a faixa "Protótipo" (`.proto`) e trocar o `robots.txt` por `Allow: /` com o sitemap.
2. Trocar o domínio no `canonical`, no `og:url`/`og:image` e no JSON-LD.
3. Substituir as fotos pelas da sessão de fotos (as do Instagram são verticais e comprimidas). Arquivos usados:
   - `hero.jpg` (deck ao pôr do sol), `logo.jpg`, `placa.jpg` ("Desde 1982"), `peixe-frito.jpg`, `petiscos.jpg`, `drink.jpg`, `manha.jpg`
   - `evento-casamento.jpg`, `evento-bolo.jpg`, `evento-aniversario.jpg`, `evento-buffet.jpg`
   - `deck.jpg`, `kids.jpg`, `musica.jpg`, `por-do-sol.jpg`
4. Pedir o logo em vetor (SVG ou PDF). Hoje só existe a versão do avatar do Instagram.

## Confirmar com o cliente

- **Horário:** o Google diz 8h–19h todos os dias; o cardápio impresso diz 9h–19h. O café da manhã (Nina Gourmet) é sábado e domingo, 8h–11h.
- **Endereço:** o Google mostra "Praia de Camboinhas, 13"; um post do Instagram mostra "Av. Beira-Mar, 13". Usamos Av. Beira-Mar, 13, CEP 24320-330.
- **WhatsApp:** (21) 99537-8586 para reservas, eventos e pedidos. É o mesmo número para tudo?
- **História:** só sabemos "desde 1982" (placa). Pedir a história da Tia Lúcia, fotos antigas e marcos para a linha do tempo.
- **Cardápio:** transcrito das fotos do cardápio impresso no Google Maps. Conferir preços, e:
  - "APERITIVOS" aparece duas vezes no impresso (separamos em "Entradas" e "Petiscos");
  - nomes de cerveja escritos errado no impresso ("Eisenban", "Estrela / Galácia") — corrigidos para Eisenbahn e Estrella Galicia;
  - "Shot de limão R$ 3,60" — confirmar valor;
  - não há drinks/caipirinhas no impresso atual (existe destaque "Drinks" no Instagram) — pedir lista e preços;
  - "Jarra de suco de natural" — corrigido.
- **iFood:** o link do Google Maps aponta para uma loja do iFood que não existe mais. Remover da ficha do Google ou reativar.
- **Música ao vivo:** frequência real (fins de semana? só datas especiais?).
- **Réveillon:** o deste ano foi cancelado; o site não menciona Réveillon.
- **Reservas do café da manhã:** o botão aponta para o Linktree da Nina Gourmet. Confirmar se querem assim.
- **Pagamento:** cardápio mostra Mastercard, Visa e Elo. Aceitam PIX?
