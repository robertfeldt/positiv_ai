# Exempel: nyansera ett argument om "inkrökthet"

Det här exemplet visar skillen [`nyansera`](../../skills/nyansera/) tillämpad på ett verkligt argument ur introtexten till Backåkraseminariet 2026 — ett samtal mellan kultur, forskning, näringsliv, politik och kyrka i Dag Hammarskjölds anda.

## Innehåll

| Fil | Innehåll |
|---|---|
| `INPUT.md` | Argumentet som prövas, ordagrant så som det matades in |
| `OUTPUT.md` | Skillens fullständiga output, oredigerad |

## Argumentet som prövas

> Den psykiska ohälsa och känsla av meningslöshet som många, inte minst unga, vittnar om kan förstås i ljuset av en tilltagande "inkrökthet" (incurvatus in se) i den egna privatsfären och det egna jaget — kontinuerligt förstärkt av de sociala mediernas algoritmer.

Argumentet valdes för att det är genuint och aktuellt (det formar ett verkligt seminariesamtal), gör ett prövbart kausalt anspråk, och har rika, verkliga motperspektiv — alltså ett ärligt testfall, inte ett tillrättalagt.

## Hur outputen producerades

En körning av `SKILL.md`-instruktionerna i en agentisk miljö (Claude Code, modell Fable 5), utan efterredigering. Notera att skillen prövar argumentet *på dess egna villkor* — outputen är inte en sågning utan en vidgning: argumentets kärna ska överleva i nyanserad form om den håller.

## Vad exemplet visar (katalogens tre frågor)

1. **Öppnar utåt:** outputen ger den som *håller* argumentet fem blickar utifrån — inklusive de ungas egen, som oftast saknas i diagnoser av unga — och slutar med vad som borde få en att ändra sig.
2. **Designval:** kraven i skillen (verkliga skillnadsaxlar, sällan hörd röst, annan tidshorisont, ideologiskt Turing-test, steelman) syns direkt i outputens struktur.
3. **Prövbarhet:** jämför själv — klistra in samma argument i en chatt med bara frågan "vad tycker du om det här argumentet?" och se skillnaden mot den strukturerade prompten.
