# Skill: nyansera

Bredda och nyansera ett argument, en utgångspunkt eller ett perspektiv — och hitta alternativa sätt att se "det/dem". Du får tillbaka: din kärna välvilligt återgiven, dolda antaganden, 4–5 genuint olika perspektiv, det starkaste motargumentet steelmannat, och en nyanserad omformulering som slutar med "vad skulle få dig att ändra dig?".

Målet är att **se mer, inte tycka mindre**.

## Filer

| Fil | Användning |
|---|---|
| `SKILL.md` | För agentiska miljöer (Claude Code, pi, Codex, opencode, m.fl.) |
| `PROMPT.md` | Fristående copy-paste-prompt för valfri AI-chatt (svenska) |
| `PROMPT_en.md` | Samma, på engelska |

## Installation och användning

**Agentiska miljöer.** `SKILL.md` är vanlig markdown med ett kort frontmatter (`name`, `description`) och fungerar i alla miljöer som läser skills/commands i markdownformat:

- *Claude Code*: kopiera katalogen till `~/.claude/skills/nyansera/` (eller projektets `.claude/skills/`), anropa med `/nyansera`.
- *pi*: samma SKILL.md-format; lägg i din skills-katalog.
- *Codex CLI*: spara innehållet som `~/.codex/prompts/nyansera.md`, anropa med `/nyansera`.
- *opencode*: lägg som custom command (se din versions dokumentation, t.ex. `~/.config/opencode/command/nyansera.md`).
- *Annan miljö*: peka på filen eller klistra in dess innehåll — instruktionerna är självbärande.

**Utan agentisk miljö.** Kopiera innehållet i `PROMPT.md` (eller `PROMPT_en.md`), klistra in i ChatGPT, Claude, Gemini eller annan chatt, och lägg din text sist. Funkar på en debattartikel, ett forskningsantagande, ett styrelsebeslut eller en familjediskussion.

## Katalogens tre frågor

1. **Öppnar det utåt?** Ja — outputen är andras blickar på din fråga plus kvalificerat motstånd mot din egen position. Skillen optimerar för perspektivskillnad och omprövning, inte för bekräftelse eller engagemang.
2. **Vilket designval?** En tvingande promptstruktur: perspektiven måste skilja sig längs verkliga axlar (värden, tidshorisont, levd erfarenhet, makt), minst en sällan hörd röst och en annan tidshorisont måste ingå, varje gestaltning måste klara ett ideologiskt Turing-test (innehavaren ska känna igen sig), motargumentet måste steelmannas — och smicker, falsk balans och påhittade källor är uttryckligen förbjudna.
3. **Vilken evidens?** Prövbar på tre sätt: (a) före/efter — nyanserar användare faktiskt sin position?; (b) gestaltningskvalitet — känner företrädare för perspektiv X igen sig?; (c) jämförelse mot en ostrukturerad baslinje ("vad tycker du om mitt argument?"). Ännu inte formellt utvärderad; bidra gärna med data.
