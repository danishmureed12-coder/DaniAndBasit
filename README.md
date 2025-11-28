# DaniAndBasit

clear
echo -e "\e[96m━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━\e[0m"
echo -e "\e[93m        DANI AND BASIT          \e[0m"
echo -e "\e[96m━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━\e[0m"
sleep 1

# Paid Banner
echo -e "\e[1;36m
██████╗░░█████╗░███╗░░██╗██╗
██╔══██╗██╔══██╗████╗░██║██║
██║░░██║███████║██╔██╗██║██║
██║░░██║██╔══██║██║╚████║██║
██████╔╝██║░░██║██║░╚███║██║
╚═════╝░╚═╝░░╚═╝╚═╝░░╚══╝╚═╝

\e[1;33m        DANI AND BASIT PAID TOOL 
\e[1;32m--------------------------------------------
\e[1;32m• Tool Price:        3$
\e[1;32m• Full Script Price: 5$
\e[1;33m--------------------------------------------
\e[1;31mNOTE: Without KEY access is not allowed!
\e[0m"
sleep 1

# License Key Check
echo -e "\e[96mEnter License Key to Continue:\e[0m"
read KEY

if [ "$KEY" != "inbox mai awoo ly jawo " ]; then
    echo -e "\n\e[91m[×] INVALID LICENSE KEY!"
    echo -e "\e[91m[×] ACCESS DENIED!"
    echo -e "\e[93mContact Admin: wa.me/00000000\e[0m"
    exit
else
    echo -e "\n\e[92m[✓] LICENSE VERIFIED — ACCESS GRANTED!\e[0m"
fi

sleep 1

# System update + Install Python & Git
echo -e "\e[93m[✓] Updating System...\e[0m"
pkg update && pkg upgrade -y
echo -e "\e[93m[✓] Installing Python & Git...\e[0m"
pkg install python git -y

# Clone GitHub Repo
echo -e "\e[93m[✓] Cloning Repository...\e[0m"
git clone https://github.com/danishmureed12-coder/DaniAndBasit.git
cd DaniAndBasit

# Run Script
echo -e "\e[92m[✓] Launching Script...\e[0m"
python danibasit.py






