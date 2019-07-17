goSetFunction()
 {
    if [ ! -d ~/.go ]; then
        mkdir ~/.go;
    fi
    echo "`pwd`" > ~/.go/$1
}

goFunction()
{
    if [ ! -e ~/.go/$1 ]; then
        echo "Entry not found!"
    else
        cd "`cat ~/.go/$1`"
		ls
    fi
}

alias "go=goFunction"
alias "gset=goSetFunction"


