# CLAUDE.md: le regole di `ABP` per Claude

@AGENTS.md
@Rules.md

> Le regole di questo repo valgono per tutti gli agenti e vivono in `AGENTS.md` (il nucleo) e in
> `Rules.md` (il testo completo): Claude Code le carica tutte e due con le due righe qui sopra.
> Qui resta solo quello che vale per Claude.

- Il protocollo di avvio di Claude (permessi, hook, domande iniziali, brief) vive nel `CLAUDE.md`
  del repo `roccobot.github.io`, che è l'hub.
- `refcheck.py` e il dispatcher degli hook vivono in `.memo/scripts/` dell'hub: in una sessione
  che non lo monta, i controlli prima di un commit non girano, e va detto.
