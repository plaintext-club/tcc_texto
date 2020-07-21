:student: Trabalho de Conclusão de Curso

# Description
Our final graduation project written in a modular ABNT compliant LaTeX document.

# Dependencies
- `sudo pacman -S texlive-most`
- `sudo pacman -S biber`

# Useful commands
- `alias pvc="latexmk -pdf -shell-escape -pvc -view=none layout.tex 1>/dev/null 2>&1 &"` - Automatically recompile the main document when a change is detected.
- `latexmk -pdf -shell-escape layout.tex` - Compile the main document.
- `latexmk -C layout.tex` - soft-clean the environment.
- `git clean -df` - hard-clean the environment.

# Authors
- Henrique Casares
- Vini Lopes
- Lucas Braga

# Resources
- [Overleaf guides](https://www.overleaf.com/learn/latex/Main_Page)
