# 00_4

#1 body div thead.text-black>tr.hidden   

#2 table thead tr th.px-3:nth-child(1)     # заголовки

#3 table thead tr th.px-3:nth-child(2)

#4 table thead tr th.px-3:nth-child(3)

#5 table thead tr th.px-3:nth-child(4)

#6 table thead tr th.px-3:nth-child(5)

#7 div a.inline-flex[href*=mailto]        


            # исправлено (vol.2)

#1 thead tr.hidden                       # заголовок таблицы

2 tr.border-b                      

#3 div a[href*=mailto]               # указатель для получения email


tr.bg-white:nth-child(1)           # строка в табл.

for i in range(1,101):
 print(f'tr.bg-white:nth-child({i})')   # цикл для всех строк




                         #.XPath.


1.  /html/body//div/table/thead/tr[1]        # заголовок таблицы

2.  /html/body/div//tbody/tr[1]            # первая строка в табл

3.  for i in range(1,101):
 print(f'/html/body/div//tbody/tr[{i}]')     # цикл для строк

4. /html/body/div//ul/li[1]//a[contains(@href, 'mailto')] # указатель для получения email





















