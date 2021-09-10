# FinoDaysHackCrungibugi
Проект для участия в программе FinoDays

По кейсу "Распознавание интонационного подтекста из сообщений"
#operating requirements
1) LINUX based OS
2) Python3 

#installing packages 
1) Установка библиотеки для распознавания интонации:
   * pip install dostoevsky
   
2) Подгрузка набора интонационных данных
   *  python3 -m dostoevsky download fasttext-social-network-model
#run demo
Из рабочей директории вызвать команду:
* python3 main.py