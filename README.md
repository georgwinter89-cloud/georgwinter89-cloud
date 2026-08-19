<p align="center">
  <a href="https://github.com/georgwinter89-cloud/FlowForge"><img src="https://raw.githubusercontent.com/georgwinter89-cloud/FlowForge/main/docs/bilder/banner.png" alt="FlowForge — Werkbank" width="100%"></a>
</p>

### Hallo, ich bin Georg.

Ich programmiere nicht — und baue trotzdem Software. Den gesamten Code schreibt
Claude; ich beschreibe, entscheide und prüfe. Dabei habe ich gelernt, dass die
eigentliche Arbeit nicht das Tippen ist, sondern das **Gerüst** drum herum:
Welche Regeln gelten für den Agenten, wer prüft wen, was passiert bei Rot, wie
kommt man zurück, wenn etwas schiefgeht.

Genau daraus ist mein Projekt entstanden.

## ⚡ FlowForge

**[georgwinter89-cloud/FlowForge](https://github.com/georgwinter89-cloud/FlowForge)** —
eine Windows-Desktop-App, in der man Coding-Workflows per Drag & Drop aus Blöcken
zusammensteckt (Angreifer, Bauer, Prüfer, Sessionende …) und ein KI-Agent sie
ausführt.

| | |
|---|---|
| **Erzwingen statt bitten** | „darf nur lesen" heißt: das Schreib-Werkzeug wird am Aufruf abgelehnt — nicht als Bitte im Prompt. |
| **Jeder Schritt rückholbar** | Sicherungspunkt vor dem Lauf und nach jedem schreibenden Block, Wiederherstellen mit Vorschau. |
| **Ehrlicher Laufbericht** | Tokens, Modell, jede Rechte-Rückfrage samt Antwort, Metriken: besteht der Prüfer beim ersten Mal? |
| **Motor** | die offizielle Claude Code CLI über das Agent SDK, optional eine lokale KI über Ollama als Helfer. |

Ein Ein-Personen-Projekt, das ich für mich gebaut habe und täglich benutze.
Bewusst deutsch, bewusst MIT, bewusst ehrlich zum Code (gewachsen, nicht entworfen —
dafür über 700 Regel-Prüfungen, die das Verhalten nachmessen).

→ [Installer in den Releases](https://github.com/georgwinter89-cloud/FlowForge/releases/latest) ·
[Was die App tut (SPEC)](https://github.com/georgwinter89-cloud/FlowForge/blob/main/SPEC.md) ·
[Wie sie entstand (BAUPLAN)](https://github.com/georgwinter89-cloud/FlowForge/blob/main/BAUPLAN.md)

## Wie ich arbeite

- **Angriffsliste zuerst.** Vor jedem Bauschritt: Woran könnte genau das scheitern? Funde zuerst ausräumen.
- **Prüfer messen, statt zu lesen.** Prüf-Agenten führen das Verhalten aus, aus zwei Blickwinkeln — Code lesen reicht nicht.
- **Eine Wahrheit, keine Chronik.** Die SPEC beschreibt die Gegenwart, git liefert die Historie. Keine wuchernden Verlaufsdokumente.
- **Folgen-Fragen statt Mechanismus-Fragen.** Entscheidungen werden danach gefragt, was sie bedeuten — nicht, wie sie technisch gehen.

## Unterstützen

Wenn dir FlowForge oder die Idee dahinter etwas bringt:
**[github.com/sponsors/georgwinter89-cloud](https://github.com/sponsors/georgwinter89-cloud)** —
Kaffeegeld, keine Einnahmequelle. Der Wert ist das Signal, dass hier ein Mensch
dahintersteht.

<p align="center"><sub>Windows 11 · Electron · React · Claude Code CLI · Deutsch</sub></p>
