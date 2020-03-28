# khs-crawler

Crawler COVID-19 dat z Krajsk�ch hygienick�ch stanic

Prototyp skript� pro crawling dat jednotliv�ch KHS. 

*Ps�no primitivn�m stylem, nejsou o�et�eny v�jimky atd.*

Pou�it� knihovny:

 - **requests** + **BeautifulSoup** - parsov�n� dat z web�
 - **PyPDF2** - parsov�n� dat z relativn� dob�e strukturovan�ch PDF 
 - **Pillow** - pr�ce s obr�zky
 - **pytesseract** - OCR pomoc� [Tesseract](https://tesseract-ocr.github.io/)

Informace o zdroj�ch: [https://www.sablatura.info/covid/hygienicke-stanice/](https://www.sablatura.info/covid/hygienicke-stanice/)

V�stupy: [https://docs.google.com/spreadsheets/d/1FFEDhS6VMWon_AWkJrf8j3XxjZ4J6UI1B2lO3IW-EEc](https://docs.google.com/spreadsheets/d/1FFEDhS6VMWon_AWkJrf8j3XxjZ4J6UI1B2lO3IW-EEc)

## Chyb�j�c� kraje:
- Jihomoravsk� kraj - ka�d� den nov� PDF, asi by �lo naj�t v�dy vhodn� nejnov�j��
- Karlovarsk� kraj - 28.3. odstranili z PDF data o okresech
- Moravskoslezsk� kraj - data v obr�zkov�ch sloupcov�ch grafech - um�st�n� hodnoty se m�n�... d�le je  k dispozici obr�zek na homepage, ale s�m m�m probl�m ho p�e��st...
- Zl�nsk� kraj - ka�d� den se m�n� PDF, ale asi realizovateln�


