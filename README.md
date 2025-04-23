# Portuguese conjugation
## Idea
While learning portuguese conjugation, I remarked there is some logic in it (ie, imperative uses indicative or subjunctive form depending on the person, etc.). So i thought that implementing the logic in code would assist me in understanding and remembering it.
That would also be a good way to learn about Python object inheritance.
## Use
Instantiate a tense class (ie "Presente_Indicativo"), set its verb and call conjugTudo() method.
You can also set option parameter to "ter" and "ir", to conjugate with "ter de"+infinitivo or ir+infinitivo forms.
## LIMITATIONS
The code implements some known irregular forms i studied or read in books, but will apply default forms to any verb it doesn't know.
It is not meant as a strong reference, but as a learning tool.
I tested it against my textbooks and dictionary, but feel free to contribute and enrich it if you are seeing some errors.
# Current status
## Implemented
### Tempos
- Presente do indicativo
- Preterito perfeito
- Imperfeito
- Presente do condicional
- Presente do subjuntivo
- Imperativo
### Options
- "ter de" + infinitivo
- "ir" + infinitivo
## Unimplemented - TO DO
### Tempos
- Perfeito composto
- Mais que perfeito
- Futuro simples
- Futuro composto
- Condicional composto
- Subjuntivo imperfeito
- Subjuntivo perfeito
- Subjuntivo mais que perfeito
- Subjuntivo futuro 
- Infinitivo conjugado: impersonal, personal simple, personal composto
- Gerundio: simple, composto
- Participio

