``` console
alias mycuts="nano ~/.bashrc"

#Django shortcut commands
alias djall="cd /home/dukula/Area && source myenv/bin/activate"
alias djno="deactivate"
alias dje="cd ~ && cd Area && source djenv/bin/activate"
alias myev="cd ~ && cd Area && source myenv/bin/activate"
alias djr="python manage.py runserver"
alias djmm="python manage.py makemigrations"
alias djm="python manage.py migrate"
djp(){
django-admin startproject "$1"
}
dja(){
python manage.py startapp "$1"
}
alias djsu="python manage.py createsuperuser"
alias djs='python manage.py shell'
#In Here to open inside a folder
alias ih="xdg-open ."
```
