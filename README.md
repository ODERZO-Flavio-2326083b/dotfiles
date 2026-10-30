# dotfiles
c'est un amalgame de plusieurs fichiers que j'ai pu trouver et est adapté à mes besoins

j'en rajouterai au fur et à mesure que j'accumule les configurations

## info sur les symlinks entre WSL et Windows (pour que je m'en souvienne)

puisque les systèmes de fichiers sont différents entre WSL et Windows, on ne peut pas créer de hardlink de windows vers WSL (ou inversement)

les symlink fonctionnent ceci-dit, il suffit de créer le symlink sur le terminal correspondant à la destination du fichier

exemple: .ideavimrc est stocké sur le WSL, utilisé par WebStorm qui cherche sur le $HOME de Windows, ainsi on va créer un symlink sur Windows avec un PowerShell
