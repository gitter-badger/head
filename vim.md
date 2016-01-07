---

### vim install script

    # vim  start
    if
        sudo vim;
    then
        echo "=====================================vim installed";
    elif
        echo "=====================================vim not installed";
    then
        sudo aptitude update;
        echo "=====================================updated successefy";
    fi
    if
        sudo aptitude -y install vim;
    then
        echo "=====================================vim install successefy";
        echo "=====================================git config --list start";
        git config --list;
        echo "=====================================git config --list end";
    else
        echo "vim not installed";
    fi
    # vim end

---