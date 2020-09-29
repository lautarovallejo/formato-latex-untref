# formato-latex-untref
Formato de tesis UNTREF en LaTeX

Breve tutorial:
1) Instalar [LaTeX](https://www.latex-project.org/get/)
2) Instalar un editor (yo usé [TeXstudio](https://www.texstudio.org/))
3) Configurar lenguaje en TeXstudio: ir a **Opciones>>Configurar TeXstudio>>Comprobación de lenguaje** y en **Idioma por defecto** seleccionar *es_ES*
4) Para compilar utilizar la cadena: **LuaLaTeX - Biber - LuaLaTeX**. En TeXstudio: ir a **Opciones>>Configurar TeXstudio>>Compilar** y en **Compilar y ver** pegar lo siguiente: *txs:///lualatex | txs:///biber | txs:///lualatex | txs:///view-pdf-internal*. Para compilar finalmente presionar *F5* o hacer click en la "flecha verde doble".

Herramientas útiles:
[Editor de ecuaciones online](https://www.codecogs.com/latex/eqneditor.php)
