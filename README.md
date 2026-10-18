# ins

Portal d'entrada als recursos de matemàtiques per a l'institut: una sola pàgina (`index.html`,
HTML + CSS sense JavaScript ni compilació) amb targetes que enllacen a cada web del projecte
Step Quiz.

## Contingut del portal

| Secció | Targetes (destí) |
|---|---|
| **Alumnat** | Step Quiz (`step-quiz.net`), Step Quiz adaptat (`a.step-quiz.net`), Repàs de l'ESO (`repas.step-quiz.net`), Geometria sintètica (`geom.step-quiz.net`) |
| **Professorat** | Banc de recursos didàctics (`m.step-quiz.net`), Llibres de text ESO (`llibre.step-quiz.net`), Batxi PRO (`pd.step-quiz.net`), Programació informàtica (`karelcat.step-quiz.net`) |
| **Proves** | Prova Cangur (`cangurcat.step-quiz.net`), Competència matemàtica (`cb.step-quiz.net`), PAU (`pau.step-quiz.net`) |
| **Formularis** | Enviar una fotografia i enviar un codi d'activitat Step Quiz (Google Forms) |

Les icones de les targetes són els fitxers `icon*.png` de l'arrel.

`.github/comprova-enllacos.py` comprova que totes les targetes porten a webs que funcionen. GitHub l'executa a cada canvi a `main`, cada dilluns al matí i a mà (`.github/workflows/enllacos.yml`, «Enllaços» a la pestanya Actions).

Per afegir o treure un web, cal editar la targeta corresponent (`<div class="app-card …">`)
dins de la secció adequada d'`index.html`.

<!-- atribucio-centre:inici -->

---

Material desenvolupat per **David Arso Civil** per al Departament de Matemàtiques de l'INS Miquel Tarradell.
Contingut sota CC BY-NC-SA 4.0, codi sota llicència MIT. Vegeu [`LLICENCIA.md`](LLICENCIA.md).

<!-- atribucio-centre:final -->
