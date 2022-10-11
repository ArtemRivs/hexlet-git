// (FEATURE01) start 
sudo apt install software-properties-common apt-transport-https wget
Затем установите ключ репозитория:
wget -q https://packages.microsoft.com/keys/microsoft.asc -O- | sudo apt-key add -
// (FEATURE01) end 


// (master) start 
УСТАНОВКА VISUAL STUDIO CODE НА UBUNTU
Для работы репозитория нужно установить несколько пакетов. Для этого выполните команду:

sudo apt install software-properties-common apt-transport-https wget

Затем установите ключ репозитория:

wget -q https://packages.microsoft.com/keys/microsoft.asc -O- | sudo apt-key add -

И добавьте сам репозиторий:

sudo add-apt-repository "deb [arch=amd64] https://packages.microsoft.com/repos/vscode stable main"

После этого остается обновить списки пакетов и установить VS Code:

sudo apt update
sudo apt install code

// (master) end 

// (FEATURE01) start 
После этого остается обновить списки пакетов и установить VS Code:
sudo apt update
sudo apt install code
// (FEATURE01) end 

// (FEATURE01) start 
После этого остается обновить списки пакетов и установить VS Code:
sudo apt update
udo apt install code
// (FEATURE01) end 

