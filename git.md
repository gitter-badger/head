---

### git install script

    # git start
    if
        sudo git;
    then
        echo "not installed";
    else
        sudo aptitude update;
    fi
    #
    if
        sudo aptitude -y install git;
        sudo git config --system user.name "680682";
        sudo git config --system user.email "680682@gmail.com";
        sudo git config --system core.editor vim;
        sudo git config --system merge.tool vimdiff;
     
    then
        echo "git has been installed";
    else
        echo "git NOT installed";
    fi
    # git end

---

