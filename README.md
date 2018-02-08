# Git_command
Comando git em windows system

# Mostrar mensagem da ultima tag e o commit de origem da tag
for /f "delims=" %%a in ('git describe --tags --abbrev^=0') do @set latesttag=%%a
git show %latesttag% --notes
