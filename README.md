# solarcode

Install python 3.12.2

pip install virtualenv

virtualenv scenvcdemo
(Se powershell as admin Set-ExecutionPolicy RemoteSigned)
.\scenvdemo\Scripts\activate.ps1

pip install requirements.txt

Create __init__.py, config.py and extensions
set app env variable $env:FLASK_APP = "__init__.py"

flask db init to create db
flask db migrate
flask db upgrade

flask run --debug


# Vash- Models 

Epeidh mporei na xreiastei apo mia aithsh pou exei kai lefta kai xwro na ginoun apodekta mono ta lefta h o xwros 
vazoume duo montela aithsewn ksexwrista ( tha ginoun populate apo thn idia forma ) 

## SolarizeApplicationMoney
Id
Onoma 
Epwnumo
AFM
Xrhmata
isAccepted 
SolarizationId (an ginei accepted )

## SolarizeApplicationSpace
Id
Onoma 
Epwnumo
AFM
Odos ependushs (Odos )
Tupos (taratsa)
Tm (ependushs)
isAccepted 
SolarizationId (an ginei accepted )


## Solarization
Id
Total MoneyAccepted
Total SpaceAccepted
Date Accepted
Stats(applications accepted, space covered, energy produced in 10 yrs)




# Ypologismos aksias xwrou gia ton algorithmo kai gia ta stats

Καρφωτές τιμές που πρέπει να βρούμε / αποφασίσουμε

Λειτουργικά Χρόνια = Χ

Πάγια εγκαταστασης = ΠΕ

Κόστος φωτοβολταικού ανα τμ = ΚΦ

Αξία χώρου - Τιμή ενοικίου ανα τμ = ΕΝ ( ανα μήνα ή χρόνο)

Έξοδα συντήρησης (ανα τμ ή ανα εγκατάσταση ) = ΕΣ 











