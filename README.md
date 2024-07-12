# DATA-SCIENCE-ARCHITECTURE-AI-and-ML
Contains the DATA SCIENCE, ARCHITECTURE, AI - series  & some snippets to solve various issues 

***  Help to fix   font family not found in Windows font database. You are recieving the below error or warning.   ***
Must be done for regular & prject env. then registered with R for your device 

***  To fix problemslike below

Fix 
> warnings()
Warning messages:
1: In grid.Call(C_textBounds, as.graphicsAnnot(x$label),  ... :
  font family not found in Windows font database
2: In grid.Call(C_textBounds, as.graphicsAnnot(x$label),  ... :
  font family not found in Windows font database
3: In grid.Call(C_textBounds, as.graphicsAnnot(x$label),  ... :
  font family not found in Windows font database



***********************************************************************************************************************
Fix for regular env
***********************************************************************************************************************
# Env. SetUp
# install.packages("ggthemes",repos = "http://cran.us.r-project.org")
# install.packages("extrafont", repos = "http://cran.us.r-project.org")

# Env. SetUp 
install.packages("ggthemes")
install.packages("extrafont")

library(ggthemes)
library(extrafont)

install.packages("Rttf2pt1")
library(Rttf2pt1)

# Load fonts
extrafont::font_import()
# Load fonts
extrafont::loadfonts(quiet = T)
extrafont::fonts()


                             
> install.packages("Rttf2pt1")
trying URL 'https://cran.rstudio.com/bin/windows/contrib/4.4/Rttf2pt1_1.3.12.zip'
Content type 'application/zip' length 152377 bytes (148 KB)
downloaded 148 KB

package ‘Rttf2pt1’ successfully unpacked and MD5 sums checked

The downloaded binary packages are in
	C:\Users\Administrator\tmp\3\RtmpimaZoi\downloaded_packages
> library(Rttf2pt1)
There were 14 warnings (use warnings() to see them)
>  warnings()
Warning messages:
1: In grid.Call(C_textBounds, as.graphicsAnnot(x$label),  ... :
  font family not found in Windows font database
2: In grid.Call(C_textBounds, as.graphicsAnnot(x$label),  ... :
  font family not found in Windows font database
3: In grid.Call(C_textBounds, as.graphicsAnnot(x$label),  ... :
  font family not found in Windows font database
4: In grid.Call.graphics(C_text, as.graphicsAnnot(x$label),  ... :
  font family not found in Windows font database
5: In grid.Call.graphics(C_text, as.graphicsAnnot(x$label),  ... :
  font family not found in Windows font database
6: In grid.Call.graphics(C_text, as.graphicsAnnot(x$label),  ... :
  font family not found in Windows font database
7: In grid.Call.graphics(C_text, as.graphicsAnnot(x$label),  ... :
  font family not found in Windows font database
8: In grid.Call(C_textBounds, as.graphicsAnnot(x$label),  ... :
  font family not found in Windows font database
9: In grid.Call(C_textBounds, as.graphicsAnnot(x$label),  ... :
  font family not found in Windows font database
10: In grid.Call(C_textBounds, as.graphicsAnnot(x$label),  ... :
  font family not found in Windows font database
11: In grid.Call.graphics(C_text, as.graphicsAnnot(x$label),  ... :
  font family not found in Windows font database
12: In grid.Call.graphics(C_text, as.graphicsAnnot(x$label),  ... :
  font family not found in Windows font database
13: In grid.Call.graphics(C_text, as.graphicsAnnot(x$label),  ... :
  font family not found in Windows font database
14: In grid.Call.graphics(C_text, as.graphicsAnnot(x$label),  ... :
  font family not found in Windows font database
> extrafont::font_import()
Importing fonts may take a few minutes, depending on the number of fonts and the speed of the system.
Continue? [y/n] y
Scanning ttf files in C:\Windows/Fonts, C:\Users\Administrator\AppData\Local/Microsoft/Windows/Fonts ...
Extracting .afm files from .ttf files...
C:\Windows\Fonts\AGENCYB.TTF => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/AGENCYB
C:\Windows\Fonts\AGENCYR.TTF => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/AGENCYR
C:\Windows\Fonts\ahronbd.ttf => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/ahronbd
C:\Windows\Fonts\aldhabi.ttf => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/aldhabi
C:\Windows\Fonts\ALGER.TTF => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/ALGER
C:\Windows\Fonts\andlso.ttf => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/andlso
C:\Windows\Fonts\ANTQUAB.TTF => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/ANTQUAB
C:\Windows\Fonts\ANTQUABI.TTF => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/ANTQUABI
C:\Windows\Fonts\ANTQUAI.TTF => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/ANTQUAI
C:\Windows\Fonts\arabtype.ttf : No FontName. Skipping.
C:\Windows\Fonts\arial.ttf => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/arial
C:\Windows\Fonts\arialbd.ttf => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/arialbd
C:\Windows\Fonts\arialbi.ttf => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/arialbi
C:\Windows\Fonts\ariali.ttf => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/ariali
C:\Windows\Fonts\ARIALN.TTF => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/ARIALN
C:\Windows\Fonts\ARIALNB.TTF => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/ARIALNB
C:\Windows\Fonts\ARIALNBI.TTF => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/ARIALNBI
C:\Windows\Fonts\ARIALNI.TTF => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/ARIALNI
C:\Windows\Fonts\ariblk.ttf => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/ariblk
C:\Windows\Fonts\ARLRDBD.TTF => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/ARLRDBD
C:\Windows\Fonts\bahnschrift.ttf => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/bahnschrift
C:\Windows\Fonts\BASKVILL.TTF => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/BASKVILL
C:\Windows\Fonts\BAUHS93.TTF => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/BAUHS93
C:\Windows\Fonts\BELL.TTF => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/BELL
C:\Windows\Fonts\BELLB.TTF => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/BELLB
C:\Windows\Fonts\BELLI.TTF => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/BELLI
C:\Windows\Fonts\BERNHC.TTF => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/BERNHC
C:\Windows\Fonts\BKANT.TTF => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/BKANT
C:\Windows\Fonts\BOD_B.TTF => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/BOD_B
C:\Windows\Fonts\BOD_BI.TTF => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/BOD_BI
C:\Windows\Fonts\BOD_BLAI.TTF => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/BOD_BLAI
C:\Windows\Fonts\BOD_BLAR.TTF => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/BOD_BLAR
C:\Windows\Fonts\BOD_CB.TTF => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/BOD_CB
C:\Windows\Fonts\BOD_CBI.TTF => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/BOD_CBI
C:\Windows\Fonts\BOD_CI.TTF => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/BOD_CI
C:\Windows\Fonts\BOD_CR.TTF => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/BOD_CR
C:\Windows\Fonts\BOD_I.TTF => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/BOD_I
C:\Windows\Fonts\BOD_PSTC.TTF => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/BOD_PSTC
C:\Windows\Fonts\BOD_R.TTF => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/BOD_R
C:\Windows\Fonts\BOOKOS.TTF => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/BOOKOS
C:\Windows\Fonts\BOOKOSB.TTF => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/BOOKOSB
C:\Windows\Fonts\BOOKOSBI.TTF => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/BOOKOSBI
C:\Windows\Fonts\BOOKOSI.TTF => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/BOOKOSI
C:\Windows\Fonts\BRADHITC.TTF => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/BRADHITC
C:\Windows\Fonts\BRITANIC.TTF => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/BRITANIC
C:\Windows\Fonts\BRLNSB.TTF => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/BRLNSB
C:\Windows\Fonts\BRLNSDB.TTF => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/BRLNSDB
C:\Windows\Fonts\BRLNSR.TTF => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/BRLNSR
C:\Windows\Fonts\BROADW.TTF => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/BROADW
C:\Windows\Fonts\BRUSHSCI.TTF => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/BRUSHSCI
C:\Windows\Fonts\BSSYM7.TTF => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/BSSYM7
C:\Windows\Fonts\calibri.ttf => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/calibri
C:\Windows\Fonts\calibrib.ttf => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/calibrib
C:\Windows\Fonts\calibrii.ttf => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/calibrii
C:\Windows\Fonts\calibril.ttf => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/calibril
C:\Windows\Fonts\calibrili.ttf => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/calibrili
C:\Windows\Fonts\calibriz.ttf => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/calibriz
C:\Windows\Fonts\CALIFB.TTF => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/CALIFB
C:\Windows\Fonts\CALIFI.TTF => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/CALIFI
C:\Windows\Fonts\CALIFR.TTF => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/CALIFR
C:\Windows\Fonts\CALIST.TTF => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/CALIST
C:\Windows\Fonts\CALISTB.TTF => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/CALISTB
C:\Windows\Fonts\CALISTBI.TTF => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/CALISTBI
C:\Windows\Fonts\CALISTI.TTF => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/CALISTI
C:\Windows\Fonts\cambriab.ttf => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/cambriab
C:\Windows\Fonts\cambriai.ttf => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/cambriai
C:\Windows\Fonts\cambriaz.ttf => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/cambriaz
C:\Windows\Fonts\Candara.ttf => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/Candara
C:\Windows\Fonts\Candarab.ttf => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/Candarab
C:\Windows\Fonts\Candarai.ttf => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/Candarai
C:\Windows\Fonts\Candaral.ttf => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/Candaral
C:\Windows\Fonts\Candarali.ttf => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/Candarali
C:\Windows\Fonts\Candaraz.ttf => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/Candaraz
C:\Windows\Fonts\CascadiaCode.ttf => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/CascadiaCode
C:\Windows\Fonts\CascadiaMono.ttf => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/CascadiaMono
C:\Windows\Fonts\CASTELAR.TTF => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/CASTELAR
C:\Windows\Fonts\CENSCBK.TTF => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/CENSCBK
C:\Windows\Fonts\CENTAUR.TTF => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/CENTAUR
C:\Windows\Fonts\CENTURY.TTF => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/CENTURY
C:\Windows\Fonts\CHILLER.TTF => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/CHILLER
C:\Windows\Fonts\COLONNA.TTF => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/COLONNA
C:\Windows\Fonts\comic.ttf => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/comic
C:\Windows\Fonts\comicbd.ttf => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/comicbd
C:\Windows\Fonts\comici.ttf => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/comici
C:\Windows\Fonts\comicz.ttf => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/comicz
C:\Windows\Fonts\consola.ttf => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/consola
C:\Windows\Fonts\consolab.ttf => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/consolab
C:\Windows\Fonts\consolai.ttf => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/consolai
C:\Windows\Fonts\consolaz.ttf => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/consolaz
C:\Windows\Fonts\constan.ttf => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/constan
C:\Windows\Fonts\constanb.ttf => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/constanb
C:\Windows\Fonts\constani.ttf => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/constani
C:\Windows\Fonts\constanz.ttf => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/constanz
C:\Windows\Fonts\COOPBL.TTF => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/COOPBL
C:\Windows\Fonts\COPRGTB.TTF => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/COPRGTB
C:\Windows\Fonts\COPRGTL.TTF => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/COPRGTL
C:\Windows\Fonts\corbel.ttf => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/corbel
C:\Windows\Fonts\corbelb.ttf => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/corbelb
C:\Windows\Fonts\corbeli.ttf => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/corbeli
C:\Windows\Fonts\corbell.ttf => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/corbell
C:\Windows\Fonts\corbelli.ttf => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/corbelli
C:\Windows\Fonts\corbelz.ttf => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/corbelz
C:\Windows\Fonts\cour.ttf => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/cour
C:\Windows\Fonts\courbd.ttf => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/courbd
C:\Windows\Fonts\courbi.ttf => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/courbi
C:\Windows\Fonts\couri.ttf => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/couri
C:\Windows\Fonts\CURLZ___.TTF => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/CURLZ___
C:\Windows\Fonts\david.ttf => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/david
C:\Windows\Fonts\davidbd.ttf => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/davidbd
C:\Windows\Fonts\DUBAI-BOLD.TTF => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/DUBAI-BOLD
C:\Windows\Fonts\DUBAI-LIGHT.TTF => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/DUBAI-LIGHT
C:\Windows\Fonts\DUBAI-MEDIUM.TTF => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/DUBAI-MEDIUM
C:\Windows\Fonts\DUBAI-REGULAR.TTF => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/DUBAI-REGULAR
C:\Windows\Fonts\ebrima.ttf => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/ebrima
C:\Windows\Fonts\ebrimabd.ttf => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/ebrimabd
C:\Windows\Fonts\ELEPHNT.TTF => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/ELEPHNT
C:\Windows\Fonts\ELEPHNTI.TTF => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/ELEPHNTI
C:\Windows\Fonts\ENGR.TTF => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/ENGR
C:\Windows\Fonts\ERASBD.TTF => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/ERASBD
C:\Windows\Fonts\ERASDEMI.TTF => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/ERASDEMI
C:\Windows\Fonts\ERASLGHT.TTF => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/ERASLGHT
C:\Windows\Fonts\ERASMD.TTF => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/ERASMD
C:\Windows\Fonts\FELIXTI.TTF => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/FELIXTI
C:\Windows\Fonts\FORTE.TTF => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/FORTE
C:\Windows\Fonts\FRABK.TTF => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/FRABK
C:\Windows\Fonts\FRABKIT.TTF => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/FRABKIT
C:\Windows\Fonts\FRADM.TTF => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/FRADM
C:\Windows\Fonts\FRADMCN.TTF => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/FRADMCN
C:\Windows\Fonts\FRADMIT.TTF => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/FRADMIT
C:\Windows\Fonts\FRAHV.TTF => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/FRAHV
C:\Windows\Fonts\FRAHVIT.TTF => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/FRAHVIT
C:\Windows\Fonts\framd.ttf => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/framd
C:\Windows\Fonts\FRAMDCN.TTF => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/FRAMDCN
C:\Windows\Fonts\framdit.ttf => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/framdit
C:\Windows\Fonts\frank.ttf => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/frank
C:\Windows\Fonts\FREESCPT.TTF => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/FREESCPT
C:\Windows\Fonts\FRSCRIPT.TTF => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/FRSCRIPT
C:\Windows\Fonts\FTLTLT.TTF => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/FTLTLT
C:\Windows\Fonts\Gabriola.ttf => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/Gabriola
C:\Windows\Fonts\gadugi.ttf => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/gadugi
C:\Windows\Fonts\gadugib.ttf => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/gadugib
C:\Windows\Fonts\GARA.TTF => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/GARA
C:\Windows\Fonts\GARABD.TTF => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/GARABD
C:\Windows\Fonts\GARAIT.TTF => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/GARAIT
C:\Windows\Fonts\georgia.ttf => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/georgia
C:\Windows\Fonts\georgiab.ttf => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/georgiab
C:\Windows\Fonts\georgiai.ttf => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/georgiai
C:\Windows\Fonts\georgiaz.ttf => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/georgiaz
C:\Windows\Fonts\GIGI.TTF => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/GIGI
C:\Windows\Fonts\GIL_____.TTF => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/GIL_____
C:\Windows\Fonts\GILB____.TTF => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/GILB____
C:\Windows\Fonts\GILBI___.TTF => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/GILBI___
C:\Windows\Fonts\GILC____.TTF => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/GILC____
C:\Windows\Fonts\GILI____.TTF => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/GILI____
C:\Windows\Fonts\GILLUBCD.TTF => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/GILLUBCD
C:\Windows\Fonts\GILSANUB.TTF => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/GILSANUB
C:\Windows\Fonts\gisha.ttf => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/gisha
C:\Windows\Fonts\gishabd.ttf => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/gishabd
C:\Windows\Fonts\GLECB.TTF => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/GLECB
C:\Windows\Fonts\GLSNECB.TTF => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/GLSNECB
C:\Windows\Fonts\GOTHIC.TTF => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/GOTHIC
C:\Windows\Fonts\GOTHICB.TTF => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/GOTHICB
C:\Windows\Fonts\GOTHICBI.TTF => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/GOTHICBI
C:\Windows\Fonts\GOTHICI.TTF => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/GOTHICI
C:\Windows\Fonts\GOUDOS.TTF => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/GOUDOS
C:\Windows\Fonts\GOUDOSB.TTF => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/GOUDOSB
C:\Windows\Fonts\GOUDOSI.TTF => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/GOUDOSI
C:\Windows\Fonts\GOUDYSTO.TTF => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/GOUDYSTO
C:\Windows\Fonts\HackNerdFont-Bold.ttf : No FontName. Skipping.
C:\Windows\Fonts\HackNerdFont-BoldItalic.ttf : No FontName. Skipping.
C:\Windows\Fonts\HackNerdFont-Italic.ttf : No FontName. Skipping.
C:\Windows\Fonts\HackNerdFont-Regular.ttf : No FontName. Skipping.
C:\Windows\Fonts\HackNerdFontMono-Bold.ttf : No FontName. Skipping.
C:\Windows\Fonts\HackNerdFontMono-BoldItalic.ttf : No FontName. Skipping.
C:\Windows\Fonts\HackNerdFontMono-Italic.ttf : No FontName. Skipping.
C:\Windows\Fonts\HackNerdFontMono-Regular.ttf : No FontName. Skipping.
C:\Windows\Fonts\HackNerdFontPropo-Bold.ttf : No FontName. Skipping.
C:\Windows\Fonts\HackNerdFontPropo-BoldItalic.ttf : No FontName. Skipping.
C:\Windows\Fonts\HackNerdFontPropo-Italic.ttf : No FontName. Skipping.
C:\Windows\Fonts\HackNerdFontPropo-Regular.ttf : No FontName. Skipping.
C:\Windows\Fonts\HARLOWSI.TTF => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/HARLOWSI
C:\Windows\Fonts\HARNGTON.TTF => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/HARNGTON
C:\Windows\Fonts\HATTEN.TTF => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/HATTEN
C:\Windows\Fonts\HeavyDataNerdFont-Regular.ttf : No FontName. Skipping.
C:\Windows\Fonts\HeavyDataNerdFontPropo-Regular.ttf : No FontName. Skipping.
C:\Windows\Fonts\himalaya.ttf => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/himalaya
C:\Windows\Fonts\HTOWERT.TTF => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/HTOWERT
C:\Windows\Fonts\HTOWERTI.TTF => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/HTOWERTI
C:\Windows\Fonts\impact.ttf => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/impact
C:\Windows\Fonts\IMPRISHA.TTF => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/IMPRISHA
C:\Windows\Fonts\INFROMAN.TTF => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/INFROMAN
C:\Windows\Fonts\Inkfree.ttf => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/Inkfree
C:\Windows\Fonts\ITCBLKAD.TTF => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/ITCBLKAD
C:\Windows\Fonts\ITCEDSCR.TTF => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/ITCEDSCR
C:\Windows\Fonts\ITCKRIST.TTF => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/ITCKRIST
C:\Windows\Fonts\javatext.ttf => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/javatext
C:\Windows\Fonts\JOKERMAN.TTF => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/JOKERMAN
C:\Windows\Fonts\JUICE___.TTF => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/JUICE___
C:\Windows\Fonts\KUNSTLER.TTF => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/KUNSTLER
C:\Windows\Fonts\l_10646.ttf => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/l_10646
C:\Windows\Fonts\LATINWD.TTF => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/LATINWD
C:\Windows\Fonts\LBRITE.TTF => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/LBRITE
C:\Windows\Fonts\LBRITED.TTF => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/LBRITED
C:\Windows\Fonts\LBRITEDI.TTF => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/LBRITEDI
C:\Windows\Fonts\LBRITEI.TTF => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/LBRITEI
C:\Windows\Fonts\LCALLIG.TTF => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/LCALLIG
C:\Windows\Fonts\LeelaUIb.ttf => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/LeelaUIb
C:\Windows\Fonts\LEELAWAD.TTF => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/LEELAWAD
C:\Windows\Fonts\LEELAWDB.TTF => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/LEELAWDB
C:\Windows\Fonts\LeelawUI.ttf => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/LeelawUI
C:\Windows\Fonts\LeelUIsl.ttf => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/LeelUIsl
C:\Windows\Fonts\LFAX.TTF => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/LFAX
C:\Windows\Fonts\LFAXD.TTF => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/LFAXD
C:\Windows\Fonts\LFAXDI.TTF => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/LFAXDI
C:\Windows\Fonts\LFAXI.TTF => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/LFAXI
C:\Windows\Fonts\LHANDW.TTF => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/LHANDW
C:\Windows\Fonts\LSANS.TTF => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/LSANS
C:\Windows\Fonts\LSANSD.TTF => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/LSANSD
C:\Windows\Fonts\LSANSDI.TTF => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/LSANSDI
C:\Windows\Fonts\LSANSI.TTF => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/LSANSI
C:\Windows\Fonts\LTYPE.TTF => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/LTYPE
C:\Windows\Fonts\LTYPEB.TTF => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/LTYPEB
C:\Windows\Fonts\LTYPEBO.TTF => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/LTYPEBO
C:\Windows\Fonts\LTYPEO.TTF => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/LTYPEO
C:\Windows\Fonts\lucon.ttf => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/lucon
C:\Windows\Fonts\lvnm.ttf => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/lvnm
C:\Windows\Fonts\lvnmbd.ttf => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/lvnmbd
C:\Windows\Fonts\MAGNETOB.TTF => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/MAGNETOB
C:\Windows\Fonts\MAIAN.TTF => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/MAIAN
C:\Windows\Fonts\majalla.ttf => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/majalla
C:\Windows\Fonts\majallab.ttf => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/majallab
C:\Windows\Fonts\malgun.ttf => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/malgun
C:\Windows\Fonts\malgunbd.ttf => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/malgunbd
C:\Windows\Fonts\malgunsl.ttf => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/malgunsl
C:\Windows\Fonts\marlett.ttf => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/marlett
C:\Windows\Fonts\MATURASC.TTF => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/MATURASC
C:\Windows\Fonts\MesloLGLDZNerdFont-Bold.ttf : No FontName. Skipping.
C:\Windows\Fonts\MesloLGLDZNerdFont-BoldItalic.ttf : No FontName. Skipping.
C:\Windows\Fonts\MesloLGLDZNerdFont-Italic.ttf : No FontName. Skipping.
C:\Windows\Fonts\MesloLGLDZNerdFont-Regular.ttf : No FontName. Skipping.
C:\Windows\Fonts\MesloLGLDZNerdFontMono-Bold.ttf : No FontName. Skipping.
C:\Windows\Fonts\MesloLGLDZNerdFontMono-BoldItalic.ttf : No FontName. Skipping.
C:\Windows\Fonts\MesloLGLDZNerdFontMono-Italic.ttf : No FontName. Skipping.
C:\Windows\Fonts\MesloLGLDZNerdFontMono-Regular.ttf : No FontName. Skipping.
C:\Windows\Fonts\MesloLGLDZNerdFontPropo-Bold.ttf : No FontName. Skipping.
C:\Windows\Fonts\MesloLGLDZNerdFontPropo-BoldItalic.ttf : No FontName. Skipping.
C:\Windows\Fonts\MesloLGLDZNerdFontPropo-Italic.ttf : No FontName. Skipping.
C:\Windows\Fonts\MesloLGLDZNerdFontPropo-Regular.ttf : No FontName. Skipping.
C:\Windows\Fonts\MesloLGLNerdFont-Bold.ttf : No FontName. Skipping.
C:\Windows\Fonts\MesloLGLNerdFont-BoldItalic.ttf : No FontName. Skipping.
C:\Windows\Fonts\MesloLGLNerdFont-Italic.ttf : No FontName. Skipping.
C:\Windows\Fonts\MesloLGLNerdFont-Regular.ttf : No FontName. Skipping.
C:\Windows\Fonts\MesloLGLNerdFontMono-Bold.ttf : No FontName. Skipping.
C:\Windows\Fonts\MesloLGLNerdFontMono-BoldItalic.ttf : No FontName. Skipping.
C:\Windows\Fonts\MesloLGLNerdFontMono-Italic.ttf : No FontName. Skipping.
C:\Windows\Fonts\MesloLGLNerdFontMono-Regular.ttf : No FontName. Skipping.
C:\Windows\Fonts\MesloLGLNerdFontPropo-Bold.ttf : No FontName. Skipping.
C:\Windows\Fonts\MesloLGLNerdFontPropo-BoldItalic.ttf : No FontName. Skipping.
C:\Windows\Fonts\MesloLGLNerdFontPropo-Italic.ttf : No FontName. Skipping.
C:\Windows\Fonts\MesloLGLNerdFontPropo-Regular.ttf : No FontName. Skipping.
C:\Windows\Fonts\MesloLGMDZNerdFont-Bold.ttf : No FontName. Skipping.
C:\Windows\Fonts\MesloLGMDZNerdFont-BoldItalic.ttf : No FontName. Skipping.
C:\Windows\Fonts\MesloLGMDZNerdFont-Italic.ttf : No FontName. Skipping.
C:\Windows\Fonts\MesloLGMDZNerdFont-Regular.ttf : No FontName. Skipping.
C:\Windows\Fonts\MesloLGMDZNerdFontMono-Bold.ttf : No FontName. Skipping.
C:\Windows\Fonts\MesloLGMDZNerdFontMono-BoldItalic.ttf : No FontName. Skipping.
C:\Windows\Fonts\MesloLGMDZNerdFontMono-Italic.ttf : No FontName. Skipping.
C:\Windows\Fonts\MesloLGMDZNerdFontMono-Regular.ttf : No FontName. Skipping.
C:\Windows\Fonts\MesloLGMDZNerdFontPropo-Bold.ttf : No FontName. Skipping.
C:\Windows\Fonts\MesloLGMDZNerdFontPropo-BoldItalic.ttf : No FontName. Skipping.
C:\Windows\Fonts\MesloLGMDZNerdFontPropo-Italic.ttf : No FontName. Skipping.
C:\Windows\Fonts\MesloLGMDZNerdFontPropo-Regular.ttf : No FontName. Skipping.
C:\Windows\Fonts\MesloLGMNerdFont-Bold.ttf : No FontName. Skipping.
C:\Windows\Fonts\MesloLGMNerdFont-BoldItalic.ttf : No FontName. Skipping.
C:\Windows\Fonts\MesloLGMNerdFont-Italic.ttf : No FontName. Skipping.
C:\Windows\Fonts\MesloLGMNerdFont-Regular.ttf : No FontName. Skipping.
C:\Windows\Fonts\MesloLGMNerdFontMono-Bold.ttf : No FontName. Skipping.
C:\Windows\Fonts\MesloLGMNerdFontMono-BoldItalic.ttf : No FontName. Skipping.
C:\Windows\Fonts\MesloLGMNerdFontMono-Italic.ttf : No FontName. Skipping.
C:\Windows\Fonts\MesloLGMNerdFontMono-Regular.ttf : No FontName. Skipping.
C:\Windows\Fonts\MesloLGMNerdFontPropo-Bold.ttf : No FontName. Skipping.
C:\Windows\Fonts\MesloLGMNerdFontPropo-BoldItalic.ttf : No FontName. Skipping.
C:\Windows\Fonts\MesloLGMNerdFontPropo-Italic.ttf : No FontName. Skipping.
C:\Windows\Fonts\MesloLGMNerdFontPropo-Regular.ttf : No FontName. Skipping.
C:\Windows\Fonts\MesloLGSDZNerdFont-Bold.ttf : No FontName. Skipping.
C:\Windows\Fonts\MesloLGSDZNerdFont-BoldItalic.ttf : No FontName. Skipping.
C:\Windows\Fonts\MesloLGSDZNerdFont-Italic.ttf : No FontName. Skipping.
C:\Windows\Fonts\MesloLGSDZNerdFont-Regular.ttf : No FontName. Skipping.
C:\Windows\Fonts\MesloLGSDZNerdFontMono-Bold.ttf : No FontName. Skipping.
C:\Windows\Fonts\MesloLGSDZNerdFontMono-BoldItalic.ttf : No FontName. Skipping.
C:\Windows\Fonts\MesloLGSDZNerdFontMono-Italic.ttf : No FontName. Skipping.
C:\Windows\Fonts\MesloLGSDZNerdFontMono-Regular.ttf : No FontName. Skipping.
C:\Windows\Fonts\MesloLGSDZNerdFontPropo-Bold.ttf : No FontName. Skipping.
C:\Windows\Fonts\MesloLGSDZNerdFontPropo-BoldItalic.ttf : No FontName. Skipping.
C:\Windows\Fonts\MesloLGSDZNerdFontPropo-Italic.ttf : No FontName. Skipping.
C:\Windows\Fonts\MesloLGSDZNerdFontPropo-Regular.ttf : No FontName. Skipping.
C:\Windows\Fonts\MesloLGSNerdFont-Bold.ttf : No FontName. Skipping.
C:\Windows\Fonts\MesloLGSNerdFont-BoldItalic.ttf : No FontName. Skipping.
C:\Windows\Fonts\MesloLGSNerdFont-Italic.ttf : No FontName. Skipping.
C:\Windows\Fonts\MesloLGSNerdFont-Regular.ttf : No FontName. Skipping.
C:\Windows\Fonts\MesloLGSNerdFontMono-Bold.ttf : No FontName. Skipping.
C:\Windows\Fonts\MesloLGSNerdFontMono-BoldItalic.ttf : No FontName. Skipping.
C:\Windows\Fonts\MesloLGSNerdFontMono-Italic.ttf : No FontName. Skipping.
C:\Windows\Fonts\MesloLGSNerdFontMono-Regular.ttf : No FontName. Skipping.
C:\Windows\Fonts\MesloLGSNerdFontPropo-Bold.ttf : No FontName. Skipping.
C:\Windows\Fonts\MesloLGSNerdFontPropo-BoldItalic.ttf : No FontName. Skipping.
C:\Windows\Fonts\MesloLGSNerdFontPropo-Italic.ttf : No FontName. Skipping.
C:\Windows\Fonts\MesloLGSNerdFontPropo-Regular.ttf : No FontName. Skipping.
C:\Windows\Fonts\micross.ttf => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/micross
C:\Windows\Fonts\MISTRAL.TTF => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/MISTRAL
C:\Windows\Fonts\mmrtext.ttf => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/mmrtext
C:\Windows\Fonts\mmrtextb.ttf => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/mmrtextb
C:\Windows\Fonts\MOD20.TTF => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/MOD20
C:\Windows\Fonts\monbaiti.ttf => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/monbaiti
C:\Windows\Fonts\mriam.ttf => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/mriam
C:\Windows\Fonts\mriamc.ttf => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/mriamc
C:\Windows\Fonts\msuighub.ttf => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/msuighub
C:\Windows\Fonts\msuighur.ttf => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/msuighur
C:\Windows\Fonts\msyi.ttf => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/msyi
C:\Windows\Fonts\MTCORSVA.TTF => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/MTCORSVA
C:\Windows\Fonts\MTEXTRA.TTF => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/MTEXTRA
C:\Windows\Fonts\mvboli.ttf => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/mvboli
C:\Windows\Fonts\NIAGENG.TTF => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/NIAGENG
C:\Windows\Fonts\NIAGSOL.TTF => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/NIAGSOL
C:\Windows\Fonts\Nirmala.ttf => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/Nirmala
C:\Windows\Fonts\NirmalaB.ttf => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/NirmalaB
C:\Windows\Fonts\NirmalaS.ttf => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/NirmalaS
C:\Windows\Fonts\nrkis.ttf => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/nrkis
C:\Windows\Fonts\ntailu.ttf => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/ntailu
C:\Windows\Fonts\ntailub.ttf => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/ntailub
C:\Windows\Fonts\nyala.ttf => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/nyala
C:\Windows\Fonts\OCRAEXT.TTF => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/OCRAEXT
C:\Windows\Fonts\OLDENGL.TTF => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/OLDENGL
C:\Windows\Fonts\ONYX.TTF => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/ONYX
C:\Windows\Fonts\OUTLOOK.TTF => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/OUTLOOK
C:\Windows\Fonts\pala.ttf => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/pala
C:\Windows\Fonts\palab.ttf => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/palab
C:\Windows\Fonts\palabi.ttf => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/palabi
C:\Windows\Fonts\palai.ttf => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/palai
C:\Windows\Fonts\PALSCRI.TTF => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/PALSCRI
C:\Windows\Fonts\PAPYRUS.TTF => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/PAPYRUS
C:\Windows\Fonts\PARCHM.TTF => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/PARCHM
C:\Windows\Fonts\PER_____.TTF => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/PER_____
C:\Windows\Fonts\PERB____.TTF => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/PERB____
C:\Windows\Fonts\PERBI___.TTF => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/PERBI___
C:\Windows\Fonts\PERI____.TTF => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/PERI____
C:\Windows\Fonts\PERTIBD.TTF => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/PERTIBD
C:\Windows\Fonts\PERTILI.TTF => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/PERTILI
C:\Windows\Fonts\phagspa.ttf => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/phagspa
C:\Windows\Fonts\phagspab.ttf => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/phagspab
C:\Windows\Fonts\PLAYBILL.TTF => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/PLAYBILL
C:\Windows\Fonts\POORICH.TTF => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/POORICH
C:\Windows\Fonts\PRISTINA.TTF => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/PRISTINA
C:\Windows\Fonts\RAGE.TTF => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/RAGE
C:\Windows\Fonts\RAVIE.TTF => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/RAVIE
C:\Windows\Fonts\REFSAN.TTF => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/REFSAN
C:\Windows\Fonts\REFSPCL.TTF => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/REFSPCL
C:\Windows\Fonts\ROCC____.TTF => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/ROCC____
C:\Windows\Fonts\ROCCB___.TTF => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/ROCCB___
C:\Windows\Fonts\ROCK.TTF => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/ROCK
C:\Windows\Fonts\ROCKB.TTF => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/ROCKB
C:\Windows\Fonts\ROCKBI.TTF => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/ROCKBI
C:\Windows\Fonts\ROCKEB.TTF => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/ROCKEB
C:\Windows\Fonts\ROCKI.TTF => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/ROCKI
C:\Windows\Fonts\rod.ttf => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/rod
C:\Windows\Fonts\SCHLBKB.TTF => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/SCHLBKB
C:\Windows\Fonts\SCHLBKBI.TTF => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/SCHLBKBI
C:\Windows\Fonts\SCHLBKI.TTF => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/SCHLBKI
C:\Windows\Fonts\SCRIPTBL.TTF => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/SCRIPTBL
C:\Windows\Fonts\segmdl2.ttf => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/segmdl2
C:\Windows\Fonts\segoepr.ttf => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/segoepr
C:\Windows\Fonts\segoeprb.ttf => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/segoeprb
C:\Windows\Fonts\segoesc.ttf => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/segoesc
C:\Windows\Fonts\segoescb.ttf => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/segoescb
C:\Windows\Fonts\segoeui.ttf => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/segoeui
C:\Windows\Fonts\segoeuib.ttf => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/segoeuib
C:\Windows\Fonts\segoeuii.ttf => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/segoeuii
C:\Windows\Fonts\segoeuil.ttf => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/segoeuil
C:\Windows\Fonts\segoeuisl.ttf => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/segoeuisl
C:\Windows\Fonts\segoeuiz.ttf => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/segoeuiz
C:\Windows\Fonts\seguibl.ttf => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/seguibl
C:\Windows\Fonts\seguibli.ttf => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/seguibli
C:\Windows\Fonts\seguiemj.ttf => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/seguiemj
C:\Windows\Fonts\seguihis.ttf => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/seguiemj
C:\Windows\Fonts\seguihis.ttf => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/seguihis
C:\Windows\Fonts\seguili.ttf => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/seguili
C:\Windows\Fonts\seguisb.ttf => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/seguisb
C:\Windows\Fonts\seguisbi.ttf => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/seguisbi
C:\Windows\Fonts\seguisli.ttf => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/seguisli
C:\Windows\Fonts\seguisym.ttf => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/seguisym
C:\Windows\Fonts\SHOWG.TTF => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/SHOWG
C:\Windows\Fonts\simpbdo.ttf => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/simpbdo
C:\Windows\Fonts\simpfxo.ttf => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/simpfxo
C:\Windows\Fonts\simpo.ttf => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/simpo
C:\Windows\Fonts\simsunb.ttf => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/simsunb
C:\Windows\Fonts\SitkaVF-Italic.ttf => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/SitkaVF-Italic
C:\Windows\Fonts\SitkaVF.ttf => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/SitkaVF
C:\Windows\Fonts\SNAP____.TTF => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/SNAP____
C:\Windows\Fonts\STENCIL.TTF => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/STENCIL
C:\Windows\Fonts\sylfaen.ttf => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/sylfaen
C:\Windows\Fonts\symbol.ttf => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/symbol
C:\Windows\Fonts\tahoma.ttf => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/tahoma
C:\Windows\Fonts\tahomabd.ttf => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/tahomabd
C:\Windows\Fonts\taile.ttf => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/taile
C:\Windows\Fonts\taileb.ttf => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/taileb
C:\Windows\Fonts\TCB_____.TTF => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/TCB_____
C:\Windows\Fonts\TCBI____.TTF => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/TCBI____
C:\Windows\Fonts\TCCB____.TTF => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/TCCB____
C:\Windows\Fonts\TCCEB.TTF => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/TCCEB
C:\Windows\Fonts\TCCM____.TTF => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/TCCM____
C:\Windows\Fonts\TCM_____.TTF => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/TCM_____
C:\Windows\Fonts\TCMI____.TTF => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/TCMI____
C:\Windows\Fonts\TEMPSITC.TTF => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/TEMPSITC
C:\Windows\Fonts\times.ttf => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/times
C:\Windows\Fonts\timesbd.ttf => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/timesbd
C:\Windows\Fonts\timesbi.ttf => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/timesbi
C:\Windows\Fonts\timesi.ttf => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/timesi
C:\Windows\Fonts\tradbdo.ttf => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/tradbdo
C:\Windows\Fonts\trado.ttf => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/trado
C:\Windows\Fonts\trebuc.ttf => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/trebuc
C:\Windows\Fonts\trebucbd.ttf => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/trebucbd
C:\Windows\Fonts\trebucbi.ttf => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/trebucbi
C:\Windows\Fonts\trebucit.ttf => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/trebucit
C:\Windows\Fonts\UbuntuMono-R.ttf => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/UbuntuMono-R
C:\Windows\Fonts\UrdType.ttf => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/UrdType
C:\Windows\Fonts\UrdTypeb.ttf => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/UrdTypeb
C:\Windows\Fonts\verdana.ttf => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/verdana
C:\Windows\Fonts\verdanab.ttf => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/verdanab
C:\Windows\Fonts\verdanai.ttf => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/verdanai
C:\Windows\Fonts\verdanaz.ttf => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/verdanaz
C:\Windows\Fonts\VINERITC.TTF => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/VINERITC
C:\Windows\Fonts\VIVALDII.TTF => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/VIVALDII
C:\Windows\Fonts\VLADIMIR.TTF => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/VLADIMIR
C:\Windows\Fonts\webdings.ttf => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/webdings
C:\Windows\Fonts\wingding.ttf => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/wingding
C:\Windows\Fonts\WINGDNG2.TTF => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/WINGDNG2
C:\Windows\Fonts\WINGDNG3.TTF => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/WINGDNG3
Found FontName for 349 fonts.
Scanning afm files in C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics
Writing font table in C:/ProgramData/R/R-4.4.0/library/extrafontdb/fontmap/fonttable.csv
Writing Fontmap to C:/ProgramData/R/R-4.4.0/library/extrafontdb/fontmap/Fontmap...



************************************************************************************

***                  This is my output at runtime                               ***


> install.packages("Rttf2pt1")
trying URL 'https://cran.rstudio.com/bin/windows/contrib/4.4/Rttf2pt1_1.3.12.zip'
Content type 'application/zip' length 152377 bytes (148 KB)
downloaded 148 KB

package ‘Rttf2pt1’ successfully unpacked and MD5 sums checked

The downloaded binary packages are in
C:\Users\Administrator\tmp\3\RtmpimaZoi\downloaded_packages
> library(Rttf2pt1)
There were 14 warnings (use warnings() to see them)
>  warnings()
Warning messages:
  1: In grid.Call(C_textBounds, as.graphicsAnnot(x$label),  ... :
                    font family not found in Windows font database
                  2: In grid.Call(C_textBounds, as.graphicsAnnot(x$label),  ... :
                                    font family not found in Windows font database
                                  3: In grid.Call(C_textBounds, as.graphicsAnnot(x$label),  ... :
                                                    font family not found in Windows font database
                                                  4: In grid.Call.graphics(C_text, as.graphicsAnnot(x$label),  ... :
                                                                             font family not found in Windows font database
                                                                           5: In grid.Call.graphics(C_text, as.graphicsAnnot(x$label),  ... :
                                                                                                      font family not found in Windows font database
                                                                                                    6: In grid.Call.graphics(C_text, as.graphicsAnnot(x$label),  ... :
                                                                                                                               font family not found in Windows font database
                                                                                                                             7: In grid.Call.graphics(C_text, as.graphicsAnnot(x$label),  ... :
                                                                                                                                                        font family not found in Windows font database
                                                                                                                                                      8: In grid.Call(C_textBounds, as.graphicsAnnot(x$label),  ... :
                                                                                                                                                                        font family not found in Windows font database
                                                                                                                                                                      9: In grid.Call(C_textBounds, as.graphicsAnnot(x$label),  ... :
                                                                                                                                                                                        font family not found in Windows font database
                                                                                                                                                                                      10: In grid.Call(C_textBounds, as.graphicsAnnot(x$label),  ... :
                                                                                                                                                                                                         font family not found in Windows font database
                                                                                                                                                                                                       11: In grid.Call.graphics(C_text, as.graphicsAnnot(x$label),  ... :
                                                                                                                                                                                                                                   font family not found in Windows font database
                                                                                                                                                                                                                                 12: In grid.Call.graphics(C_text, as.graphicsAnnot(x$label),  ... :
                                                                                                                                                                                                                                                             font family not found in Windows font database
                                                                                                                                                                                                                                                           13: In grid.Call.graphics(C_text, as.graphicsAnnot(x$label),  ... :
                                                                                                                                                                                                                                                                                       font family not found in Windows font database
                                                                                                                                                                                                                                                                                     14: In grid.Call.graphics(C_text, as.graphicsAnnot(x$label),  ... :
                                                                                                                                                                                                                                                                                                                 font family not found in Windows font database
                                                                                                                                                                                                                                                                                                               > extrafont::font_import()
                                                                                                                                                                                                                                                                                                               Importing fonts may take a few minutes, depending on the number of fonts and the speed of the system.
                                                                                                                                                                                                                                                                                                               Continue? [y/n] y
                                                                                                                                                                                                                                                                                                               Scanning ttf files in C:\Windows/Fonts, C:\Users\Administrator\AppData\Local/Microsoft/Windows/Fonts ...
                                                                                                                                                                                                                                                                                                               Extracting .afm files from .ttf files...
                                                                                                                                                                                                                                                                                                               C:\Windows\Fonts\AGENCYB.TTF => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/AGENCYB
                                                                                                                                                                                                                                                                                                               C:\Windows\Fonts\AGENCYR.TTF => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/AGENCYR
                                                                                                                                                                                                                                                                                                               C:\Windows\Fonts\ahronbd.ttf => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/ahronbd
                                                                                                                                                                                                                                                                                                               C:\Windows\Fonts\aldhabi.ttf => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/aldhabi
                                                                                                                                                                                                                                                                                                               C:\Windows\Fonts\ALGER.TTF => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/ALGER
                                                                                                                                                                                                                                                                                                               C:\Windows\Fonts\andlso.ttf => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/andlso
                                                                                                                                                                                                                                                                                                               C:\Windows\Fonts\ANTQUAB.TTF => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/ANTQUAB
                                                                                                                                                                                                                                                                                                               C:\Windows\Fonts\ANTQUABI.TTF => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/ANTQUABI
                                                                                                                                                                                                                                                                                                               C:\Windows\Fonts\ANTQUAI.TTF => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/ANTQUAI
                                                                                                                                                                                                                                                                                                               C:\Windows\Fonts\arabtype.ttf : No FontName. Skipping.
                                                                                                                                                                                                                                                                                                               C:\Windows\Fonts\arial.ttf => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/arial
                                                                                                                                                                                                                                                                                                               C:\Windows\Fonts\arialbd.ttf => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/arialbd
                                                                                                                                                                                                                                                                                                               C:\Windows\Fonts\arialbi.ttf => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/arialbi
                                                                                                                                                                                                                                                                                                               C:\Windows\Fonts\ariali.ttf => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/ariali
                                                                                                                                                                                                                                                                                                               C:\Windows\Fonts\ARIALN.TTF => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/ARIALN
                                                                                                                                                                                                                                                                                                               C:\Windows\Fonts\ARIALNB.TTF => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/ARIALNB
                                                                                                                                                                                                                                                                                                               C:\Windows\Fonts\ARIALNBI.TTF => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/ARIALNBI
                                                                                                                                                                                                                                                                                                               C:\Windows\Fonts\ARIALNI.TTF => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/ARIALNI
                                                                                                                                                                                                                                                                                                               C:\Windows\Fonts\ariblk.ttf => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/ariblk
                                                                                                                                                                                                                                                                                                               C:\Windows\Fonts\ARLRDBD.TTF => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/ARLRDBD
                                                                                                                                                                                                                                                                                                               C:\Windows\Fonts\bahnschrift.ttf => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/bahnschrift
                                                                                                                                                                                                                                                                                                               C:\Windows\Fonts\BASKVILL.TTF => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/BASKVILL
                                                                                                                                                                                                                                                                                                               C:\Windows\Fonts\BAUHS93.TTF => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/BAUHS93
                                                                                                                                                                                                                                                                                                               C:\Windows\Fonts\BELL.TTF => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/BELL
                                                                                                                                                                                                                                                                                                               C:\Windows\Fonts\BELLB.TTF => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/BELLB
                                                                                                                                                                                                                                                                                                               C:\Windows\Fonts\BELLI.TTF => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/BELLI
                                                                                                                                                                                                                                                                                                               C:\Windows\Fonts\BERNHC.TTF => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/BERNHC
                                                                                                                                                                                                                                                                                                               C:\Windows\Fonts\BKANT.TTF => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/BKANT
                                                                                                                                                                                                                                                                                                               C:\Windows\Fonts\BOD_B.TTF => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/BOD_B
                                                                                                                                                                                                                                                                                                               C:\Windows\Fonts\BOD_BI.TTF => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/BOD_BI
                                                                                                                                                                                                                                                                                                               C:\Windows\Fonts\BOD_BLAI.TTF => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/BOD_BLAI
                                                                                                                                                                                                                                                                                                               C:\Windows\Fonts\BOD_BLAR.TTF => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/BOD_BLAR
                                                                                                                                                                                                                                                                                                               C:\Windows\Fonts\BOD_CB.TTF => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/BOD_CB
                                                                                                                                                                                                                                                                                                               C:\Windows\Fonts\BOD_CBI.TTF => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/BOD_CBI
                                                                                                                                                                                                                                                                                                               C:\Windows\Fonts\BOD_CI.TTF => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/BOD_CI
                                                                                                                                                                                                                                                                                                               C:\Windows\Fonts\BOD_CR.TTF => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/BOD_CR
                                                                                                                                                                                                                                                                                                               C:\Windows\Fonts\BOD_I.TTF => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/BOD_I
                                                                                                                                                                                                                                                                                                               C:\Windows\Fonts\BOD_PSTC.TTF => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/BOD_PSTC
                                                                                                                                                                                                                                                                                                               C:\Windows\Fonts\BOD_R.TTF => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/BOD_R
                                                                                                                                                                                                                                                                                                               C:\Windows\Fonts\BOOKOS.TTF => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/BOOKOS
                                                                                                                                                                                                                                                                                                               C:\Windows\Fonts\BOOKOSB.TTF => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/BOOKOSB
                                                                                                                                                                                                                                                                                                               C:\Windows\Fonts\BOOKOSBI.TTF => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/BOOKOSBI
                                                                                                                                                                                                                                                                                                               C:\Windows\Fonts\BOOKOSI.TTF => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/BOOKOSI
                                                                                                                                                                                                                                                                                                               C:\Windows\Fonts\BRADHITC.TTF => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/BRADHITC
                                                                                                                                                                                                                                                                                                               C:\Windows\Fonts\BRITANIC.TTF => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/BRITANIC
                                                                                                                                                                                                                                                                                                               C:\Windows\Fonts\BRLNSB.TTF => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/BRLNSB
                                                                                                                                                                                                                                                                                                               C:\Windows\Fonts\BRLNSDB.TTF => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/BRLNSDB
                                                                                                                                                                                                                                                                                                               C:\Windows\Fonts\BRLNSR.TTF => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/BRLNSR
                                                                                                                                                                                                                                                                                                               C:\Windows\Fonts\BROADW.TTF => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/BROADW
                                                                                                                                                                                                                                                                                                               C:\Windows\Fonts\BRUSHSCI.TTF => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/BRUSHSCI
                                                                                                                                                                                                                                                                                                               C:\Windows\Fonts\BSSYM7.TTF => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/BSSYM7
                                                                                                                                                                                                                                                                                                               C:\Windows\Fonts\calibri.ttf => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/calibri
                                                                                                                                                                                                                                                                                                               C:\Windows\Fonts\calibrib.ttf => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/calibrib
                                                                                                                                                                                                                                                                                                               C:\Windows\Fonts\calibrii.ttf => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/calibrii
                                                                                                                                                                                                                                                                                                               C:\Windows\Fonts\calibril.ttf => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/calibril
                                                                                                                                                                                                                                                                                                               C:\Windows\Fonts\calibrili.ttf => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/calibrili
                                                                                                                                                                                                                                                                                                               C:\Windows\Fonts\calibriz.ttf => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/calibriz
                                                                                                                                                                                                                                                                                                               C:\Windows\Fonts\CALIFB.TTF => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/CALIFB
                                                                                                                                                                                                                                                                                                               C:\Windows\Fonts\CALIFI.TTF => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/CALIFI
                                                                                                                                                                                                                                                                                                               C:\Windows\Fonts\CALIFR.TTF => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/CALIFR
                                                                                                                                                                                                                                                                                                               C:\Windows\Fonts\CALIST.TTF => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/CALIST
                                                                                                                                                                                                                                                                                                               C:\Windows\Fonts\CALISTB.TTF => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/CALISTB
                                                                                                                                                                                                                                                                                                               C:\Windows\Fonts\CALISTBI.TTF => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/CALISTBI
                                                                                                                                                                                                                                                                                                               C:\Windows\Fonts\CALISTI.TTF => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/CALISTI
                                                                                                                                                                                                                                                                                                               C:\Windows\Fonts\cambriab.ttf => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/cambriab
                                                                                                                                                                                                                                                                                                               C:\Windows\Fonts\cambriai.ttf => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/cambriai
                                                                                                                                                                                                                                                                                                               C:\Windows\Fonts\cambriaz.ttf => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/cambriaz
                                                                                                                                                                                                                                                                                                               C:\Windows\Fonts\Candara.ttf => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/Candara
                                                                                                                                                                                                                                                                                                               C:\Windows\Fonts\Candarab.ttf => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/Candarab
                                                                                                                                                                                                                                                                                                               C:\Windows\Fonts\Candarai.ttf => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/Candarai
                                                                                                                                                                                                                                                                                                               C:\Windows\Fonts\Candaral.ttf => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/Candaral
                                                                                                                                                                                                                                                                                                               C:\Windows\Fonts\Candarali.ttf => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/Candarali
                                                                                                                                                                                                                                                                                                               C:\Windows\Fonts\Candaraz.ttf => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/Candaraz
                                                                                                                                                                                                                                                                                                               C:\Windows\Fonts\CascadiaCode.ttf => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/CascadiaCode
                                                                                                                                                                                                                                                                                                               C:\Windows\Fonts\CascadiaMono.ttf => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/CascadiaMono
                                                                                                                                                                                                                                                                                                               C:\Windows\Fonts\CASTELAR.TTF => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/CASTELAR
                                                                                                                                                                                                                                                                                                               C:\Windows\Fonts\CENSCBK.TTF => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/CENSCBK
                                                                                                                                                                                                                                                                                                               C:\Windows\Fonts\CENTAUR.TTF => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/CENTAUR
                                                                                                                                                                                                                                                                                                               C:\Windows\Fonts\CENTURY.TTF => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/CENTURY
                                                                                                                                                                                                                                                                                                               C:\Windows\Fonts\CHILLER.TTF => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/CHILLER
                                                                                                                                                                                                                                                                                                               C:\Windows\Fonts\COLONNA.TTF => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/COLONNA
                                                                                                                                                                                                                                                                                                               C:\Windows\Fonts\comic.ttf => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/comic
                                                                                                                                                                                                                                                                                                               C:\Windows\Fonts\comicbd.ttf => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/comicbd
                                                                                                                                                                                                                                                                                                               C:\Windows\Fonts\comici.ttf => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/comici
                                                                                                                                                                                                                                                                                                               C:\Windows\Fonts\comicz.ttf => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/comicz
                                                                                                                                                                                                                                                                                                               C:\Windows\Fonts\consola.ttf => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/consola
                                                                                                                                                                                                                                                                                                               C:\Windows\Fonts\consolab.ttf => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/consolab
                                                                                                                                                                                                                                                                                                               C:\Windows\Fonts\consolai.ttf => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/consolai
                                                                                                                                                                                                                                                                                                               C:\Windows\Fonts\consolaz.ttf => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/consolaz
                                                                                                                                                                                                                                                                                                               C:\Windows\Fonts\constan.ttf => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/constan
                                                                                                                                                                                                                                                                                                               C:\Windows\Fonts\constanb.ttf => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/constanb
                                                                                                                                                                                                                                                                                                               C:\Windows\Fonts\constani.ttf => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/constani
                                                                                                                                                                                                                                                                                                               C:\Windows\Fonts\constanz.ttf => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/constanz
                                                                                                                                                                                                                                                                                                               C:\Windows\Fonts\COOPBL.TTF => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/COOPBL
                                                                                                                                                                                                                                                                                                               C:\Windows\Fonts\COPRGTB.TTF => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/COPRGTB
                                                                                                                                                                                                                                                                                                               C:\Windows\Fonts\COPRGTL.TTF => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/COPRGTL
                                                                                                                                                                                                                                                                                                               C:\Windows\Fonts\corbel.ttf => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/corbel
                                                                                                                                                                                                                                                                                                               C:\Windows\Fonts\corbelb.ttf => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/corbelb
                                                                                                                                                                                                                                                                                                               C:\Windows\Fonts\corbeli.ttf => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/corbeli
                                                                                                                                                                                                                                                                                                               C:\Windows\Fonts\corbell.ttf => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/corbell
                                                                                                                                                                                                                                                                                                               C:\Windows\Fonts\corbelli.ttf => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/corbelli
                                                                                                                                                                                                                                                                                                               C:\Windows\Fonts\corbelz.ttf => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/corbelz
                                                                                                                                                                                                                                                                                                               C:\Windows\Fonts\cour.ttf => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/cour
                                                                                                                                                                                                                                                                                                               C:\Windows\Fonts\courbd.ttf => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/courbd
                                                                                                                                                                                                                                                                                                               C:\Windows\Fonts\courbi.ttf => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/courbi
                                                                                                                                                                                                                                                                                                               C:\Windows\Fonts\couri.ttf => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/couri
                                                                                                                                                                                                                                                                                                               C:\Windows\Fonts\CURLZ___.TTF => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/CURLZ___
                                                                                                                                                                                                                                                                                                               C:\Windows\Fonts\david.ttf => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/david
                                                                                                                                                                                                                                                                                                               C:\Windows\Fonts\davidbd.ttf => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/davidbd
                                                                                                                                                                                                                                                                                                               C:\Windows\Fonts\DUBAI-BOLD.TTF => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/DUBAI-BOLD
                                                                                                                                                                                                                                                                                                               C:\Windows\Fonts\DUBAI-LIGHT.TTF => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/DUBAI-LIGHT
                                                                                                                                                                                                                                                                                                               C:\Windows\Fonts\DUBAI-MEDIUM.TTF => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/DUBAI-MEDIUM
                                                                                                                                                                                                                                                                                                               C:\Windows\Fonts\DUBAI-REGULAR.TTF => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/DUBAI-REGULAR
                                                                                                                                                                                                                                                                                                               C:\Windows\Fonts\ebrima.ttf => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/ebrima
                                                                                                                                                                                                                                                                                                               C:\Windows\Fonts\ebrimabd.ttf => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/ebrimabd
                                                                                                                                                                                                                                                                                                               C:\Windows\Fonts\ELEPHNT.TTF => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/ELEPHNT
                                                                                                                                                                                                                                                                                                               C:\Windows\Fonts\ELEPHNTI.TTF => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/ELEPHNTI
                                                                                                                                                                                                                                                                                                               C:\Windows\Fonts\ENGR.TTF => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/ENGR
                                                                                                                                                                                                                                                                                                               C:\Windows\Fonts\ERASBD.TTF => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/ERASBD
                                                                                                                                                                                                                                                                                                               C:\Windows\Fonts\ERASDEMI.TTF => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/ERASDEMI
                                                                                                                                                                                                                                                                                                               C:\Windows\Fonts\ERASLGHT.TTF => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/ERASLGHT
                                                                                                                                                                                                                                                                                                               C:\Windows\Fonts\ERASMD.TTF => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/ERASMD
                                                                                                                                                                                                                                                                                                               C:\Windows\Fonts\FELIXTI.TTF => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/FELIXTI
                                                                                                                                                                                                                                                                                                               C:\Windows\Fonts\FORTE.TTF => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/FORTE
                                                                                                                                                                                                                                                                                                               C:\Windows\Fonts\FRABK.TTF => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/FRABK
                                                                                                                                                                                                                                                                                                               C:\Windows\Fonts\FRABKIT.TTF => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/FRABKIT
                                                                                                                                                                                                                                                                                                               C:\Windows\Fonts\FRADM.TTF => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/FRADM
                                                                                                                                                                                                                                                                                                               C:\Windows\Fonts\FRADMCN.TTF => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/FRADMCN
                                                                                                                                                                                                                                                                                                               C:\Windows\Fonts\FRADMIT.TTF => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/FRADMIT
                                                                                                                                                                                                                                                                                                               C:\Windows\Fonts\FRAHV.TTF => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/FRAHV
                                                                                                                                                                                                                                                                                                               C:\Windows\Fonts\FRAHVIT.TTF => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/FRAHVIT
                                                                                                                                                                                                                                                                                                               C:\Windows\Fonts\framd.ttf => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/framd
                                                                                                                                                                                                                                                                                                               C:\Windows\Fonts\FRAMDCN.TTF => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/FRAMDCN
                                                                                                                                                                                                                                                                                                               C:\Windows\Fonts\framdit.ttf => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/framdit
                                                                                                                                                                                                                                                                                                               C:\Windows\Fonts\frank.ttf => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/frank
                                                                                                                                                                                                                                                                                                               C:\Windows\Fonts\FREESCPT.TTF => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/FREESCPT
                                                                                                                                                                                                                                                                                                               C:\Windows\Fonts\FRSCRIPT.TTF => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/FRSCRIPT
                                                                                                                                                                                                                                                                                                               C:\Windows\Fonts\FTLTLT.TTF => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/FTLTLT
                                                                                                                                                                                                                                                                                                               C:\Windows\Fonts\Gabriola.ttf => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/Gabriola
                                                                                                                                                                                                                                                                                                               C:\Windows\Fonts\gadugi.ttf => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/gadugi
                                                                                                                                                                                                                                                                                                               C:\Windows\Fonts\gadugib.ttf => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/gadugib
                                                                                                                                                                                                                                                                                                               C:\Windows\Fonts\GARA.TTF => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/GARA
                                                                                                                                                                                                                                                                                                               C:\Windows\Fonts\GARABD.TTF => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/GARABD
                                                                                                                                                                                                                                                                                                               C:\Windows\Fonts\GARAIT.TTF => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/GARAIT
                                                                                                                                                                                                                                                                                                               C:\Windows\Fonts\georgia.ttf => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/georgia
                                                                                                                                                                                                                                                                                                               C:\Windows\Fonts\georgiab.ttf => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/georgiab
                                                                                                                                                                                                                                                                                                               C:\Windows\Fonts\georgiai.ttf => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/georgiai
                                                                                                                                                                                                                                                                                                               C:\Windows\Fonts\georgiaz.ttf => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/georgiaz
                                                                                                                                                                                                                                                                                                               C:\Windows\Fonts\GIGI.TTF => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/GIGI
                                                                                                                                                                                                                                                                                                               C:\Windows\Fonts\GIL_____.TTF => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/GIL_____
                                                                                                                                                                                                                                                                                                               C:\Windows\Fonts\GILB____.TTF => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/GILB____
                                                                                                                                                                                                                                                                                                               C:\Windows\Fonts\GILBI___.TTF => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/GILBI___
                                                                                                                                                                                                                                                                                                               C:\Windows\Fonts\GILC____.TTF => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/GILC____
                                                                                                                                                                                                                                                                                                               C:\Windows\Fonts\GILI____.TTF => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/GILI____
                                                                                                                                                                                                                                                                                                               C:\Windows\Fonts\GILLUBCD.TTF => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/GILLUBCD
                                                                                                                                                                                                                                                                                                               C:\Windows\Fonts\GILSANUB.TTF => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/GILSANUB
                                                                                                                                                                                                                                                                                                               C:\Windows\Fonts\gisha.ttf => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/gisha
                                                                                                                                                                                                                                                                                                               C:\Windows\Fonts\gishabd.ttf => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/gishabd
                                                                                                                                                                                                                                                                                                               C:\Windows\Fonts\GLECB.TTF => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/GLECB
                                                                                                                                                                                                                                                                                                               C:\Windows\Fonts\GLSNECB.TTF => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/GLSNECB
                                                                                                                                                                                                                                                                                                               C:\Windows\Fonts\GOTHIC.TTF => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/GOTHIC
                                                                                                                                                                                                                                                                                                               C:\Windows\Fonts\GOTHICB.TTF => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/GOTHICB
                                                                                                                                                                                                                                                                                                               C:\Windows\Fonts\GOTHICBI.TTF => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/GOTHICBI
                                                                                                                                                                                                                                                                                                               C:\Windows\Fonts\GOTHICI.TTF => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/GOTHICI
                                                                                                                                                                                                                                                                                                               C:\Windows\Fonts\GOUDOS.TTF => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/GOUDOS
                                                                                                                                                                                                                                                                                                               C:\Windows\Fonts\GOUDOSB.TTF => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/GOUDOSB
                                                                                                                                                                                                                                                                                                               C:\Windows\Fonts\GOUDOSI.TTF => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/GOUDOSI
                                                                                                                                                                                                                                                                                                               C:\Windows\Fonts\GOUDYSTO.TTF => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/GOUDYSTO
                                                                                                                                                                                                                                                                                                               C:\Windows\Fonts\HackNerdFont-Bold.ttf : No FontName. Skipping.
                                                                                                                                                                                                                                                                                                               C:\Windows\Fonts\HackNerdFont-BoldItalic.ttf : No FontName. Skipping.
                                                                                                                                                                                                                                                                                                               C:\Windows\Fonts\HackNerdFont-Italic.ttf : No FontName. Skipping.
                                                                                                                                                                                                                                                                                                               C:\Windows\Fonts\HackNerdFont-Regular.ttf : No FontName. Skipping.
                                                                                                                                                                                                                                                                                                               C:\Windows\Fonts\HackNerdFontMono-Bold.ttf : No FontName. Skipping.
                                                                                                                                                                                                                                                                                                               C:\Windows\Fonts\HackNerdFontMono-BoldItalic.ttf : No FontName. Skipping.
                                                                                                                                                                                                                                                                                                               C:\Windows\Fonts\HackNerdFontMono-Italic.ttf : No FontName. Skipping.
                                                                                                                                                                                                                                                                                                               C:\Windows\Fonts\HackNerdFontMono-Regular.ttf : No FontName. Skipping.
                                                                                                                                                                                                                                                                                                               C:\Windows\Fonts\HackNerdFontPropo-Bold.ttf : No FontName. Skipping.
                                                                                                                                                                                                                                                                                                               C:\Windows\Fonts\HackNerdFontPropo-BoldItalic.ttf : No FontName. Skipping.
                                                                                                                                                                                                                                                                                                               C:\Windows\Fonts\HackNerdFontPropo-Italic.ttf : No FontName. Skipping.
                                                                                                                                                                                                                                                                                                               C:\Windows\Fonts\HackNerdFontPropo-Regular.ttf : No FontName. Skipping.
                                                                                                                                                                                                                                                                                                               C:\Windows\Fonts\HARLOWSI.TTF => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/HARLOWSI
                                                                                                                                                                                                                                                                                                               C:\Windows\Fonts\HARNGTON.TTF => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/HARNGTON
                                                                                                                                                                                                                                                                                                               C:\Windows\Fonts\HATTEN.TTF => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/HATTEN
                                                                                                                                                                                                                                                                                                               C:\Windows\Fonts\HeavyDataNerdFont-Regular.ttf : No FontName. Skipping.
                                                                                                                                                                                                                                                                                                               C:\Windows\Fonts\HeavyDataNerdFontPropo-Regular.ttf : No FontName. Skipping.
                                                                                                                                                                                                                                                                                                               C:\Windows\Fonts\himalaya.ttf => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/himalaya
                                                                                                                                                                                                                                                                                                               C:\Windows\Fonts\HTOWERT.TTF => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/HTOWERT
                                                                                                                                                                                                                                                                                                               C:\Windows\Fonts\HTOWERTI.TTF => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/HTOWERTI
                                                                                                                                                                                                                                                                                                               C:\Windows\Fonts\impact.ttf => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/impact
                                                                                                                                                                                                                                                                                                               C:\Windows\Fonts\IMPRISHA.TTF => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/IMPRISHA
                                                                                                                                                                                                                                                                                                               C:\Windows\Fonts\INFROMAN.TTF => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/INFROMAN
                                                                                                                                                                                                                                                                                                               C:\Windows\Fonts\Inkfree.ttf => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/Inkfree
                                                                                                                                                                                                                                                                                                               C:\Windows\Fonts\ITCBLKAD.TTF => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/ITCBLKAD
                                                                                                                                                                                                                                                                                                               C:\Windows\Fonts\ITCEDSCR.TTF => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/ITCEDSCR
                                                                                                                                                                                                                                                                                                               C:\Windows\Fonts\ITCKRIST.TTF => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/ITCKRIST
                                                                                                                                                                                                                                                                                                               C:\Windows\Fonts\javatext.ttf => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/javatext
                                                                                                                                                                                                                                                                                                               C:\Windows\Fonts\JOKERMAN.TTF => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/JOKERMAN
                                                                                                                                                                                                                                                                                                               C:\Windows\Fonts\JUICE___.TTF => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/JUICE___
                                                                                                                                                                                                                                                                                                               C:\Windows\Fonts\KUNSTLER.TTF => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/KUNSTLER
                                                                                                                                                                                                                                                                                                               C:\Windows\Fonts\l_10646.ttf => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/l_10646
                                                                                                                                                                                                                                                                                                               C:\Windows\Fonts\LATINWD.TTF => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/LATINWD
                                                                                                                                                                                                                                                                                                               C:\Windows\Fonts\LBRITE.TTF => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/LBRITE
                                                                                                                                                                                                                                                                                                               C:\Windows\Fonts\LBRITED.TTF => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/LBRITED
                                                                                                                                                                                                                                                                                                               C:\Windows\Fonts\LBRITEDI.TTF => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/LBRITEDI
                                                                                                                                                                                                                                                                                                               C:\Windows\Fonts\LBRITEI.TTF => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/LBRITEI
                                                                                                                                                                                                                                                                                                               C:\Windows\Fonts\LCALLIG.TTF => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/LCALLIG
                                                                                                                                                                                                                                                                                                               C:\Windows\Fonts\LeelaUIb.ttf => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/LeelaUIb
                                                                                                                                                                                                                                                                                                               C:\Windows\Fonts\LEELAWAD.TTF => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/LEELAWAD
                                                                                                                                                                                                                                                                                                               C:\Windows\Fonts\LEELAWDB.TTF => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/LEELAWDB
                                                                                                                                                                                                                                                                                                               C:\Windows\Fonts\LeelawUI.ttf => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/LeelawUI
                                                                                                                                                                                                                                                                                                               C:\Windows\Fonts\LeelUIsl.ttf => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/LeelUIsl
                                                                                                                                                                                                                                                                                                               C:\Windows\Fonts\LFAX.TTF => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/LFAX
                                                                                                                                                                                                                                                                                                               C:\Windows\Fonts\LFAXD.TTF => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/LFAXD
                                                                                                                                                                                                                                                                                                               C:\Windows\Fonts\LFAXDI.TTF => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/LFAXDI
                                                                                                                                                                                                                                                                                                               C:\Windows\Fonts\LFAXI.TTF => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/LFAXI
                                                                                                                                                                                                                                                                                                               C:\Windows\Fonts\LHANDW.TTF => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/LHANDW
                                                                                                                                                                                                                                                                                                               C:\Windows\Fonts\LSANS.TTF => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/LSANS
                                                                                                                                                                                                                                                                                                               C:\Windows\Fonts\LSANSD.TTF => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/LSANSD
                                                                                                                                                                                                                                                                                                               C:\Windows\Fonts\LSANSDI.TTF => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/LSANSDI
                                                                                                                                                                                                                                                                                                               C:\Windows\Fonts\LSANSI.TTF => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/LSANSI
                                                                                                                                                                                                                                                                                                               C:\Windows\Fonts\LTYPE.TTF => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/LTYPE
                                                                                                                                                                                                                                                                                                               C:\Windows\Fonts\LTYPEB.TTF => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/LTYPEB
                                                                                                                                                                                                                                                                                                               C:\Windows\Fonts\LTYPEBO.TTF => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/LTYPEBO
                                                                                                                                                                                                                                                                                                               C:\Windows\Fonts\LTYPEO.TTF => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/LTYPEO
                                                                                                                                                                                                                                                                                                               C:\Windows\Fonts\lucon.ttf => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/lucon
                                                                                                                                                                                                                                                                                                               C:\Windows\Fonts\lvnm.ttf => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/lvnm
                                                                                                                                                                                                                                                                                                               C:\Windows\Fonts\lvnmbd.ttf => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/lvnmbd
                                                                                                                                                                                                                                                                                                               C:\Windows\Fonts\MAGNETOB.TTF => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/MAGNETOB
                                                                                                                                                                                                                                                                                                               C:\Windows\Fonts\MAIAN.TTF => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/MAIAN
                                                                                                                                                                                                                                                                                                               C:\Windows\Fonts\majalla.ttf => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/majalla
                                                                                                                                                                                                                                                                                                               C:\Windows\Fonts\majallab.ttf => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/majallab
                                                                                                                                                                                                                                                                                                               C:\Windows\Fonts\malgun.ttf => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/malgun
                                                                                                                                                                                                                                                                                                               C:\Windows\Fonts\malgunbd.ttf => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/malgunbd
                                                                                                                                                                                                                                                                                                               C:\Windows\Fonts\malgunsl.ttf => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/malgunsl
                                                                                                                                                                                                                                                                                                               C:\Windows\Fonts\marlett.ttf => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/marlett
                                                                                                                                                                                                                                                                                                               C:\Windows\Fonts\MATURASC.TTF => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/MATURASC
                                                                                                                                                                                                                                                                                                               C:\Windows\Fonts\MesloLGLDZNerdFont-Bold.ttf : No FontName. Skipping.
                                                                                                                                                                                                                                                                                                               C:\Windows\Fonts\MesloLGLDZNerdFont-BoldItalic.ttf : No FontName. Skipping.
                                                                                                                                                                                                                                                                                                               C:\Windows\Fonts\MesloLGLDZNerdFont-Italic.ttf : No FontName. Skipping.
                                                                                                                                                                                                                                                                                                               C:\Windows\Fonts\MesloLGLDZNerdFont-Regular.ttf : No FontName. Skipping.
                                                                                                                                                                                                                                                                                                               C:\Windows\Fonts\MesloLGLDZNerdFontMono-Bold.ttf : No FontName. Skipping.
                                                                                                                                                                                                                                                                                                               C:\Windows\Fonts\MesloLGLDZNerdFontMono-BoldItalic.ttf : No FontName. Skipping.
                                                                                                                                                                                                                                                                                                               C:\Windows\Fonts\MesloLGLDZNerdFontMono-Italic.ttf : No FontName. Skipping.
                                                                                                                                                                                                                                                                                                               C:\Windows\Fonts\MesloLGLDZNerdFontMono-Regular.ttf : No FontName. Skipping.
                                                                                                                                                                                                                                                                                                               C:\Windows\Fonts\MesloLGLDZNerdFontPropo-Bold.ttf : No FontName. Skipping.
                                                                                                                                                                                                                                                                                                               C:\Windows\Fonts\MesloLGLDZNerdFontPropo-BoldItalic.ttf : No FontName. Skipping.
                                                                                                                                                                                                                                                                                                               C:\Windows\Fonts\MesloLGLDZNerdFontPropo-Italic.ttf : No FontName. Skipping.
                                                                                                                                                                                                                                                                                                               C:\Windows\Fonts\MesloLGLDZNerdFontPropo-Regular.ttf : No FontName. Skipping.
                                                                                                                                                                                                                                                                                                               C:\Windows\Fonts\MesloLGLNerdFont-Bold.ttf : No FontName. Skipping.
                                                                                                                                                                                                                                                                                                               C:\Windows\Fonts\MesloLGLNerdFont-BoldItalic.ttf : No FontName. Skipping.
                                                                                                                                                                                                                                                                                                               C:\Windows\Fonts\MesloLGLNerdFont-Italic.ttf : No FontName. Skipping.
                                                                                                                                                                                                                                                                                                               C:\Windows\Fonts\MesloLGLNerdFont-Regular.ttf : No FontName. Skipping.
                                                                                                                                                                                                                                                                                                               C:\Windows\Fonts\MesloLGLNerdFontMono-Bold.ttf : No FontName. Skipping.
                                                                                                                                                                                                                                                                                                               C:\Windows\Fonts\MesloLGLNerdFontMono-BoldItalic.ttf : No FontName. Skipping.
                                                                                                                                                                                                                                                                                                               C:\Windows\Fonts\MesloLGLNerdFontMono-Italic.ttf : No FontName. Skipping.
                                                                                                                                                                                                                                                                                                               C:\Windows\Fonts\MesloLGLNerdFontMono-Regular.ttf : No FontName. Skipping.
                                                                                                                                                                                                                                                                                                               C:\Windows\Fonts\MesloLGLNerdFontPropo-Bold.ttf : No FontName. Skipping.
                                                                                                                                                                                                                                                                                                               C:\Windows\Fonts\MesloLGLNerdFontPropo-BoldItalic.ttf : No FontName. Skipping.
                                                                                                                                                                                                                                                                                                               C:\Windows\Fonts\MesloLGLNerdFontPropo-Italic.ttf : No FontName. Skipping.
                                                                                                                                                                                                                                                                                                               C:\Windows\Fonts\MesloLGLNerdFontPropo-Regular.ttf : No FontName. Skipping.
                                                                                                                                                                                                                                                                                                               C:\Windows\Fonts\MesloLGMDZNerdFont-Bold.ttf : No FontName. Skipping.
                                                                                                                                                                                                                                                                                                               C:\Windows\Fonts\MesloLGMDZNerdFont-BoldItalic.ttf : No FontName. Skipping.
                                                                                                                                                                                                                                                                                                               C:\Windows\Fonts\MesloLGMDZNerdFont-Italic.ttf : No FontName. Skipping.
                                                                                                                                                                                                                                                                                                               C:\Windows\Fonts\MesloLGMDZNerdFont-Regular.ttf : No FontName. Skipping.
                                                                                                                                                                                                                                                                                                               C:\Windows\Fonts\MesloLGMDZNerdFontMono-Bold.ttf : No FontName. Skipping.
                                                                                                                                                                                                                                                                                                               C:\Windows\Fonts\MesloLGMDZNerdFontMono-BoldItalic.ttf : No FontName. Skipping.
                                                                                                                                                                                                                                                                                                               C:\Windows\Fonts\MesloLGMDZNerdFontMono-Italic.ttf : No FontName. Skipping.
                                                                                                                                                                                                                                                                                                               C:\Windows\Fonts\MesloLGMDZNerdFontMono-Regular.ttf : No FontName. Skipping.
                                                                                                                                                                                                                                                                                                               C:\Windows\Fonts\MesloLGMDZNerdFontPropo-Bold.ttf : No FontName. Skipping.
                                                                                                                                                                                                                                                                                                               C:\Windows\Fonts\MesloLGMDZNerdFontPropo-BoldItalic.ttf : No FontName. Skipping.
                                                                                                                                                                                                                                                                                                               C:\Windows\Fonts\MesloLGMDZNerdFontPropo-Italic.ttf : No FontName. Skipping.
                                                                                                                                                                                                                                                                                                               C:\Windows\Fonts\MesloLGMDZNerdFontPropo-Regular.ttf : No FontName. Skipping.
                                                                                                                                                                                                                                                                                                               C:\Windows\Fonts\MesloLGMNerdFont-Bold.ttf : No FontName. Skipping.
                                                                                                                                                                                                                                                                                                               C:\Windows\Fonts\MesloLGMNerdFont-BoldItalic.ttf : No FontName. Skipping.
                                                                                                                                                                                                                                                                                                               C:\Windows\Fonts\MesloLGMNerdFont-Italic.ttf : No FontName. Skipping.
                                                                                                                                                                                                                                                                                                               C:\Windows\Fonts\MesloLGMNerdFont-Regular.ttf : No FontName. Skipping.
                                                                                                                                                                                                                                                                                                               C:\Windows\Fonts\MesloLGMNerdFontMono-Bold.ttf : No FontName. Skipping.
                                                                                                                                                                                                                                                                                                               C:\Windows\Fonts\MesloLGMNerdFontMono-BoldItalic.ttf : No FontName. Skipping.
                                                                                                                                                                                                                                                                                                               C:\Windows\Fonts\MesloLGMNerdFontMono-Italic.ttf : No FontName. Skipping.
                                                                                                                                                                                                                                                                                                               C:\Windows\Fonts\MesloLGMNerdFontMono-Regular.ttf : No FontName. Skipping.
                                                                                                                                                                                                                                                                                                               C:\Windows\Fonts\MesloLGMNerdFontPropo-Bold.ttf : No FontName. Skipping.
                                                                                                                                                                                                                                                                                                               C:\Windows\Fonts\MesloLGMNerdFontPropo-BoldItalic.ttf : No FontName. Skipping.
                                                                                                                                                                                                                                                                                                               C:\Windows\Fonts\MesloLGMNerdFontPropo-Italic.ttf : No FontName. Skipping.
                                                                                                                                                                                                                                                                                                               C:\Windows\Fonts\MesloLGMNerdFontPropo-Regular.ttf : No FontName. Skipping.
                                                                                                                                                                                                                                                                                                               C:\Windows\Fonts\MesloLGSDZNerdFont-Bold.ttf : No FontName. Skipping.
                                                                                                                                                                                                                                                                                                               C:\Windows\Fonts\MesloLGSDZNerdFont-BoldItalic.ttf : No FontName. Skipping.
                                                                                                                                                                                                                                                                                                               C:\Windows\Fonts\MesloLGSDZNerdFont-Italic.ttf : No FontName. Skipping.
                                                                                                                                                                                                                                                                                                               C:\Windows\Fonts\MesloLGSDZNerdFont-Regular.ttf : No FontName. Skipping.
                                                                                                                                                                                                                                                                                                               C:\Windows\Fonts\MesloLGSDZNerdFontMono-Bold.ttf : No FontName. Skipping.
                                                                                                                                                                                                                                                                                                               C:\Windows\Fonts\MesloLGSDZNerdFontMono-BoldItalic.ttf : No FontName. Skipping.
                                                                                                                                                                                                                                                                                                               C:\Windows\Fonts\MesloLGSDZNerdFontMono-Italic.ttf : No FontName. Skipping.
                                                                                                                                                                                                                                                                                                               C:\Windows\Fonts\MesloLGSDZNerdFontMono-Regular.ttf : No FontName. Skipping.
                                                                                                                                                                                                                                                                                                               C:\Windows\Fonts\MesloLGSDZNerdFontPropo-Bold.ttf : No FontName. Skipping.
                                                                                                                                                                                                                                                                                                               C:\Windows\Fonts\MesloLGSDZNerdFontPropo-BoldItalic.ttf : No FontName. Skipping.
                                                                                                                                                                                                                                                                                                               C:\Windows\Fonts\MesloLGSDZNerdFontPropo-Italic.ttf : No FontName. Skipping.
                                                                                                                                                                                                                                                                                                               C:\Windows\Fonts\MesloLGSDZNerdFontPropo-Regular.ttf : No FontName. Skipping.
                                                                                                                                                                                                                                                                                                               C:\Windows\Fonts\MesloLGSNerdFont-Bold.ttf : No FontName. Skipping.
                                                                                                                                                                                                                                                                                                               C:\Windows\Fonts\MesloLGSNerdFont-BoldItalic.ttf : No FontName. Skipping.
                                                                                                                                                                                                                                                                                                               C:\Windows\Fonts\MesloLGSNerdFont-Italic.ttf : No FontName. Skipping.
                                                                                                                                                                                                                                                                                                               C:\Windows\Fonts\MesloLGSNerdFont-Regular.ttf : No FontName. Skipping.
                                                                                                                                                                                                                                                                                                               C:\Windows\Fonts\MesloLGSNerdFontMono-Bold.ttf : No FontName. Skipping.
                                                                                                                                                                                                                                                                                                               C:\Windows\Fonts\MesloLGSNerdFontMono-BoldItalic.ttf : No FontName. Skipping.
                                                                                                                                                                                                                                                                                                               C:\Windows\Fonts\MesloLGSNerdFontMono-Italic.ttf : No FontName. Skipping.
                                                                                                                                                                                                                                                                                                               C:\Windows\Fonts\MesloLGSNerdFontMono-Regular.ttf : No FontName. Skipping.
                                                                                                                                                                                                                                                                                                               C:\Windows\Fonts\MesloLGSNerdFontPropo-Bold.ttf : No FontName. Skipping.
                                                                                                                                                                                                                                                                                                               C:\Windows\Fonts\MesloLGSNerdFontPropo-BoldItalic.ttf : No FontName. Skipping.
                                                                                                                                                                                                                                                                                                               C:\Windows\Fonts\MesloLGSNerdFontPropo-Italic.ttf : No FontName. Skipping.
                                                                                                                                                                                                                                                                                                               C:\Windows\Fonts\MesloLGSNerdFontPropo-Regular.ttf : No FontName. Skipping.
                                                                                                                                                                                                                                                                                                               C:\Windows\Fonts\micross.ttf => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/micross
                                                                                                                                                                                                                                                                                                               C:\Windows\Fonts\MISTRAL.TTF => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/MISTRAL
                                                                                                                                                                                                                                                                                                               C:\Windows\Fonts\mmrtext.ttf => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/mmrtext
                                                                                                                                                                                                                                                                                                               C:\Windows\Fonts\mmrtextb.ttf => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/mmrtextb
                                                                                                                                                                                                                                                                                                               C:\Windows\Fonts\MOD20.TTF => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/MOD20
                                                                                                                                                                                                                                                                                                               C:\Windows\Fonts\monbaiti.ttf => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/monbaiti
                                                                                                                                                                                                                                                                                                               C:\Windows\Fonts\mriam.ttf => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/mriam
                                                                                                                                                                                                                                                                                                               C:\Windows\Fonts\mriamc.ttf => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/mriamc
                                                                                                                                                                                                                                                                                                               C:\Windows\Fonts\msuighub.ttf => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/msuighub
                                                                                                                                                                                                                                                                                                               C:\Windows\Fonts\msuighur.ttf => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/msuighur
                                                                                                                                                                                                                                                                                                               C:\Windows\Fonts\msyi.ttf => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/msyi
                                                                                                                                                                                                                                                                                                               C:\Windows\Fonts\MTCORSVA.TTF => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/MTCORSVA
                                                                                                                                                                                                                                                                                                               C:\Windows\Fonts\MTEXTRA.TTF => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/MTEXTRA
                                                                                                                                                                                                                                                                                                               C:\Windows\Fonts\mvboli.ttf => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/mvboli
                                                                                                                                                                                                                                                                                                               C:\Windows\Fonts\NIAGENG.TTF => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/NIAGENG
                                                                                                                                                                                                                                                                                                               C:\Windows\Fonts\NIAGSOL.TTF => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/NIAGSOL
                                                                                                                                                                                                                                                                                                               C:\Windows\Fonts\Nirmala.ttf => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/Nirmala
                                                                                                                                                                                                                                                                                                               C:\Windows\Fonts\NirmalaB.ttf => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/NirmalaB
                                                                                                                                                                                                                                                                                                               C:\Windows\Fonts\NirmalaS.ttf => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/NirmalaS
                                                                                                                                                                                                                                                                                                               C:\Windows\Fonts\nrkis.ttf => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/nrkis
                                                                                                                                                                                                                                                                                                               C:\Windows\Fonts\ntailu.ttf => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/ntailu
                                                                                                                                                                                                                                                                                                               C:\Windows\Fonts\ntailub.ttf => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/ntailub
                                                                                                                                                                                                                                                                                                               C:\Windows\Fonts\nyala.ttf => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/nyala
                                                                                                                                                                                                                                                                                                               C:\Windows\Fonts\OCRAEXT.TTF => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/OCRAEXT
                                                                                                                                                                                                                                                                                                               C:\Windows\Fonts\OLDENGL.TTF => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/OLDENGL
                                                                                                                                                                                                                                                                                                               C:\Windows\Fonts\ONYX.TTF => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/ONYX
                                                                                                                                                                                                                                                                                                               C:\Windows\Fonts\OUTLOOK.TTF => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/OUTLOOK
                                                                                                                                                                                                                                                                                                               C:\Windows\Fonts\pala.ttf => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/pala
                                                                                                                                                                                                                                                                                                               C:\Windows\Fonts\palab.ttf => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/palab
                                                                                                                                                                                                                                                                                                               C:\Windows\Fonts\palabi.ttf => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/palabi
                                                                                                                                                                                                                                                                                                               C:\Windows\Fonts\palai.ttf => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/palai
                                                                                                                                                                                                                                                                                                               C:\Windows\Fonts\PALSCRI.TTF => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/PALSCRI
                                                                                                                                                                                                                                                                                                               C:\Windows\Fonts\PAPYRUS.TTF => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/PAPYRUS
                                                                                                                                                                                                                                                                                                               C:\Windows\Fonts\PARCHM.TTF => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/PARCHM
                                                                                                                                                                                                                                                                                                               C:\Windows\Fonts\PER_____.TTF => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/PER_____
                                                                                                                                                                                                                                                                                                               C:\Windows\Fonts\PERB____.TTF => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/PERB____
                                                                                                                                                                                                                                                                                                               C:\Windows\Fonts\PERBI___.TTF => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/PERBI___
                                                                                                                                                                                                                                                                                                               C:\Windows\Fonts\PERI____.TTF => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/PERI____
                                                                                                                                                                                                                                                                                                               C:\Windows\Fonts\PERTIBD.TTF => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/PERTIBD
                                                                                                                                                                                                                                                                                                               C:\Windows\Fonts\PERTILI.TTF => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/PERTILI
                                                                                                                                                                                                                                                                                                               C:\Windows\Fonts\phagspa.ttf => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/phagspa
                                                                                                                                                                                                                                                                                                               C:\Windows\Fonts\phagspab.ttf => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/phagspab
                                                                                                                                                                                                                                                                                                               C:\Windows\Fonts\PLAYBILL.TTF => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/PLAYBILL
                                                                                                                                                                                                                                                                                                               C:\Windows\Fonts\POORICH.TTF => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/POORICH
                                                                                                                                                                                                                                                                                                               C:\Windows\Fonts\PRISTINA.TTF => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/PRISTINA
                                                                                                                                                                                                                                                                                                               C:\Windows\Fonts\RAGE.TTF => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/RAGE
                                                                                                                                                                                                                                                                                                               C:\Windows\Fonts\RAVIE.TTF => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/RAVIE
                                                                                                                                                                                                                                                                                                               C:\Windows\Fonts\REFSAN.TTF => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/REFSAN
                                                                                                                                                                                                                                                                                                               C:\Windows\Fonts\REFSPCL.TTF => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/REFSPCL
                                                                                                                                                                                                                                                                                                               C:\Windows\Fonts\ROCC____.TTF => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/ROCC____
                                                                                                                                                                                                                                                                                                               C:\Windows\Fonts\ROCCB___.TTF => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/ROCCB___
                                                                                                                                                                                                                                                                                                               C:\Windows\Fonts\ROCK.TTF => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/ROCK
                                                                                                                                                                                                                                                                                                               C:\Windows\Fonts\ROCKB.TTF => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/ROCKB
                                                                                                                                                                                                                                                                                                               C:\Windows\Fonts\ROCKBI.TTF => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/ROCKBI
                                                                                                                                                                                                                                                                                                               C:\Windows\Fonts\ROCKEB.TTF => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/ROCKEB
                                                                                                                                                                                                                                                                                                               C:\Windows\Fonts\ROCKI.TTF => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/ROCKI
                                                                                                                                                                                                                                                                                                               C:\Windows\Fonts\rod.ttf => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/rod
                                                                                                                                                                                                                                                                                                               C:\Windows\Fonts\SCHLBKB.TTF => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/SCHLBKB
                                                                                                                                                                                                                                                                                                               C:\Windows\Fonts\SCHLBKBI.TTF => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/SCHLBKBI
                                                                                                                                                                                                                                                                                                               C:\Windows\Fonts\SCHLBKI.TTF => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/SCHLBKI
                                                                                                                                                                                                                                                                                                               C:\Windows\Fonts\SCRIPTBL.TTF => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/SCRIPTBL
                                                                                                                                                                                                                                                                                                               C:\Windows\Fonts\segmdl2.ttf => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/segmdl2
                                                                                                                                                                                                                                                                                                               C:\Windows\Fonts\segoepr.ttf => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/segoepr
                                                                                                                                                                                                                                                                                                               C:\Windows\Fonts\segoeprb.ttf => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/segoeprb
                                                                                                                                                                                                                                                                                                               C:\Windows\Fonts\segoesc.ttf => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/segoesc
                                                                                                                                                                                                                                                                                                               C:\Windows\Fonts\segoescb.ttf => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/segoescb
                                                                                                                                                                                                                                                                                                               C:\Windows\Fonts\segoeui.ttf => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/segoeui
                                                                                                                                                                                                                                                                                                               C:\Windows\Fonts\segoeuib.ttf => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/segoeuib
                                                                                                                                                                                                                                                                                                               C:\Windows\Fonts\segoeuii.ttf => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/segoeuii
                                                                                                                                                                                                                                                                                                               C:\Windows\Fonts\segoeuil.ttf => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/segoeuil
                                                                                                                                                                                                                                                                                                               C:\Windows\Fonts\segoeuisl.ttf => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/segoeuisl
                                                                                                                                                                                                                                                                                                               C:\Windows\Fonts\segoeuiz.ttf => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/segoeuiz
                                                                                                                                                                                                                                                                                                               C:\Windows\Fonts\seguibl.ttf => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/seguibl
                                                                                                                                                                                                                                                                                                               C:\Windows\Fonts\seguibli.ttf => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/seguibli
                                                                                                                                                                                                                                                                                                               C:\Windows\Fonts\seguiemj.ttf => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/seguiemj
                                                                                                                                                                                                                                                                                                               C:\Windows\Fonts\seguihis.ttf => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/seguiemj
                                                                                                                                                                                                                                                                                                               C:\Windows\Fonts\seguihis.ttf => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/seguihis
                                                                                                                                                                                                                                                                                                               C:\Windows\Fonts\seguili.ttf => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/seguili
                                                                                                                                                                                                                                                                                                               C:\Windows\Fonts\seguisb.ttf => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/seguisb
                                                                                                                                                                                                                                                                                                               C:\Windows\Fonts\seguisbi.ttf => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/seguisbi
                                                                                                                                                                                                                                                                                                               C:\Windows\Fonts\seguisli.ttf => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/seguisli
                                                                                                                                                                                                                                                                                                               C:\Windows\Fonts\seguisym.ttf => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/seguisym
                                                                                                                                                                                                                                                                                                               C:\Windows\Fonts\SHOWG.TTF => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/SHOWG
                                                                                                                                                                                                                                                                                                               C:\Windows\Fonts\simpbdo.ttf => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/simpbdo
                                                                                                                                                                                                                                                                                                               C:\Windows\Fonts\simpfxo.ttf => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/simpfxo
                                                                                                                                                                                                                                                                                                               C:\Windows\Fonts\simpo.ttf => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/simpo
                                                                                                                                                                                                                                                                                                               C:\Windows\Fonts\simsunb.ttf => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/simsunb
                                                                                                                                                                                                                                                                                                               C:\Windows\Fonts\SitkaVF-Italic.ttf => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/SitkaVF-Italic
                                                                                                                                                                                                                                                                                                               C:\Windows\Fonts\SitkaVF.ttf => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/SitkaVF
                                                                                                                                                                                                                                                                                                               C:\Windows\Fonts\SNAP____.TTF => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/SNAP____
                                                                                                                                                                                                                                                                                                               C:\Windows\Fonts\STENCIL.TTF => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/STENCIL
                                                                                                                                                                                                                                                                                                               C:\Windows\Fonts\sylfaen.ttf => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/sylfaen
                                                                                                                                                                                                                                                                                                               C:\Windows\Fonts\symbol.ttf => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/symbol
                                                                                                                                                                                                                                                                                                               C:\Windows\Fonts\tahoma.ttf => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/tahoma
                                                                                                                                                                                                                                                                                                               C:\Windows\Fonts\tahomabd.ttf => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/tahomabd
                                                                                                                                                                                                                                                                                                               C:\Windows\Fonts\taile.ttf => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/taile
                                                                                                                                                                                                                                                                                                               C:\Windows\Fonts\taileb.ttf => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/taileb
                                                                                                                                                                                                                                                                                                               C:\Windows\Fonts\TCB_____.TTF => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/TCB_____
                                                                                                                                                                                                                                                                                                               C:\Windows\Fonts\TCBI____.TTF => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/TCBI____
                                                                                                                                                                                                                                                                                                               C:\Windows\Fonts\TCCB____.TTF => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/TCCB____
                                                                                                                                                                                                                                                                                                               C:\Windows\Fonts\TCCEB.TTF => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/TCCEB
                                                                                                                                                                                                                                                                                                               C:\Windows\Fonts\TCCM____.TTF => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/TCCM____
                                                                                                                                                                                                                                                                                                               C:\Windows\Fonts\TCM_____.TTF => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/TCM_____
                                                                                                                                                                                                                                                                                                               C:\Windows\Fonts\TCMI____.TTF => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/TCMI____
                                                                                                                                                                                                                                                                                                               C:\Windows\Fonts\TEMPSITC.TTF => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/TEMPSITC
                                                                                                                                                                                                                                                                                                               C:\Windows\Fonts\times.ttf => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/times
                                                                                                                                                                                                                                                                                                               C:\Windows\Fonts\timesbd.ttf => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/timesbd
                                                                                                                                                                                                                                                                                                               C:\Windows\Fonts\timesbi.ttf => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/timesbi
                                                                                                                                                                                                                                                                                                               C:\Windows\Fonts\timesi.ttf => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/timesi
                                                                                                                                                                                                                                                                                                               C:\Windows\Fonts\tradbdo.ttf => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/tradbdo
                                                                                                                                                                                                                                                                                                               C:\Windows\Fonts\trado.ttf => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/trado
                                                                                                                                                                                                                                                                                                               C:\Windows\Fonts\trebuc.ttf => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/trebuc
                                                                                                                                                                                                                                                                                                               C:\Windows\Fonts\trebucbd.ttf => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/trebucbd
                                                                                                                                                                                                                                                                                                               C:\Windows\Fonts\trebucbi.ttf => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/trebucbi
                                                                                                                                                                                                                                                                                                               C:\Windows\Fonts\trebucit.ttf => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/trebucit
                                                                                                                                                                                                                                                                                                               C:\Windows\Fonts\UbuntuMono-R.ttf => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/UbuntuMono-R
                                                                                                                                                                                                                                                                                                               C:\Windows\Fonts\UrdType.ttf => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/UrdType
                                                                                                                                                                                                                                                                                                               C:\Windows\Fonts\UrdTypeb.ttf => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/UrdTypeb
                                                                                                                                                                                                                                                                                                               C:\Windows\Fonts\verdana.ttf => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/verdana
                                                                                                                                                                                                                                                                                                               C:\Windows\Fonts\verdanab.ttf => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/verdanab
                                                                                                                                                                                                                                                                                                               C:\Windows\Fonts\verdanai.ttf => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/verdanai
                                                                                                                                                                                                                                                                                                               C:\Windows\Fonts\verdanaz.ttf => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/verdanaz
                                                                                                                                                                                                                                                                                                               C:\Windows\Fonts\VINERITC.TTF => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/VINERITC
                                                                                                                                                                                                                                                                                                               C:\Windows\Fonts\VIVALDII.TTF => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/VIVALDII
                                                                                                                                                                                                                                                                                                               C:\Windows\Fonts\VLADIMIR.TTF => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/VLADIMIR
                                                                                                                                                                                                                                                                                                               C:\Windows\Fonts\webdings.ttf => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/webdings
                                                                                                                                                                                                                                                                                                               C:\Windows\Fonts\wingding.ttf => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/wingding
                                                                                                                                                                                                                                                                                                               C:\Windows\Fonts\WINGDNG2.TTF => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/WINGDNG2
                                                                                                                                                                                                                                                                                                               C:\Windows\Fonts\WINGDNG3.TTF => C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics/WINGDNG3
                                                                                                                                                                                                                                                                                                               Found FontName for 349 fonts.
                                                                                                                                                                                                                                                                                                               Scanning afm files in C:/ProgramData/R/R-4.4.0/library/extrafontdb/metrics
                                                                                                                                                                                                                                                                                                               Writing font table in C:/ProgramData/R/R-4.4.0/library/extrafontdb/fontmap/fonttable.csv
                                                                                                                                                                                                                                                                                                               Writing Fontmap to C:/ProgramData/R/R-4.4.0/library/extrafontdb/fontmap/Fontmap...

                                                                                                                                                                                                                                                                                                               > # Load fonts
                                                                                                                                                                                                                                                                                                                 > extrafont::loadfonts(quiet = T)
                                                                                                                                                                                                                                                                                                               > extrafont::fonts()
                                                                                                                                                                                                                                                                                                               [1] "Agency FB"                       "Aharoni"                         "Aldhabi"                         "Algerian"                        "Andalus"                         "Arial Black"
                                                                                                                                                                                                                                                                                                               [7] "Arial"                           "Arial Narrow"                    "Arial Rounded MT Bold"           "Bahnschrift"                     "Baskerville Old Face"            "Bauhaus 93"
                                                                                                                                                                                                                                                                                                               [13] "Bell MT"                         "Berlin Sans FB"                  "Berlin Sans FB Demi"             "Bernard MT Condensed"            "Blackadder ITC"                  "Bodoni MT"
                                                                                                                                                                                                                                                                                                               [19] "Bodoni MT Black"                 "Bodoni MT Condensed"             "Bodoni MT Poster Compressed"     "Book Antiqua"                    "Bookman Old Style"               "Bookshelf Symbol 7"
                                                                                                                                                                                                                                                                                                               [25] "Bradley Hand ITC"                "Britannic Bold"                  "Broadway"                        "Brush Script MT"                 "Calibri"                         "Calibri Light"
                                                                                                                                                                                                                                                                                                               [31] "Californian FB"                  "Calisto MT"                      "Cambria"                         "Candara"                         "Candara Light"                   "Cascadia Code"
                                                                                                                                                                                                                                                                                                               [37] "Cascadia Mono"                   "Castellar"                       "Centaur"                         "Century"                         "Century Gothic"                  "Century Schoolbook"
                                                                                                                                                                                                                                                                                                               [43] "Chiller"                         "Colonna MT"                      "Comic Sans MS"                   "Consolas"                        "Constantia"                      "Cooper Black"
                                                                                                                                                                                                                                                                                                               [49] "Copperplate Gothic Bold"         "Copperplate Gothic Light"        "Corbel"                          "Corbel Light"                    "Courier New"                     "Curlz MT"
                                                                                                                                                                                                                                                                                                               [55] "David"                           "Dubai"                           "Dubai Light"                     "Dubai Medium"                    "Ebrima"                          "Edwardian Script ITC"
                                                                                                                                                                                                                                                                                                               [61] "Elephant"                        "Engravers MT"                    "Eras Bold ITC"                   "Eras Demi ITC"                   "Eras Light ITC"                  "Eras Medium ITC"
                                                                                                                                                                                                                                                                                                               [67] "Felix Titling"                   "Footlight MT Light"              "Forte"                           "Franklin Gothic Book"            "Franklin Gothic Demi"            "Franklin Gothic Demi Cond"
                                                                                                                                                                                                                                                                                                               [73] "Franklin Gothic Heavy"           "Franklin Gothic Medium"          "Franklin Gothic Medium Cond"     "FrankRuehl"                      "Freestyle Script"                "French Script MT"
                                                                                                                                                                                                                                                                                                               [79] "Gabriola"                        "Gadugi"                          "Garamond"                        "Georgia"                         "Gigi"                            "Gill Sans Ultra Bold"
                                                                                                                                                                                                                                                                                                               [85] "Gill Sans Ultra Bold Condensed"  "Gill Sans MT"                    "Gill Sans MT Condensed"          "Gill Sans MT Ext Condensed Bold" "Gisha"                           "Gloucester MT Extra Condensed"
                                                                                                                                                                                                                                                                                                               [91] "Goudy Old Style"                 "Goudy Stout"                     "Haettenschweiler"                "Harlow Solid Italic"             "Harrington"                      "High Tower Text"
                                                                                                                                                                                                                                                                                                               [97] "Impact"                          "Imprint MT Shadow"               "Informal Roman"                  "Ink Free"                        "Javanese Text"                   "Jokerman"
                                                                                                                                                                                                                                                                                                               [103] "Juice ITC"                       "Kristen ITC"                     "Kunstler Script"                 "Wide Latin"                      "Leelawadee"                      "Leelawadee UI"
                                                                                                                                                                                                                                                                                                               [109] "Leelawadee UI Semilight"         "Levenim MT"                      "Lucida Bright"                   "Lucida Calligraphy"              "Lucida Console"                  "Lucida Fax"
                                                                                                                                                                                                                                                                                                               [115] "Lucida Handwriting"              "Lucida Sans"                     "Lucida Sans Typewriter"          "Lucida Sans Unicode"             "Magneto"                         "Maiandra GD"
                                                                                                                                                                                                                                                                                                               [121] "Malgun Gothic"                   "Malgun Gothic Semilight"         "Marlett"                         "Matura MT Script Capitals"       "Microsoft Himalaya"              "Microsoft Yi Baiti"
                                                                                                                                                                                                                                                                                                               [127] "Microsoft New Tai Lue"           "Microsoft PhagsPa"               "Microsoft Sans Serif"            "Microsoft Tai Le"                "Microsoft Uighur"                "Miriam"
                                                                                                                                                                                                                                                                                                               [133] "Miriam Fixed"                    "Mistral"                         "Modern No. 20"                   "Mongolian Baiti"                 "Monotype Corsiva"                "MS Outlook"
                                                                                                                                                                                                                                                                                                               [139] "MS Reference Sans Serif"         "MS Reference Specialty"          "MT Extra"                        "MV Boli"                         "Myanmar Text"                    "Narkisim"
                                                                                                                                                                                                                                                                                                               [145] "Niagara Engraved"                "Niagara Solid"                   "Nirmala UI"                      "Nirmala UI Semilight"            "Nyala"                           "OCR A Extended"
                                                                                                                                                                                                                                                                                                               [151] "Old English Text MT"             "Onyx"                            "Palace Script MT"                "Palatino Linotype"               "Papyrus"                         "Parchment"
                                                                                                                                                                                                                                                                                                               [157] "Perpetua"                        "Perpetua Titling MT"             "Playbill"                        "Poor Richard"                    "Pristina"                        "Rage Italic"
                                                                                                                                                                                                                                                                                                               [163] "Ravie"                           "Rockwell"                        "Rockwell Condensed"              "Rockwell Extra Bold"             "Rod"                             "Sakkal Majalla"
                                                                                                                                                                                                                                                                                                               [169] "Script MT Bold"                  "Segoe MDL2 Assets"               "Segoe Print"                     "Segoe Script"                    "Segoe UI"                        "Segoe UI Light"
                                                                                                                                                                                                                                                                                                               [175] "Segoe UI Semibold"               "Segoe UI Semilight"              "Segoe UI Black"                  "Segoe UI Emoji"                  "Segoe UI Historic"               "Segoe UI Symbol"
                                                                                                                                                                                                                                                                                                               [181] "Showcard Gothic"                 "Simplified Arabic"               "Simplified Arabic Fixed"         "SimSun-ExtB"                     "Sitka Text"                      "Snap ITC"
                                                                                                                                                                                                                                                                                                               [187] "Stencil"                         "Sylfaen"                         "Symbol"                          "Tahoma"                          "Tempus Sans ITC"                 "Times New Roman"
                                                                                                                                                                                                                                                                                                               [193] "Traditional Arabic"              "Trebuchet MS"                    "Tw Cen MT"                       "Tw Cen MT Condensed"             "Tw Cen MT Condensed Extra Bold"  "Ubuntu Mono"
                                                                                                                                                                                                                                                                                                               [199] "Urdu Typesetting"                "Verdana"                         "Viner Hand ITC"                  "Vivaldi"                         "Vladimir Script"                 "Webdings"
                                                                                                                                                                                                                                                                                                               [205] "Wingdings"                       "Wingdings 2"                     "Wingdings 3"
                                                                                                                                                                                                                                                                                                               
***********************************************************************************************************************
Fix for project env
***********************************************************************************************************************                                                                                                                                                                                                                                                                                                
# Import Fonts to Proj ENV. i.e.  RENV                                                                                                                                                                                                                                                                                          
> library(extrafont)
Registering fonts with R
> font_import()
Importing fonts may take a few minutes, depending on the number of fonts and the speed of the system.
Continue? [y/n] y
Scanning ttf files in C:\Windows/Fonts, C:\Users\Administrator\AppData\Local/Microsoft/Windows/Fonts ...
Extracting .afm files from .ttf files...
C:\Windows\Fonts\AGENCYB.TTF => C:/Users/Administrator/AppData/Local/R/cache/R/renv/cache/v5/windows/R-4.4/x86_64-w64-mingw32/extrafontdb/1.0/a861555ddec7451c653b40e713166c6f/extrafontdb/metrics/AGENCYB
C:\Windows\Fonts\AGENCYR.TTF => C:/Users/Administrator/AppData/Local/R/cache/R/renv/cache/v5/windows/R-4.4/x86_64-w64-mingw32/extrafontdb/1.0/a861555ddec7451c653b40e713166c6f/extrafontdb/metrics/AGENCYR
C:\Windows\Fonts\ahronbd.ttf => C:/Users/Administrator/AppData/Local/R/cache/R/renv/cache/v5/windows/R-4.4/x86_64-w64-mingw32/extrafontdb/1.0/a861555ddec7451c653b40e713166c6f/extrafontdb/metrics/ahronbd
C:\Windows\Fonts\aldhabi.ttf => C:/Users/Administrator/AppData/Local/R/cache/R/renv/cache/v5/windows/R-4.4/x86_64-w64-mingw32/extrafontdb/1.0/a861555ddec7451c653b40e713166c6f/extrafontdb/metrics/aldhabi
C:\Windows\Fonts\ALGER.TTF => C:/Users/Administrator/AppData/Local/R/cache/R/renv/cache/v5/windows/R-4.4/x86_64-w64-mingw32/extrafontdb/1.0/a861555ddec7451c653b40e713166c6f/extrafontdb/metrics/ALGER
C:\Windows\Fonts\andlso.ttf => C:/Users/Administrator/AppData/Local/R/cache/R/renv/cache/v5/windows/R-4.4/x86_64-w64-mingw32/extrafontdb/1.0/a861555ddec7451c653b40e713166c6f/extrafontdb/metrics/andlso
C:\Windows\Fonts\ANTQUAB.TTF => C:/Users/Administrator/AppData/Local/R/cache/R/renv/cache/v5/windows/R-4.4/x86_64-w64-mingw32/extrafontdb/1.0/a861555ddec7451c653b40e713166c6f/extrafontdb/metrics/ANTQUAB
C:\Windows\Fonts\ANTQUABI.TTF => C:/Users/Administrator/AppData/Local/R/cache/R/renv/cache/v5/windows/R-4.4/x86_64-w64-mingw32/extrafontdb/1.0/a861555ddec7451c653b40e713166c6f/extrafontdb/metrics/ANTQUABI
C:\Windows\Fonts\ANTQUAI.TTF => C:/Users/Administrator/AppData/Local/R/cache/R/renv/cache/v5/windows/R-4.4/x86_64-w64-mingw32/extrafontdb/1.0/a861555ddec7451c653b40e713166c6f/extrafontdb/metrics/ANTQUAI
C:\Windows\Fonts\arabtype.ttf : No FontName. Skipping.
C:\Windows\Fonts\arial.ttf => C:/Users/Administrator/AppData/Local/R/cache/R/renv/cache/v5/windows/R-4.4/x86_64-w64-mingw32/extrafontdb/1.0/a861555ddec7451c653b40e713166c6f/extrafontdb/metrics/arial
C:\Windows\Fonts\arialbd.ttf => C:/Users/Administrator/AppData/Local/R/cache/R/renv/cache/v5/windows/R-4.4/x86_64-w64-mingw32/extrafontdb/1.0/a861555ddec7451c653b40e713166c6f/extrafontdb/metrics/arialbd
C:\Windows\Fonts\arialbi.ttf => C:/Users/Administrator/AppData/Local/R/cache/R/renv/cache/v5/windows/R-4.4/x86_64-w64-mingw32/extrafontdb/1.0/a861555ddec7451c653b40e713166c6f/extrafontdb/metrics/arialbi
C:\Windows\Fonts\ariali.ttf => C:/Users/Administrator/AppData/Local/R/cache/R/renv/cache/v5/windows/R-4.4/x86_64-w64-mingw32/extrafontdb/1.0/a861555ddec7451c653b40e713166c6f/extrafontdb/metrics/ariali
C:\Windows\Fonts\ARIALN.TTF => C:/Users/Administrator/AppData/Local/R/cache/R/renv/cache/v5/windows/R-4.4/x86_64-w64-mingw32/extrafontdb/1.0/a861555ddec7451c653b40e713166c6f/extrafontdb/metrics/ARIALN
C:\Windows\Fonts\ARIALNB.TTF => C:/Users/Administrator/AppData/Local/R/cache/R/renv/cache/v5/windows/R-4.4/x86_64-w64-mingw32/extrafontdb/1.0/a861555ddec7451c653b40e713166c6f/extrafontdb/metrics/ARIALNB
C:\Windows\Fonts\ARIALNBI.TTF => C:/Users/Administrator/AppData/Local/R/cache/R/renv/cache/v5/windows/R-4.4/x86_64-w64-mingw32/extrafontdb/1.0/a861555ddec7451c653b40e713166c6f/extrafontdb/metrics/ARIALNBI
C:\Windows\Fonts\ARIALNI.TTF => C:/Users/Administrator/AppData/Local/R/cache/R/renv/cache/v5/windows/R-4.4/x86_64-w64-mingw32/extrafontdb/1.0/a861555ddec7451c653b40e713166c6f/extrafontdb/metrics/ARIALNI
C:\Windows\Fonts\ariblk.ttf => C:/Users/Administrator/AppData/Local/R/cache/R/renv/cache/v5/windows/R-4.4/x86_64-w64-mingw32/extrafontdb/1.0/a861555ddec7451c653b40e713166c6f/extrafontdb/metrics/ariblk
C:\Windows\Fonts\ARLRDBD.TTF => C:/Users/Administrator/AppData/Local/R/cache/R/renv/cache/v5/windows/R-4.4/x86_64-w64-mingw32/extrafontdb/1.0/a861555ddec7451c653b40e713166c6f/extrafontdb/metrics/ARLRDBD
C:\Windows\Fonts\bahnschrift.ttf => C:/Users/Administrator/AppData/Local/R/cache/R/renv/cache/v5/windows/R-4.4/x86_64-w64-mingw32/extrafontdb/1.0/a861555ddec7451c653b40e713166c6f/extrafontdb/metrics/bahnschrift
C:\Windows\Fonts\BASKVILL.TTF => C:/Users/Administrator/AppData/Local/R/cache/R/renv/cache/v5/windows/R-4.4/x86_64-w64-mingw32/extrafontdb/1.0/a861555ddec7451c653b40e713166c6f/extrafontdb/metrics/BASKVILL
C:\Windows\Fonts\BAUHS93.TTF => C:/Users/Administrator/AppData/Local/R/cache/R/renv/cache/v5/windows/R-4.4/x86_64-w64-mingw32/extrafontdb/1.0/a861555ddec7451c653b40e713166c6f/extrafontdb/metrics/BAUHS93
C:\Windows\Fonts\BELL.TTF => C:/Users/Administrator/AppData/Local/R/cache/R/renv/cache/v5/windows/R-4.4/x86_64-w64-mingw32/extrafontdb/1.0/a861555ddec7451c653b40e713166c6f/extrafontdb/metrics/BELL
C:\Windows\Fonts\BELLB.TTF => C:/Users/Administrator/AppData/Local/R/cache/R/renv/cache/v5/windows/R-4.4/x86_64-w64-mingw32/extrafontdb/1.0/a861555ddec7451c653b40e713166c6f/extrafontdb/metrics/BELLB
C:\Windows\Fonts\BELLI.TTF => C:/Users/Administrator/AppData/Local/R/cache/R/renv/cache/v5/windows/R-4.4/x86_64-w64-mingw32/extrafontdb/1.0/a861555ddec7451c653b40e713166c6f/extrafontdb/metrics/BELLI
C:\Windows\Fonts\BERNHC.TTF => C:/Users/Administrator/AppData/Local/R/cache/R/renv/cache/v5/windows/R-4.4/x86_64-w64-mingw32/extrafontdb/1.0/a861555ddec7451c653b40e713166c6f/extrafontdb/metrics/BERNHC
C:\Windows\Fonts\BKANT.TTF => C:/Users/Administrator/AppData/Local/R/cache/R/renv/cache/v5/windows/R-4.4/x86_64-w64-mingw32/extrafontdb/1.0/a861555ddec7451c653b40e713166c6f/extrafontdb/metrics/BKANT
C:\Windows\Fonts\BOD_B.TTF => C:/Users/Administrator/AppData/Local/R/cache/R/renv/cache/v5/windows/R-4.4/x86_64-w64-mingw32/extrafontdb/1.0/a861555ddec7451c653b40e713166c6f/extrafontdb/metrics/BOD_B
C:\Windows\Fonts\BOD_BI.TTF => C:/Users/Administrator/AppData/Local/R/cache/R/renv/cache/v5/windows/R-4.4/x86_64-w64-mingw32/extrafontdb/1.0/a861555ddec7451c653b40e713166c6f/extrafontdb/metrics/BOD_BI
C:\Windows\Fonts\BOD_BLAI.TTF => C:/Users/Administrator/AppData/Local/R/cache/R/renv/cache/v5/windows/R-4.4/x86_64-w64-mingw32/extrafontdb/1.0/a861555ddec7451c653b40e713166c6f/extrafontdb/metrics/BOD_BLAI
C:\Windows\Fonts\BOD_BLAR.TTF => C:/Users/Administrator/AppData/Local/R/cache/R/renv/cache/v5/windows/R-4.4/x86_64-w64-mingw32/extrafontdb/1.0/a861555ddec7451c653b40e713166c6f/extrafontdb/metrics/BOD_BLAR
C:\Windows\Fonts\BOD_CB.TTF => C:/Users/Administrator/AppData/Local/R/cache/R/renv/cache/v5/windows/R-4.4/x86_64-w64-mingw32/extrafontdb/1.0/a861555ddec7451c653b40e713166c6f/extrafontdb/metrics/BOD_CB
C:\Windows\Fonts\BOD_CBI.TTF => C:/Users/Administrator/AppData/Local/R/cache/R/renv/cache/v5/windows/R-4.4/x86_64-w64-mingw32/extrafontdb/1.0/a861555ddec7451c653b40e713166c6f/extrafontdb/metrics/BOD_CBI
C:\Windows\Fonts\BOD_CI.TTF => C:/Users/Administrator/AppData/Local/R/cache/R/renv/cache/v5/windows/R-4.4/x86_64-w64-mingw32/extrafontdb/1.0/a861555ddec7451c653b40e713166c6f/extrafontdb/metrics/BOD_CI
C:\Windows\Fonts\BOD_CR.TTF => C:/Users/Administrator/AppData/Local/R/cache/R/renv/cache/v5/windows/R-4.4/x86_64-w64-mingw32/extrafontdb/1.0/a861555ddec7451c653b40e713166c6f/extrafontdb/metrics/BOD_CR
C:\Windows\Fonts\BOD_I.TTF => C:/Users/Administrator/AppData/Local/R/cache/R/renv/cache/v5/windows/R-4.4/x86_64-w64-mingw32/extrafontdb/1.0/a861555ddec7451c653b40e713166c6f/extrafontdb/metrics/BOD_I
C:\Windows\Fonts\BOD_PSTC.TTF => C:/Users/Administrator/AppData/Local/R/cache/R/renv/cache/v5/windows/R-4.4/x86_64-w64-mingw32/extrafontdb/1.0/a861555ddec7451c653b40e713166c6f/extrafontdb/metrics/BOD_PSTC
C:\Windows\Fonts\BOD_R.TTF => C:/Users/Administrator/AppData/Local/R/cache/R/renv/cache/v5/windows/R-4.4/x86_64-w64-mingw32/extrafontdb/1.0/a861555ddec7451c653b40e713166c6f/extrafontdb/metrics/BOD_R
C:\Windows\Fonts\BOOKOS.TTF => C:/Users/Administrator/AppData/Local/R/cache/R/renv/cache/v5/windows/R-4.4/x86_64-w64-mingw32/extrafontdb/1.0/a861555ddec7451c653b40e713166c6f/extrafontdb/metrics/BOOKOS
C:\Windows\Fonts\BOOKOSB.TTF => C:/Users/Administrator/AppData/Local/R/cache/R/renv/cache/v5/windows/R-4.4/x86_64-w64-mingw32/extrafontdb/1.0/a861555ddec7451c653b40e713166c6f/extrafontdb/metrics/BOOKOSB
C:\Windows\Fonts\BOOKOSBI.TTF => C:/Users/Administrator/AppData/Local/R/cache/R/renv/cache/v5/windows/R-4.4/x86_64-w64-mingw32/extrafontdb/1.0/a861555ddec7451c653b40e713166c6f/extrafontdb/metrics/BOOKOSBI
C:\Windows\Fonts\BOOKOSI.TTF => C:/Users/Administrator/AppData/Local/R/cache/R/renv/cache/v5/windows/R-4.4/x86_64-w64-mingw32/extrafontdb/1.0/a861555ddec7451c653b40e713166c6f/extrafontdb/metrics/BOOKOSI
C:\Windows\Fonts\BRADHITC.TTF => C:/Users/Administrator/AppData/Local/R/cache/R/renv/cache/v5/windows/R-4.4/x86_64-w64-mingw32/extrafontdb/1.0/a861555ddec7451c653b40e713166c6f/extrafontdb/metrics/BRADHITC
C:\Windows\Fonts\BRITANIC.TTF => C:/Users/Administrator/AppData/Local/R/cache/R/renv/cache/v5/windows/R-4.4/x86_64-w64-mingw32/extrafontdb/1.0/a861555ddec7451c653b40e713166c6f/extrafontdb/metrics/BRITANIC
C:\Windows\Fonts\BRLNSB.TTF => C:/Users/Administrator/AppData/Local/R/cache/R/renv/cache/v5/windows/R-4.4/x86_64-w64-mingw32/extrafontdb/1.0/a861555ddec7451c653b40e713166c6f/extrafontdb/metrics/BRLNSB
C:\Windows\Fonts\BRLNSDB.TTF => C:/Users/Administrator/AppData/Local/R/cache/R/renv/cache/v5/windows/R-4.4/x86_64-w64-mingw32/extrafontdb/1.0/a861555ddec7451c653b40e713166c6f/extrafontdb/metrics/BRLNSDB
C:\Windows\Fonts\BRLNSR.TTF => C:/Users/Administrator/AppData/Local/R/cache/R/renv/cache/v5/windows/R-4.4/x86_64-w64-mingw32/extrafontdb/1.0/a861555ddec7451c653b40e713166c6f/extrafontdb/metrics/BRLNSR
C:\Windows\Fonts\BROADW.TTF => C:/Users/Administrator/AppData/Local/R/cache/R/renv/cache/v5/windows/R-4.4/x86_64-w64-mingw32/extrafontdb/1.0/a861555ddec7451c653b40e713166c6f/extrafontdb/metrics/BROADW
C:\Windows\Fonts\BRUSHSCI.TTF => C:/Users/Administrator/AppData/Local/R/cache/R/renv/cache/v5/windows/R-4.4/x86_64-w64-mingw32/extrafontdb/1.0/a861555ddec7451c653b40e713166c6f/extrafontdb/metrics/BRUSHSCI
C:\Windows\Fonts\BSSYM7.TTF => C:/Users/Administrator/AppData/Local/R/cache/R/renv/cache/v5/windows/R-4.4/x86_64-w64-mingw32/extrafontdb/1.0/a861555ddec7451c653b40e713166c6f/extrafontdb/metrics/BSSYM7
C:\Windows\Fonts\calibri.ttf => C:/Users/Administrator/AppData/Local/R/cache/R/renv/cache/v5/windows/R-4.4/x86_64-w64-mingw32/extrafontdb/1.0/a861555ddec7451c653b40e713166c6f/extrafontdb/metrics/calibri
C:\Windows\Fonts\calibrib.ttf => C:/Users/Administrator/AppData/Local/R/cache/R/renv/cache/v5/windows/R-4.4/x86_64-w64-mingw32/extrafontdb/1.0/a861555ddec7451c653b40e713166c6f/extrafontdb/metrics/calibrib
C:\Windows\Fonts\calibrii.ttf => C:/Users/Administrator/AppData/Local/R/cache/R/renv/cache/v5/windows/R-4.4/x86_64-w64-mingw32/extrafontdb/1.0/a861555ddec7451c653b40e713166c6f/extrafontdb/metrics/calibrii
C:\Windows\Fonts\calibril.ttf => C:/Users/Administrator/AppData/Local/R/cache/R/renv/cache/v5/windows/R-4.4/x86_64-w64-mingw32/extrafontdb/1.0/a861555ddec7451c653b40e713166c6f/extrafontdb/metrics/calibril
C:\Windows\Fonts\calibrili.ttf => C:/Users/Administrator/AppData/Local/R/cache/R/renv/cache/v5/windows/R-4.4/x86_64-w64-mingw32/extrafontdb/1.0/a861555ddec7451c653b40e713166c6f/extrafontdb/metrics/calibrili
C:\Windows\Fonts\calibriz.ttf => C:/Users/Administrator/AppData/Local/R/cache/R/renv/cache/v5/windows/R-4.4/x86_64-w64-mingw32/extrafontdb/1.0/a861555ddec7451c653b40e713166c6f/extrafontdb/metrics/calibriz
C:\Windows\Fonts\CALIFB.TTF => C:/Users/Administrator/AppData/Local/R/cache/R/renv/cache/v5/windows/R-4.4/x86_64-w64-mingw32/extrafontdb/1.0/a861555ddec7451c653b40e713166c6f/extrafontdb/metrics/CALIFB
C:\Windows\Fonts\CALIFI.TTF => C:/Users/Administrator/AppData/Local/R/cache/R/renv/cache/v5/windows/R-4.4/x86_64-w64-mingw32/extrafontdb/1.0/a861555ddec7451c653b40e713166c6f/extrafontdb/metrics/CALIFI
C:\Windows\Fonts\CALIFR.TTF => C:/Users/Administrator/AppData/Local/R/cache/R/renv/cache/v5/windows/R-4.4/x86_64-w64-mingw32/extrafontdb/1.0/a861555ddec7451c653b40e713166c6f/extrafontdb/metrics/CALIFR
C:\Windows\Fonts\CALIST.TTF => C:/Users/Administrator/AppData/Local/R/cache/R/renv/cache/v5/windows/R-4.4/x86_64-w64-mingw32/extrafontdb/1.0/a861555ddec7451c653b40e713166c6f/extrafontdb/metrics/CALIST
C:\Windows\Fonts\CALISTB.TTF => C:/Users/Administrator/AppData/Local/R/cache/R/renv/cache/v5/windows/R-4.4/x86_64-w64-mingw32/extrafontdb/1.0/a861555ddec7451c653b40e713166c6f/extrafontdb/metrics/CALISTB
C:\Windows\Fonts\CALISTBI.TTF => C:/Users/Administrator/AppData/Local/R/cache/R/renv/cache/v5/windows/R-4.4/x86_64-w64-mingw32/extrafontdb/1.0/a861555ddec7451c653b40e713166c6f/extrafontdb/metrics/CALISTBI
C:\Windows\Fonts\CALISTI.TTF => C:/Users/Administrator/AppData/Local/R/cache/R/renv/cache/v5/windows/R-4.4/x86_64-w64-mingw32/extrafontdb/1.0/a861555ddec7451c653b40e713166c6f/extrafontdb/metrics/CALISTI
C:\Windows\Fonts\cambriab.ttf => C:/Users/Administrator/AppData/Local/R/cache/R/renv/cache/v5/windows/R-4.4/x86_64-w64-mingw32/extrafontdb/1.0/a861555ddec7451c653b40e713166c6f/extrafontdb/metrics/cambriab
C:\Windows\Fonts\cambriai.ttf => C:/Users/Administrator/AppData/Local/R/cache/R/renv/cache/v5/windows/R-4.4/x86_64-w64-mingw32/extrafontdb/1.0/a861555ddec7451c653b40e713166c6f/extrafontdb/metrics/cambriai
C:\Windows\Fonts\cambriaz.ttf => C:/Users/Administrator/AppData/Local/R/cache/R/renv/cache/v5/windows/R-4.4/x86_64-w64-mingw32/extrafontdb/1.0/a861555ddec7451c653b40e713166c6f/extrafontdb/metrics/cambriaz
C:\Windows\Fonts\Candara.ttf => C:/Users/Administrator/AppData/Local/R/cache/R/renv/cache/v5/windows/R-4.4/x86_64-w64-mingw32/extrafontdb/1.0/a861555ddec7451c653b40e713166c6f/extrafontdb/metrics/Candara
C:\Windows\Fonts\Candarab.ttf => C:/Users/Administrator/AppData/Local/R/cache/R/renv/cache/v5/windows/R-4.4/x86_64-w64-mingw32/extrafontdb/1.0/a861555ddec7451c653b40e713166c6f/extrafontdb/metrics/Candarab
C:\Windows\Fonts\Candarai.ttf => C:/Users/Administrator/AppData/Local/R/cache/R/renv/cache/v5/windows/R-4.4/x86_64-w64-mingw32/extrafontdb/1.0/a861555ddec7451c653b40e713166c6f/extrafontdb/metrics/Candarai
C:\Windows\Fonts\Candaral.ttf => C:/Users/Administrator/AppData/Local/R/cache/R/renv/cache/v5/windows/R-4.4/x86_64-w64-mingw32/extrafontdb/1.0/a861555ddec7451c653b40e713166c6f/extrafontdb/metrics/Candaral
C:\Windows\Fonts\Candarali.ttf => C:/Users/Administrator/AppData/Local/R/cache/R/renv/cache/v5/windows/R-4.4/x86_64-w64-mingw32/extrafontdb/1.0/a861555ddec7451c653b40e713166c6f/extrafontdb/metrics/Candarali
C:\Windows\Fonts\Candaraz.ttf => C:/Users/Administrator/AppData/Local/R/cache/R/renv/cache/v5/windows/R-4.4/x86_64-w64-mingw32/extrafontdb/1.0/a861555ddec7451c653b40e713166c6f/extrafontdb/metrics/Candaraz
C:\Windows\Fonts\CascadiaCode.ttf => C:/Users/Administrator/AppData/Local/R/cache/R/renv/cache/v5/windows/R-4.4/x86_64-w64-mingw32/extrafontdb/1.0/a861555ddec7451c653b40e713166c6f/extrafontdb/metrics/CascadiaCode
C:\Windows\Fonts\CascadiaCodeItalic.ttf => C:/Users/Administrator/AppData/Local/R/cache/R/renv/cache/v5/windows/R-4.4/x86_64-w64-mingw32/extrafontdb/1.0/a861555ddec7451c653b40e713166c6f/extrafontdb/metrics/CascadiaCodeItalic
C:\Windows\Fonts\CascadiaMono.ttf => C:/Users/Administrator/AppData/Local/R/cache/R/renv/cache/v5/windows/R-4.4/x86_64-w64-mingw32/extrafontdb/1.0/a861555ddec7451c653b40e713166c6f/extrafontdb/metrics/CascadiaMono
C:\Windows\Fonts\CascadiaMonoItalic.ttf => C:/Users/Administrator/AppData/Local/R/cache/R/renv/cache/v5/windows/R-4.4/x86_64-w64-mingw32/extrafontdb/1.0/a861555ddec7451c653b40e713166c6f/extrafontdb/metrics/CascadiaMonoItalic
C:\Windows\Fonts\CASTELAR.TTF => C:/Users/Administrator/AppData/Local/R/cache/R/renv/cache/v5/windows/R-4.4/x86_64-w64-mingw32/extrafontdb/1.0/a861555ddec7451c653b40e713166c6f/extrafontdb/metrics/CASTELAR
C:\Windows\Fonts\CENSCBK.TTF => C:/Users/Administrator/AppData/Local/R/cache/R/renv/cache/v5/windows/R-4.4/x86_64-w64-mingw32/extrafontdb/1.0/a861555ddec7451c653b40e713166c6f/extrafontdb/metrics/CENSCBK
C:\Windows\Fonts\CENTAUR.TTF => C:/Users/Administrator/AppData/Local/R/cache/R/renv/cache/v5/windows/R-4.4/x86_64-w64-mingw32/extrafontdb/1.0/a861555ddec7451c653b40e713166c6f/extrafontdb/metrics/CENTAUR
C:\Windows\Fonts\CENTURY.TTF => C:/Users/Administrator/AppData/Local/R/cache/R/renv/cache/v5/windows/R-4.4/x86_64-w64-mingw32/extrafontdb/1.0/a861555ddec7451c653b40e713166c6f/extrafontdb/metrics/CENTURY
C:\Windows\Fonts\CHILLER.TTF => C:/Users/Administrator/AppData/Local/R/cache/R/renv/cache/v5/windows/R-4.4/x86_64-w64-mingw32/extrafontdb/1.0/a861555ddec7451c653b40e713166c6f/extrafontdb/metrics/CHILLER
C:\Windows\Fonts\COLONNA.TTF => C:/Users/Administrator/AppData/Local/R/cache/R/renv/cache/v5/windows/R-4.4/x86_64-w64-mingw32/extrafontdb/1.0/a861555ddec7451c653b40e713166c6f/extrafontdb/metrics/COLONNA
C:\Windows\Fonts\comic.ttf => C:/Users/Administrator/AppData/Local/R/cache/R/renv/cache/v5/windows/R-4.4/x86_64-w64-mingw32/extrafontdb/1.0/a861555ddec7451c653b40e713166c6f/extrafontdb/metrics/comic
C:\Windows\Fonts\comicbd.ttf => C:/Users/Administrator/AppData/Local/R/cache/R/renv/cache/v5/windows/R-4.4/x86_64-w64-mingw32/extrafontdb/1.0/a861555ddec7451c653b40e713166c6f/extrafontdb/metrics/comicbd
C:\Windows\Fonts\comici.ttf => C:/Users/Administrator/AppData/Local/R/cache/R/renv/cache/v5/windows/R-4.4/x86_64-w64-mingw32/extrafontdb/1.0/a861555ddec7451c653b40e713166c6f/extrafontdb/metrics/comici
C:\Windows\Fonts\comicz.ttf => C:/Users/Administrator/AppData/Local/R/cache/R/renv/cache/v5/windows/R-4.4/x86_64-w64-mingw32/extrafontdb/1.0/a861555ddec7451c653b40e713166c6f/extrafontdb/metrics/comicz
C:\Windows\Fonts\consola.ttf => C:/Users/Administrator/AppData/Local/R/cache/R/renv/cache/v5/windows/R-4.4/x86_64-w64-mingw32/extrafontdb/1.0/a861555ddec7451c653b40e713166c6f/extrafontdb/metrics/consola
C:\Windows\Fonts\consolab.ttf => C:/Users/Administrator/AppData/Local/R/cache/R/renv/cache/v5/windows/R-4.4/x86_64-w64-mingw32/extrafontdb/1.0/a861555ddec7451c653b40e713166c6f/extrafontdb/metrics/consolab
C:\Windows\Fonts\consolai.ttf => C:/Users/Administrator/AppData/Local/R/cache/R/renv/cache/v5/windows/R-4.4/x86_64-w64-mingw32/extrafontdb/1.0/a861555ddec7451c653b40e713166c6f/extrafontdb/metrics/consolai
C:\Windows\Fonts\consolaz.ttf => C:/Users/Administrator/AppData/Local/R/cache/R/renv/cache/v5/windows/R-4.4/x86_64-w64-mingw32/extrafontdb/1.0/a861555ddec7451c653b40e713166c6f/extrafontdb/metrics/consolaz
C:\Windows\Fonts\constan.ttf => C:/Users/Administrator/AppData/Local/R/cache/R/renv/cache/v5/windows/R-4.4/x86_64-w64-mingw32/extrafontdb/1.0/a861555ddec7451c653b40e713166c6f/extrafontdb/metrics/constan
C:\Windows\Fonts\constanb.ttf => C:/Users/Administrator/AppData/Local/R/cache/R/renv/cache/v5/windows/R-4.4/x86_64-w64-mingw32/extrafontdb/1.0/a861555ddec7451c653b40e713166c6f/extrafontdb/metrics/constanb
C:\Windows\Fonts\constani.ttf => C:/Users/Administrator/AppData/Local/R/cache/R/renv/cache/v5/windows/R-4.4/x86_64-w64-mingw32/extrafontdb/1.0/a861555ddec7451c653b40e713166c6f/extrafontdb/metrics/constani
C:\Windows\Fonts\constanz.ttf => C:/Users/Administrator/AppData/Local/R/cache/R/renv/cache/v5/windows/R-4.4/x86_64-w64-mingw32/extrafontdb/1.0/a861555ddec7451c653b40e713166c6f/extrafontdb/metrics/constanz
C:\Windows\Fonts\COOPBL.TTF => C:/Users/Administrator/AppData/Local/R/cache/R/renv/cache/v5/windows/R-4.4/x86_64-w64-mingw32/extrafontdb/1.0/a861555ddec7451c653b40e713166c6f/extrafontdb/metrics/COOPBL
C:\Windows\Fonts\COPRGTB.TTF => C:/Users/Administrator/AppData/Local/R/cache/R/renv/cache/v5/windows/R-4.4/x86_64-w64-mingw32/extrafontdb/1.0/a861555ddec7451c653b40e713166c6f/extrafontdb/metrics/COPRGTB
C:\Windows\Fonts\COPRGTL.TTF => C:/Users/Administrator/AppData/Local/R/cache/R/renv/cache/v5/windows/R-4.4/x86_64-w64-mingw32/extrafontdb/1.0/a861555ddec7451c653b40e713166c6f/extrafontdb/metrics/COPRGTL
C:\Windows\Fonts\corbel.ttf => C:/Users/Administrator/AppData/Local/R/cache/R/renv/cache/v5/windows/R-4.4/x86_64-w64-mingw32/extrafontdb/1.0/a861555ddec7451c653b40e713166c6f/extrafontdb/metrics/corbel
C:\Windows\Fonts\corbelb.ttf => C:/Users/Administrator/AppData/Local/R/cache/R/renv/cache/v5/windows/R-4.4/x86_64-w64-mingw32/extrafontdb/1.0/a861555ddec7451c653b40e713166c6f/extrafontdb/metrics/corbelb
C:\Windows\Fonts\corbeli.ttf => C:/Users/Administrator/AppData/Local/R/cache/R/renv/cache/v5/windows/R-4.4/x86_64-w64-mingw32/extrafontdb/1.0/a861555ddec7451c653b40e713166c6f/extrafontdb/metrics/corbeli
C:\Windows\Fonts\corbell.ttf => C:/Users/Administrator/AppData/Local/R/cache/R/renv/cache/v5/windows/R-4.4/x86_64-w64-mingw32/extrafontdb/1.0/a861555ddec7451c653b40e713166c6f/extrafontdb/metrics/corbell
C:\Windows\Fonts\corbelli.ttf => C:/Users/Administrator/AppData/Local/R/cache/R/renv/cache/v5/windows/R-4.4/x86_64-w64-mingw32/extrafontdb/1.0/a861555ddec7451c653b40e713166c6f/extrafontdb/metrics/corbelli
C:\Windows\Fonts\corbelz.ttf => C:/Users/Administrator/AppData/Local/R/cache/R/renv/cache/v5/windows/R-4.4/x86_64-w64-mingw32/extrafontdb/1.0/a861555ddec7451c653b40e713166c6f/extrafontdb/metrics/corbelz
C:\Windows\Fonts\cour.ttf => C:/Users/Administrator/AppData/Local/R/cache/R/renv/cache/v5/windows/R-4.4/x86_64-w64-mingw32/extrafontdb/1.0/a861555ddec7451c653b40e713166c6f/extrafontdb/metrics/cour
C:\Windows\Fonts\courbd.ttf => C:/Users/Administrator/AppData/Local/R/cache/R/renv/cache/v5/windows/R-4.4/x86_64-w64-mingw32/extrafontdb/1.0/a861555ddec7451c653b40e713166c6f/extrafontdb/metrics/courbd
C:\Windows\Fonts\courbi.ttf => C:/Users/Administrator/AppData/Local/R/cache/R/renv/cache/v5/windows/R-4.4/x86_64-w64-mingw32/extrafontdb/1.0/a861555ddec7451c653b40e713166c6f/extrafontdb/metrics/courbi
C:\Windows\Fonts\couri.ttf => C:/Users/Administrator/AppData/Local/R/cache/R/renv/cache/v5/windows/R-4.4/x86_64-w64-mingw32/extrafontdb/1.0/a861555ddec7451c653b40e713166c6f/extrafontdb/metrics/couri
C:\Windows\Fonts\CURLZ___.TTF => C:/Users/Administrator/AppData/Local/R/cache/R/renv/cache/v5/windows/R-4.4/x86_64-w64-mingw32/extrafontdb/1.0/a861555ddec7451c653b40e713166c6f/extrafontdb/metrics/CURLZ___
C:\Windows\Fonts\david.ttf => C:/Users/Administrator/AppData/Local/R/cache/R/renv/cache/v5/windows/R-4.4/x86_64-w64-mingw32/extrafontdb/1.0/a861555ddec7451c653b40e713166c6f/extrafontdb/metrics/david
C:\Windows\Fonts\davidbd.ttf => C:/Users/Administrator/AppData/Local/R/cache/R/renv/cache/v5/windows/R-4.4/x86_64-w64-mingw32/extrafontdb/1.0/a861555ddec7451c653b40e713166c6f/extrafontdb/metrics/davidbd
C:\Windows\Fonts\Deleted\HackNerdFont-Bold.ttf : No FontName. Skipping.
C:\Windows\Fonts\Deleted\HackNerdFont-BoldItalic.ttf : No FontName. Skipping.
C:\Windows\Fonts\Deleted\HackNerdFont-Italic.ttf : No FontName. Skipping.
C:\Windows\Fonts\Deleted\HackNerdFont-Regular.ttf : No FontName. Skipping.
C:\Windows\Fonts\Deleted\HackNerdFontMono-Bold.ttf : No FontName. Skipping.
C:\Windows\Fonts\Deleted\HackNerdFontMono-BoldItalic.ttf : No FontName. Skipping.
C:\Windows\Fonts\Deleted\HackNerdFontMono-Italic.ttf : No FontName. Skipping.
C:\Windows\Fonts\Deleted\HackNerdFontMono-Regular.ttf : No FontName. Skipping.
C:\Windows\Fonts\Deleted\HackNerdFontPropo-Bold.ttf : No FontName. Skipping.
C:\Windows\Fonts\Deleted\HackNerdFontPropo-BoldItalic.ttf : No FontName. Skipping.
C:\Windows\Fonts\Deleted\HackNerdFontPropo-Italic.ttf : No FontName. Skipping.
C:\Windows\Fonts\Deleted\HackNerdFontPropo-Regular.ttf : No FontName. Skipping.
C:\Windows\Fonts\DUBAI-BOLD.TTF => C:/Users/Administrator/AppData/Local/R/cache/R/renv/cache/v5/windows/R-4.4/x86_64-w64-mingw32/extrafontdb/1.0/a861555ddec7451c653b40e713166c6f/extrafontdb/metrics/DUBAI-BOLD
C:\Windows\Fonts\DUBAI-LIGHT.TTF => C:/Users/Administrator/AppData/Local/R/cache/R/renv/cache/v5/windows/R-4.4/x86_64-w64-mingw32/extrafontdb/1.0/a861555ddec7451c653b40e713166c6f/extrafontdb/metrics/DUBAI-LIGHT
C:\Windows\Fonts\DUBAI-MEDIUM.TTF => C:/Users/Administrator/AppData/Local/R/cache/R/renv/cache/v5/windows/R-4.4/x86_64-w64-mingw32/extrafontdb/1.0/a861555ddec7451c653b40e713166c6f/extrafontdb/metrics/DUBAI-MEDIUM
C:\Windows\Fonts\DUBAI-REGULAR.TTF => C:/Users/Administrator/AppData/Local/R/cache/R/renv/cache/v5/windows/R-4.4/x86_64-w64-mingw32/extrafontdb/1.0/a861555ddec7451c653b40e713166c6f/extrafontdb/metrics/DUBAI-REGULAR
C:\Windows\Fonts\ebrima.ttf => C:/Users/Administrator/AppData/Local/R/cache/R/renv/cache/v5/windows/R-4.4/x86_64-w64-mingw32/extrafontdb/1.0/a861555ddec7451c653b40e713166c6f/extrafontdb/metrics/ebrima
C:\Windows\Fonts\ebrimabd.ttf => C:/Users/Administrator/AppData/Local/R/cache/R/renv/cache/v5/windows/R-4.4/x86_64-w64-mingw32/extrafontdb/1.0/a861555ddec7451c653b40e713166c6f/extrafontdb/metrics/ebrimabd
C:\Windows\Fonts\ELEPHNT.TTF => C:/Users/Administrator/AppData/Local/R/cache/R/renv/cache/v5/windows/R-4.4/x86_64-w64-mingw32/extrafontdb/1.0/a861555ddec7451c653b40e713166c6f/extrafontdb/metrics/ELEPHNT
C:\Windows\Fonts\ELEPHNTI.TTF => C:/Users/Administrator/AppData/Local/R/cache/R/renv/cache/v5/windows/R-4.4/x86_64-w64-mingw32/extrafontdb/1.0/a861555ddec7451c653b40e713166c6f/extrafontdb/metrics/ELEPHNTI
C:\Windows\Fonts\ENGR.TTF => C:/Users/Administrator/AppData/Local/R/cache/R/renv/cache/v5/windows/R-4.4/x86_64-w64-mingw32/extrafontdb/1.0/a861555ddec7451c653b40e713166c6f/extrafontdb/metrics/ENGR
C:\Windows\Fonts\ERASBD.TTF => C:/Users/Administrator/AppData/Local/R/cache/R/renv/cache/v5/windows/R-4.4/x86_64-w64-mingw32/extrafontdb/1.0/a861555ddec7451c653b40e713166c6f/extrafontdb/metrics/ERASBD
C:\Windows\Fonts\ERASDEMI.TTF => C:/Users/Administrator/AppData/Local/R/cache/R/renv/cache/v5/windows/R-4.4/x86_64-w64-mingw32/extrafontdb/1.0/a861555ddec7451c653b40e713166c6f/extrafontdb/metrics/ERASDEMI
C:\Windows\Fonts\ERASLGHT.TTF => C:/Users/Administrator/AppData/Local/R/cache/R/renv/cache/v5/windows/R-4.4/x86_64-w64-mingw32/extrafontdb/1.0/a861555ddec7451c653b40e713166c6f/extrafontdb/metrics/ERASLGHT
C:\Windows\Fonts\ERASMD.TTF => C:/Users/Administrator/AppData/Local/R/cache/R/renv/cache/v5/windows/R-4.4/x86_64-w64-mingw32/extrafontdb/1.0/a861555ddec7451c653b40e713166c6f/extrafontdb/metrics/ERASMD
C:\Windows\Fonts\FELIXTI.TTF => C:/Users/Administrator/AppData/Local/R/cache/R/renv/cache/v5/windows/R-4.4/x86_64-w64-mingw32/extrafontdb/1.0/a861555ddec7451c653b40e713166c6f/extrafontdb/metrics/FELIXTI
C:\Windows\Fonts\FORTE.TTF => C:/Users/Administrator/AppData/Local/R/cache/R/renv/cache/v5/windows/R-4.4/x86_64-w64-mingw32/extrafontdb/1.0/a861555ddec7451c653b40e713166c6f/extrafontdb/metrics/FORTE
C:\Windows\Fonts\FRABK.TTF => C:/Users/Administrator/AppData/Local/R/cache/R/renv/cache/v5/windows/R-4.4/x86_64-w64-mingw32/extrafontdb/1.0/a861555ddec7451c653b40e713166c6f/extrafontdb/metrics/FRABK
C:\Windows\Fonts\FRABKIT.TTF => C:/Users/Administrator/AppData/Local/R/cache/R/renv/cache/v5/windows/R-4.4/x86_64-w64-mingw32/extrafontdb/1.0/a861555ddec7451c653b40e713166c6f/extrafontdb/metrics/FRABKIT
C:\Windows\Fonts\FRADM.TTF => C:/Users/Administrator/AppData/Local/R/cache/R/renv/cache/v5/windows/R-4.4/x86_64-w64-mingw32/extrafontdb/1.0/a861555ddec7451c653b40e713166c6f/extrafontdb/metrics/FRADM
C:\Windows\Fonts\FRADMCN.TTF => C:/Users/Administrator/AppData/Local/R/cache/R/renv/cache/v5/windows/R-4.4/x86_64-w64-mingw32/extrafontdb/1.0/a861555ddec7451c653b40e713166c6f/extrafontdb/metrics/FRADMCN
C:\Windows\Fonts\FRADMIT.TTF => C:/Users/Administrator/AppData/Local/R/cache/R/renv/cache/v5/windows/R-4.4/x86_64-w64-mingw32/extrafontdb/1.0/a861555ddec7451c653b40e713166c6f/extrafontdb/metrics/FRADMIT
C:\Windows\Fonts\FRAHV.TTF => C:/Users/Administrator/AppData/Local/R/cache/R/renv/cache/v5/windows/R-4.4/x86_64-w64-mingw32/extrafontdb/1.0/a861555ddec7451c653b40e713166c6f/extrafontdb/metrics/FRAHV
C:\Windows\Fonts\FRAHVIT.TTF => C:/Users/Administrator/AppData/Local/R/cache/R/renv/cache/v5/windows/R-4.4/x86_64-w64-mingw32/extrafontdb/1.0/a861555ddec7451c653b40e713166c6f/extrafontdb/metrics/FRAHVIT
C:\Windows\Fonts\framd.ttf => C:/Users/Administrator/AppData/Local/R/cache/R/renv/cache/v5/windows/R-4.4/x86_64-w64-mingw32/extrafontdb/1.0/a861555ddec7451c653b40e713166c6f/extrafontdb/metrics/framd
C:\Windows\Fonts\FRAMDCN.TTF => C:/Users/Administrator/AppData/Local/R/cache/R/renv/cache/v5/windows/R-4.4/x86_64-w64-mingw32/extrafontdb/1.0/a861555ddec7451c653b40e713166c6f/extrafontdb/metrics/FRAMDCN
C:\Windows\Fonts\framdit.ttf => C:/Users/Administrator/AppData/Local/R/cache/R/renv/cache/v5/windows/R-4.4/x86_64-w64-mingw32/extrafontdb/1.0/a861555ddec7451c653b40e713166c6f/extrafontdb/metrics/framdit
C:\Windows\Fonts\frank.ttf => C:/Users/Administrator/AppData/Local/R/cache/R/renv/cache/v5/windows/R-4.4/x86_64-w64-mingw32/extrafontdb/1.0/a861555ddec7451c653b40e713166c6f/extrafontdb/metrics/frank
C:\Windows\Fonts\FREESCPT.TTF => C:/Users/Administrator/AppData/Local/R/cache/R/renv/cache/v5/windows/R-4.4/x86_64-w64-mingw32/extrafontdb/1.0/a861555ddec7451c653b40e713166c6f/extrafontdb/metrics/FREESCPT
C:\Windows\Fonts\FRSCRIPT.TTF => C:/Users/Administrator/AppData/Local/R/cache/R/renv/cache/v5/windows/R-4.4/x86_64-w64-mingw32/extrafontdb/1.0/a861555ddec7451c653b40e713166c6f/extrafontdb/metrics/FRSCRIPT
C:\Windows\Fonts\FTLTLT.TTF => C:/Users/Administrator/AppData/Local/R/cache/R/renv/cache/v5/windows/R-4.4/x86_64-w64-mingw32/extrafontdb/1.0/a861555ddec7451c653b40e713166c6f/extrafontdb/metrics/FTLTLT
C:\Windows\Fonts\Gabriola.ttf => C:/Users/Administrator/AppData/Local/R/cache/R/renv/cache/v5/windows/R-4.4/x86_64-w64-mingw32/extrafontdb/1.0/a861555ddec7451c653b40e713166c6f/extrafontdb/metrics/Gabriola
C:\Windows\Fonts\gadugi.ttf => C:/Users/Administrator/AppData/Local/R/cache/R/renv/cache/v5/windows/R-4.4/x86_64-w64-mingw32/extrafontdb/1.0/a861555ddec7451c653b40e713166c6f/extrafontdb/metrics/gadugi
C:\Windows\Fonts\gadugib.ttf => C:/Users/Administrator/AppData/Local/R/cache/R/renv/cache/v5/windows/R-4.4/x86_64-w64-mingw32/extrafontdb/1.0/a861555ddec7451c653b40e713166c6f/extrafontdb/metrics/gadugib
C:\Windows\Fonts\GARA.TTF => C:/Users/Administrator/AppData/Local/R/cache/R/renv/cache/v5/windows/R-4.4/x86_64-w64-mingw32/extrafontdb/1.0/a861555ddec7451c653b40e713166c6f/extrafontdb/metrics/GARA
C:\Windows\Fonts\GARABD.TTF => C:/Users/Administrator/AppData/Local/R/cache/R/renv/cache/v5/windows/R-4.4/x86_64-w64-mingw32/extrafontdb/1.0/a861555ddec7451c653b40e713166c6f/extrafontdb/metrics/GARABD
C:\Windows\Fonts\GARAIT.TTF => C:/Users/Administrator/AppData/Local/R/cache/R/renv/cache/v5/windows/R-4.4/x86_64-w64-mingw32/extrafontdb/1.0/a861555ddec7451c653b40e713166c6f/extrafontdb/metrics/GARAIT
C:\Windows\Fonts\georgia.ttf => C:/Users/Administrator/AppData/Local/R/cache/R/renv/cache/v5/windows/R-4.4/x86_64-w64-mingw32/extrafontdb/1.0/a861555ddec7451c653b40e713166c6f/extrafontdb/metrics/georgia
C:\Windows\Fonts\georgiab.ttf => C:/Users/Administrator/AppData/Local/R/cache/R/renv/cache/v5/windows/R-4.4/x86_64-w64-mingw32/extrafontdb/1.0/a861555ddec7451c653b40e713166c6f/extrafontdb/metrics/georgiab
C:\Windows\Fonts\georgiai.ttf => C:/Users/Administrator/AppData/Local/R/cache/R/renv/cache/v5/windows/R-4.4/x86_64-w64-mingw32/extrafontdb/1.0/a861555ddec7451c653b40e713166c6f/extrafontdb/metrics/georgiai
C:\Windows\Fonts\georgiaz.ttf => C:/Users/Administrator/AppData/Local/R/cache/R/renv/cache/v5/windows/R-4.4/x86_64-w64-mingw32/extrafontdb/1.0/a861555ddec7451c653b40e713166c6f/extrafontdb/metrics/georgiaz
C:\Windows\Fonts\GIGI.TTF => C:/Users/Administrator/AppData/Local/R/cache/R/renv/cache/v5/windows/R-4.4/x86_64-w64-mingw32/extrafontdb/1.0/a861555ddec7451c653b40e713166c6f/extrafontdb/metrics/GIGI
C:\Windows\Fonts\GIL_____.TTF => C:/Users/Administrator/AppData/Local/R/cache/R/renv/cache/v5/windows/R-4.4/x86_64-w64-mingw32/extrafontdb/1.0/a861555ddec7451c653b40e713166c6f/extrafontdb/metrics/GIL_____
C:\Windows\Fonts\GILB____.TTF => C:/Users/Administrator/AppData/Local/R/cache/R/renv/cache/v5/windows/R-4.4/x86_64-w64-mingw32/extrafontdb/1.0/a861555ddec7451c653b40e713166c6f/extrafontdb/metrics/GILB____
C:\Windows\Fonts\GILBI___.TTF => C:/Users/Administrator/AppData/Local/R/cache/R/renv/cache/v5/windows/R-4.4/x86_64-w64-mingw32/extrafontdb/1.0/a861555ddec7451c653b40e713166c6f/extrafontdb/metrics/GILBI___
C:\Windows\Fonts\GILC____.TTF => C:/Users/Administrator/AppData/Local/R/cache/R/renv/cache/v5/windows/R-4.4/x86_64-w64-mingw32/extrafontdb/1.0/a861555ddec7451c653b40e713166c6f/extrafontdb/metrics/GILC____
C:\Windows\Fonts\GILI____.TTF => C:/Users/Administrator/AppData/Local/R/cache/R/renv/cache/v5/windows/R-4.4/x86_64-w64-mingw32/extrafontdb/1.0/a861555ddec7451c653b40e713166c6f/extrafontdb/metrics/GILI____
C:\Windows\Fonts\GILLUBCD.TTF => C:/Users/Administrator/AppData/Local/R/cache/R/renv/cache/v5/windows/R-4.4/x86_64-w64-mingw32/extrafontdb/1.0/a861555ddec7451c653b40e713166c6f/extrafontdb/metrics/GILLUBCD
C:\Windows\Fonts\GILSANUB.TTF => C:/Users/Administrator/AppData/Local/R/cache/R/renv/cache/v5/windows/R-4.4/x86_64-w64-mingw32/extrafontdb/1.0/a861555ddec7451c653b40e713166c6f/extrafontdb/metrics/GILSANUB
C:\Windows\Fonts\gisha.ttf => C:/Users/Administrator/AppData/Local/R/cache/R/renv/cache/v5/windows/R-4.4/x86_64-w64-mingw32/extrafontdb/1.0/a861555ddec7451c653b40e713166c6f/extrafontdb/metrics/gisha
C:\Windows\Fonts\gishabd.ttf => C:/Users/Administrator/AppData/Local/R/cache/R/renv/cache/v5/windows/R-4.4/x86_64-w64-mingw32/extrafontdb/1.0/a861555ddec7451c653b40e713166c6f/extrafontdb/metrics/gishabd
C:\Windows\Fonts\GLECB.TTF => C:/Users/Administrator/AppData/Local/R/cache/R/renv/cache/v5/windows/R-4.4/x86_64-w64-mingw32/extrafontdb/1.0/a861555ddec7451c653b40e713166c6f/extrafontdb/metrics/GLECB
C:\Windows\Fonts\GLSNECB.TTF => C:/Users/Administrator/AppData/Local/R/cache/R/renv/cache/v5/windows/R-4.4/x86_64-w64-mingw32/extrafontdb/1.0/a861555ddec7451c653b40e713166c6f/extrafontdb/metrics/GLSNECB
C:\Windows\Fonts\GOTHIC.TTF => C:/Users/Administrator/AppData/Local/R/cache/R/renv/cache/v5/windows/R-4.4/x86_64-w64-mingw32/extrafontdb/1.0/a861555ddec7451c653b40e713166c6f/extrafontdb/metrics/GOTHIC
C:\Windows\Fonts\GOTHICB.TTF => C:/Users/Administrator/AppData/Local/R/cache/R/renv/cache/v5/windows/R-4.4/x86_64-w64-mingw32/extrafontdb/1.0/a861555ddec7451c653b40e713166c6f/extrafontdb/metrics/GOTHICB
C:\Windows\Fonts\GOTHICBI.TTF => C:/Users/Administrator/AppData/Local/R/cache/R/renv/cache/v5/windows/R-4.4/x86_64-w64-mingw32/extrafontdb/1.0/a861555ddec7451c653b40e713166c6f/extrafontdb/metrics/GOTHICBI
C:\Windows\Fonts\GOTHICI.TTF => C:/Users/Administrator/AppData/Local/R/cache/R/renv/cache/v5/windows/R-4.4/x86_64-w64-mingw32/extrafontdb/1.0/a861555ddec7451c653b40e713166c6f/extrafontdb/metrics/GOTHICI
C:\Windows\Fonts\GOUDOS.TTF => C:/Users/Administrator/AppData/Local/R/cache/R/renv/cache/v5/windows/R-4.4/x86_64-w64-mingw32/extrafontdb/1.0/a861555ddec7451c653b40e713166c6f/extrafontdb/metrics/GOUDOS
C:\Windows\Fonts\GOUDOSB.TTF => C:/Users/Administrator/AppData/Local/R/cache/R/renv/cache/v5/windows/R-4.4/x86_64-w64-mingw32/extrafontdb/1.0/a861555ddec7451c653b40e713166c6f/extrafontdb/metrics/GOUDOSB
C:\Windows\Fonts\GOUDOSI.TTF => C:/Users/Administrator/AppData/Local/R/cache/R/renv/cache/v5/windows/R-4.4/x86_64-w64-mingw32/extrafontdb/1.0/a861555ddec7451c653b40e713166c6f/extrafontdb/metrics/GOUDOSI
C:\Windows\Fonts\GOUDYSTO.TTF => C:/Users/Administrator/AppData/Local/R/cache/R/renv/cache/v5/windows/R-4.4/x86_64-w64-mingw32/extrafontdb/1.0/a861555ddec7451c653b40e713166c6f/extrafontdb/metrics/GOUDYSTO
C:\Windows\Fonts\HackNerdFont-Bold.ttf : No FontName. Skipping.
C:\Windows\Fonts\HackNerdFont-BoldItalic.ttf : No FontName. Skipping.
C:\Windows\Fonts\HackNerdFont-Italic.ttf : No FontName. Skipping.
C:\Windows\Fonts\HackNerdFont-Regular.ttf : No FontName. Skipping.
C:\Windows\Fonts\HackNerdFontMono-Bold.ttf : No FontName. Skipping.
C:\Windows\Fonts\HackNerdFontMono-BoldItalic.ttf : No FontName. Skipping.
C:\Windows\Fonts\HackNerdFontMono-Italic.ttf : No FontName. Skipping.
C:\Windows\Fonts\HackNerdFontMono-Regular.ttf : No FontName. Skipping.
C:\Windows\Fonts\HackNerdFontPropo-Bold.ttf : No FontName. Skipping.
C:\Windows\Fonts\HackNerdFontPropo-BoldItalic.ttf : No FontName. Skipping.
C:\Windows\Fonts\HackNerdFontPropo-Italic.ttf : No FontName. Skipping.
C:\Windows\Fonts\HackNerdFontPropo-Regular.ttf : No FontName. Skipping.
C:\Windows\Fonts\HARLOWSI.TTF => C:/Users/Administrator/AppData/Local/R/cache/R/renv/cache/v5/windows/R-4.4/x86_64-w64-mingw32/extrafontdb/1.0/a861555ddec7451c653b40e713166c6f/extrafontdb/metrics/HARLOWSI
C:\Windows\Fonts\HARNGTON.TTF => C:/Users/Administrator/AppData/Local/R/cache/R/renv/cache/v5/windows/R-4.4/x86_64-w64-mingw32/extrafontdb/1.0/a861555ddec7451c653b40e713166c6f/extrafontdb/metrics/HARNGTON
C:\Windows\Fonts\HATTEN.TTF => C:/Users/Administrator/AppData/Local/R/cache/R/renv/cache/v5/windows/R-4.4/x86_64-w64-mingw32/extrafontdb/1.0/a861555ddec7451c653b40e713166c6f/extrafontdb/metrics/HATTEN
C:\Windows\Fonts\HeavyDataNerdFont-Regular.ttf : No FontName. Skipping.
C:\Windows\Fonts\HeavyDataNerdFontPropo-Regular.ttf : No FontName. Skipping.
C:\Windows\Fonts\himalaya.ttf => C:/Users/Administrator/AppData/Local/R/cache/R/renv/cache/v5/windows/R-4.4/x86_64-w64-mingw32/extrafontdb/1.0/a861555ddec7451c653b40e713166c6f/extrafontdb/metrics/himalaya
C:\Windows\Fonts\HTOWERT.TTF => C:/Users/Administrator/AppData/Local/R/cache/R/renv/cache/v5/windows/R-4.4/x86_64-w64-mingw32/extrafontdb/1.0/a861555ddec7451c653b40e713166c6f/extrafontdb/metrics/HTOWERT
C:\Windows\Fonts\HTOWERTI.TTF => C:/Users/Administrator/AppData/Local/R/cache/R/renv/cache/v5/windows/R-4.4/x86_64-w64-mingw32/extrafontdb/1.0/a861555ddec7451c653b40e713166c6f/extrafontdb/metrics/HTOWERTI
C:\Windows\Fonts\impact.ttf => C:/Users/Administrator/AppData/Local/R/cache/R/renv/cache/v5/windows/R-4.4/x86_64-w64-mingw32/extrafontdb/1.0/a861555ddec7451c653b40e713166c6f/extrafontdb/metrics/impact
C:\Windows\Fonts\IMPRISHA.TTF => C:/Users/Administrator/AppData/Local/R/cache/R/renv/cache/v5/windows/R-4.4/x86_64-w64-mingw32/extrafontdb/1.0/a861555ddec7451c653b40e713166c6f/extrafontdb/metrics/IMPRISHA
C:\Windows\Fonts\INFROMAN.TTF => C:/Users/Administrator/AppData/Local/R/cache/R/renv/cache/v5/windows/R-4.4/x86_64-w64-mingw32/extrafontdb/1.0/a861555ddec7451c653b40e713166c6f/extrafontdb/metrics/INFROMAN
C:\Windows\Fonts\Inkfree.ttf => C:/Users/Administrator/AppData/Local/R/cache/R/renv/cache/v5/windows/R-4.4/x86_64-w64-mingw32/extrafontdb/1.0/a861555ddec7451c653b40e713166c6f/extrafontdb/metrics/Inkfree
C:\Windows\Fonts\ITCBLKAD.TTF => C:/Users/Administrator/AppData/Local/R/cache/R/renv/cache/v5/windows/R-4.4/x86_64-w64-mingw32/extrafontdb/1.0/a861555ddec7451c653b40e713166c6f/extrafontdb/metrics/ITCBLKAD
C:\Windows\Fonts\ITCEDSCR.TTF => C:/Users/Administrator/AppData/Local/R/cache/R/renv/cache/v5/windows/R-4.4/x86_64-w64-mingw32/extrafontdb/1.0/a861555ddec7451c653b40e713166c6f/extrafontdb/metrics/ITCEDSCR
C:\Windows\Fonts\ITCKRIST.TTF => C:/Users/Administrator/AppData/Local/R/cache/R/renv/cache/v5/windows/R-4.4/x86_64-w64-mingw32/extrafontdb/1.0/a861555ddec7451c653b40e713166c6f/extrafontdb/metrics/ITCKRIST
C:\Windows\Fonts\javatext.ttf => C:/Users/Administrator/AppData/Local/R/cache/R/renv/cache/v5/windows/R-4.4/x86_64-w64-mingw32/extrafontdb/1.0/a861555ddec7451c653b40e713166c6f/extrafontdb/metrics/javatext
C:\Windows\Fonts\JOKERMAN.TTF => C:/Users/Administrator/AppData/Local/R/cache/R/renv/cache/v5/windows/R-4.4/x86_64-w64-mingw32/extrafontdb/1.0/a861555ddec7451c653b40e713166c6f/extrafontdb/metrics/JOKERMAN
C:\Windows\Fonts\JUICE___.TTF => C:/Users/Administrator/AppData/Local/R/cache/R/renv/cache/v5/windows/R-4.4/x86_64-w64-mingw32/extrafontdb/1.0/a861555ddec7451c653b40e713166c6f/extrafontdb/metrics/JUICE___
C:\Windows\Fonts\KUNSTLER.TTF => C:/Users/Administrator/AppData/Local/R/cache/R/renv/cache/v5/windows/R-4.4/x86_64-w64-mingw32/extrafontdb/1.0/a861555ddec7451c653b40e713166c6f/extrafontdb/metrics/KUNSTLER
C:\Windows\Fonts\l_10646.ttf => C:/Users/Administrator/AppData/Local/R/cache/R/renv/cache/v5/windows/R-4.4/x86_64-w64-mingw32/extrafontdb/1.0/a861555ddec7451c653b40e713166c6f/extrafontdb/metrics/l_10646
C:\Windows\Fonts\LATINWD.TTF => C:/Users/Administrator/AppData/Local/R/cache/R/renv/cache/v5/windows/R-4.4/x86_64-w64-mingw32/extrafontdb/1.0/a861555ddec7451c653b40e713166c6f/extrafontdb/metrics/LATINWD
C:\Windows\Fonts\LBRITE.TTF => C:/Users/Administrator/AppData/Local/R/cache/R/renv/cache/v5/windows/R-4.4/x86_64-w64-mingw32/extrafontdb/1.0/a861555ddec7451c653b40e713166c6f/extrafontdb/metrics/LBRITE
C:\Windows\Fonts\LBRITED.TTF => C:/Users/Administrator/AppData/Local/R/cache/R/renv/cache/v5/windows/R-4.4/x86_64-w64-mingw32/extrafontdb/1.0/a861555ddec7451c653b40e713166c6f/extrafontdb/metrics/LBRITED
C:\Windows\Fonts\LBRITEDI.TTF => C:/Users/Administrator/AppData/Local/R/cache/R/renv/cache/v5/windows/R-4.4/x86_64-w64-mingw32/extrafontdb/1.0/a861555ddec7451c653b40e713166c6f/extrafontdb/metrics/LBRITEDI
C:\Windows\Fonts\LBRITEI.TTF => C:/Users/Administrator/AppData/Local/R/cache/R/renv/cache/v5/windows/R-4.4/x86_64-w64-mingw32/extrafontdb/1.0/a861555ddec7451c653b40e713166c6f/extrafontdb/metrics/LBRITEI
C:\Windows\Fonts\LCALLIG.TTF => C:/Users/Administrator/AppData/Local/R/cache/R/renv/cache/v5/windows/R-4.4/x86_64-w64-mingw32/extrafontdb/1.0/a861555ddec7451c653b40e713166c6f/extrafontdb/metrics/LCALLIG
C:\Windows\Fonts\LeelaUIb.ttf => C:/Users/Administrator/AppData/Local/R/cache/R/renv/cache/v5/windows/R-4.4/x86_64-w64-mingw32/extrafontdb/1.0/a861555ddec7451c653b40e713166c6f/extrafontdb/metrics/LeelaUIb
C:\Windows\Fonts\LEELAWAD.TTF => C:/Users/Administrator/AppData/Local/R/cache/R/renv/cache/v5/windows/R-4.4/x86_64-w64-mingw32/extrafontdb/1.0/a861555ddec7451c653b40e713166c6f/extrafontdb/metrics/LEELAWAD
C:\Windows\Fonts\LEELAWDB.TTF => C:/Users/Administrator/AppData/Local/R/cache/R/renv/cache/v5/windows/R-4.4/x86_64-w64-mingw32/extrafontdb/1.0/a861555ddec7451c653b40e713166c6f/extrafontdb/metrics/LEELAWDB
C:\Windows\Fonts\LeelawUI.ttf => C:/Users/Administrator/AppData/Local/R/cache/R/renv/cache/v5/windows/R-4.4/x86_64-w64-mingw32/extrafontdb/1.0/a861555ddec7451c653b40e713166c6f/extrafontdb/metrics/LeelawUI
C:\Windows\Fonts\LeelUIsl.ttf => C:/Users/Administrator/AppData/Local/R/cache/R/renv/cache/v5/windows/R-4.4/x86_64-w64-mingw32/extrafontdb/1.0/a861555ddec7451c653b40e713166c6f/extrafontdb/metrics/LeelUIsl
C:\Windows\Fonts\LFAX.TTF => C:/Users/Administrator/AppData/Local/R/cache/R/renv/cache/v5/windows/R-4.4/x86_64-w64-mingw32/extrafontdb/1.0/a861555ddec7451c653b40e713166c6f/extrafontdb/metrics/LFAX
C:\Windows\Fonts\LFAXD.TTF => C:/Users/Administrator/AppData/Local/R/cache/R/renv/cache/v5/windows/R-4.4/x86_64-w64-mingw32/extrafontdb/1.0/a861555ddec7451c653b40e713166c6f/extrafontdb/metrics/LFAXD
C:\Windows\Fonts\LFAXDI.TTF => C:/Users/Administrator/AppData/Local/R/cache/R/renv/cache/v5/windows/R-4.4/x86_64-w64-mingw32/extrafontdb/1.0/a861555ddec7451c653b40e713166c6f/extrafontdb/metrics/LFAXDI
C:\Windows\Fonts\LFAXI.TTF => C:/Users/Administrator/AppData/Local/R/cache/R/renv/cache/v5/windows/R-4.4/x86_64-w64-mingw32/extrafontdb/1.0/a861555ddec7451c653b40e713166c6f/extrafontdb/metrics/LFAXI
C:\Windows\Fonts\LHANDW.TTF => C:/Users/Administrator/AppData/Local/R/cache/R/renv/cache/v5/windows/R-4.4/x86_64-w64-mingw32/extrafontdb/1.0/a861555ddec7451c653b40e713166c6f/extrafontdb/metrics/LHANDW
C:\Windows\Fonts\LSANS.TTF => C:/Users/Administrator/AppData/Local/R/cache/R/renv/cache/v5/windows/R-4.4/x86_64-w64-mingw32/extrafontdb/1.0/a861555ddec7451c653b40e713166c6f/extrafontdb/metrics/LSANS
C:\Windows\Fonts\LSANSD.TTF => C:/Users/Administrator/AppData/Local/R/cache/R/renv/cache/v5/windows/R-4.4/x86_64-w64-mingw32/extrafontdb/1.0/a861555ddec7451c653b40e713166c6f/extrafontdb/metrics/LSANSD
C:\Windows\Fonts\LSANSDI.TTF => C:/Users/Administrator/AppData/Local/R/cache/R/renv/cache/v5/windows/R-4.4/x86_64-w64-mingw32/extrafontdb/1.0/a861555ddec7451c653b40e713166c6f/extrafontdb/metrics/LSANSDI
C:\Windows\Fonts\LSANSI.TTF => C:/Users/Administrator/AppData/Local/R/cache/R/renv/cache/v5/windows/R-4.4/x86_64-w64-mingw32/extrafontdb/1.0/a861555ddec7451c653b40e713166c6f/extrafontdb/metrics/LSANSI
C:\Windows\Fonts\LTYPE.TTF => C:/Users/Administrator/AppData/Local/R/cache/R/renv/cache/v5/windows/R-4.4/x86_64-w64-mingw32/extrafontdb/1.0/a861555ddec7451c653b40e713166c6f/extrafontdb/metrics/LTYPE
C:\Windows\Fonts\LTYPEB.TTF => C:/Users/Administrator/AppData/Local/R/cache/R/renv/cache/v5/windows/R-4.4/x86_64-w64-mingw32/extrafontdb/1.0/a861555ddec7451c653b40e713166c6f/extrafontdb/metrics/LTYPEB
C:\Windows\Fonts\LTYPEBO.TTF => C:/Users/Administrator/AppData/Local/R/cache/R/renv/cache/v5/windows/R-4.4/x86_64-w64-mingw32/extrafontdb/1.0/a861555ddec7451c653b40e713166c6f/extrafontdb/metrics/LTYPEBO
C:\Windows\Fonts\LTYPEO.TTF => C:/Users/Administrator/AppData/Local/R/cache/R/renv/cache/v5/windows/R-4.4/x86_64-w64-mingw32/extrafontdb/1.0/a861555ddec7451c653b40e713166c6f/extrafontdb/metrics/LTYPEO
C:\Windows\Fonts\lucon.ttf => C:/Users/Administrator/AppData/Local/R/cache/R/renv/cache/v5/windows/R-4.4/x86_64-w64-mingw32/extrafontdb/1.0/a861555ddec7451c653b40e713166c6f/extrafontdb/metrics/lucon
C:\Windows\Fonts\lvnm.ttf => C:/Users/Administrator/AppData/Local/R/cache/R/renv/cache/v5/windows/R-4.4/x86_64-w64-mingw32/extrafontdb/1.0/a861555ddec7451c653b40e713166c6f/extrafontdb/metrics/lvnm
C:\Windows\Fonts\lvnmbd.ttf => C:/Users/Administrator/AppData/Local/R/cache/R/renv/cache/v5/windows/R-4.4/x86_64-w64-mingw32/extrafontdb/1.0/a861555ddec7451c653b40e713166c6f/extrafontdb/metrics/lvnmbd
C:\Windows\Fonts\MAGNETOB.TTF => C:/Users/Administrator/AppData/Local/R/cache/R/renv/cache/v5/windows/R-4.4/x86_64-w64-mingw32/extrafontdb/1.0/a861555ddec7451c653b40e713166c6f/extrafontdb/metrics/MAGNETOB
C:\Windows\Fonts\MAIAN.TTF => C:/Users/Administrator/AppData/Local/R/cache/R/renv/cache/v5/windows/R-4.4/x86_64-w64-mingw32/extrafontdb/1.0/a861555ddec7451c653b40e713166c6f/extrafontdb/metrics/MAIAN
C:\Windows\Fonts\majalla.ttf => C:/Users/Administrator/AppData/Local/R/cache/R/renv/cache/v5/windows/R-4.4/x86_64-w64-mingw32/extrafontdb/1.0/a861555ddec7451c653b40e713166c6f/extrafontdb/metrics/majalla
C:\Windows\Fonts\majallab.ttf => C:/Users/Administrator/AppData/Local/R/cache/R/renv/cache/v5/windows/R-4.4/x86_64-w64-mingw32/extrafontdb/1.0/a861555ddec7451c653b40e713166c6f/extrafontdb/metrics/majallab
C:\Windows\Fonts\malgun.ttf => C:/Users/Administrator/AppData/Local/R/cache/R/renv/cache/v5/windows/R-4.4/x86_64-w64-mingw32/extrafontdb/1.0/a861555ddec7451c653b40e713166c6f/extrafontdb/metrics/malgun
C:\Windows\Fonts\malgunbd.ttf => C:/Users/Administrator/AppData/Local/R/cache/R/renv/cache/v5/windows/R-4.4/x86_64-w64-mingw32/extrafontdb/1.0/a861555ddec7451c653b40e713166c6f/extrafontdb/metrics/malgunbd
C:\Windows\Fonts\malgunsl.ttf => C:/Users/Administrator/AppData/Local/R/cache/R/renv/cache/v5/windows/R-4.4/x86_64-w64-mingw32/extrafontdb/1.0/a861555ddec7451c653b40e713166c6f/extrafontdb/metrics/malgunsl
C:\Windows\Fonts\marlett.ttf => C:/Users/Administrator/AppData/Local/R/cache/R/renv/cache/v5/windows/R-4.4/x86_64-w64-mingw32/extrafontdb/1.0/a861555ddec7451c653b40e713166c6f/extrafontdb/metrics/marlett
C:\Windows\Fonts\MATURASC.TTF => C:/Users/Administrator/AppData/Local/R/cache/R/renv/cache/v5/windows/R-4.4/x86_64-w64-mingw32/extrafontdb/1.0/a861555ddec7451c653b40e713166c6f/extrafontdb/metrics/MATURASC
C:\Windows\Fonts\MesloLGLDZNerdFont-Bold.ttf : No FontName. Skipping.
C:\Windows\Fonts\MesloLGLDZNerdFont-BoldItalic.ttf : No FontName. Skipping.
C:\Windows\Fonts\MesloLGLDZNerdFont-Italic.ttf : No FontName. Skipping.
C:\Windows\Fonts\MesloLGLDZNerdFont-Regular.ttf : No FontName. Skipping.
C:\Windows\Fonts\MesloLGLDZNerdFontMono-Bold.ttf : No FontName. Skipping.
C:\Windows\Fonts\MesloLGLDZNerdFontMono-BoldItalic.ttf : No FontName. Skipping.
C:\Windows\Fonts\MesloLGLDZNerdFontMono-Italic.ttf : No FontName. Skipping.
C:\Windows\Fonts\MesloLGLDZNerdFontMono-Regular.ttf : No FontName. Skipping.
C:\Windows\Fonts\MesloLGLDZNerdFontPropo-Bold.ttf : No FontName. Skipping.
C:\Windows\Fonts\MesloLGLDZNerdFontPropo-BoldItalic.ttf : No FontName. Skipping.
C:\Windows\Fonts\MesloLGLDZNerdFontPropo-Italic.ttf : No FontName. Skipping.
C:\Windows\Fonts\MesloLGLDZNerdFontPropo-Regular.ttf : No FontName. Skipping.
C:\Windows\Fonts\MesloLGLNerdFont-Bold.ttf : No FontName. Skipping.
C:\Windows\Fonts\MesloLGLNerdFont-BoldItalic.ttf : No FontName. Skipping.
C:\Windows\Fonts\MesloLGLNerdFont-Italic.ttf : No FontName. Skipping.
C:\Windows\Fonts\MesloLGLNerdFont-Regular.ttf : No FontName. Skipping.
C:\Windows\Fonts\MesloLGLNerdFontMono-Bold.ttf : No FontName. Skipping.
C:\Windows\Fonts\MesloLGLNerdFontMono-BoldItalic.ttf : No FontName. Skipping.
C:\Windows\Fonts\MesloLGLNerdFontMono-Italic.ttf : No FontName. Skipping.
C:\Windows\Fonts\MesloLGLNerdFontMono-Regular.ttf : No FontName. Skipping.
C:\Windows\Fonts\MesloLGLNerdFontPropo-Bold.ttf : No FontName. Skipping.
C:\Windows\Fonts\MesloLGLNerdFontPropo-BoldItalic.ttf : No FontName. Skipping.
C:\Windows\Fonts\MesloLGLNerdFontPropo-Italic.ttf : No FontName. Skipping.
C:\Windows\Fonts\MesloLGLNerdFontPropo-Regular.ttf : No FontName. Skipping.
C:\Windows\Fonts\MesloLGMDZNerdFont-Bold.ttf : No FontName. Skipping.
C:\Windows\Fonts\MesloLGMDZNerdFont-BoldItalic.ttf : No FontName. Skipping.
C:\Windows\Fonts\MesloLGMDZNerdFont-Italic.ttf : No FontName. Skipping.
C:\Windows\Fonts\MesloLGMDZNerdFont-Regular.ttf : No FontName. Skipping.
C:\Windows\Fonts\MesloLGMDZNerdFontMono-Bold.ttf : No FontName. Skipping.
C:\Windows\Fonts\MesloLGMDZNerdFontMono-BoldItalic.ttf : No FontName. Skipping.
C:\Windows\Fonts\MesloLGMDZNerdFontMono-Italic.ttf : No FontName. Skipping.
C:\Windows\Fonts\MesloLGMDZNerdFontMono-Regular.ttf : No FontName. Skipping.
C:\Windows\Fonts\MesloLGMDZNerdFontPropo-Bold.ttf : No FontName. Skipping.
C:\Windows\Fonts\MesloLGMDZNerdFontPropo-BoldItalic.ttf : No FontName. Skipping.
C:\Windows\Fonts\MesloLGMDZNerdFontPropo-Italic.ttf : No FontName. Skipping.
C:\Windows\Fonts\MesloLGMDZNerdFontPropo-Regular.ttf : No FontName. Skipping.
C:\Windows\Fonts\MesloLGMNerdFont-Bold.ttf : No FontName. Skipping.
C:\Windows\Fonts\MesloLGMNerdFont-BoldItalic.ttf : No FontName. Skipping.
C:\Windows\Fonts\MesloLGMNerdFont-Italic.ttf : No FontName. Skipping.
C:\Windows\Fonts\MesloLGMNerdFont-Regular.ttf : No FontName. Skipping.
C:\Windows\Fonts\MesloLGMNerdFontMono-Bold.ttf : No FontName. Skipping.
C:\Windows\Fonts\MesloLGMNerdFontMono-BoldItalic.ttf : No FontName. Skipping.
C:\Windows\Fonts\MesloLGMNerdFontMono-Italic.ttf : No FontName. Skipping.
C:\Windows\Fonts\MesloLGMNerdFontMono-Regular.ttf : No FontName. Skipping.
C:\Windows\Fonts\MesloLGMNerdFontPropo-Bold.ttf : No FontName. Skipping.
C:\Windows\Fonts\MesloLGMNerdFontPropo-BoldItalic.ttf : No FontName. Skipping.
C:\Windows\Fonts\MesloLGMNerdFontPropo-Italic.ttf : No FontName. Skipping.
C:\Windows\Fonts\MesloLGMNerdFontPropo-Regular.ttf : No FontName. Skipping.
C:\Windows\Fonts\MesloLGSDZNerdFont-Bold.ttf : No FontName. Skipping.
C:\Windows\Fonts\MesloLGSDZNerdFont-BoldItalic.ttf : No FontName. Skipping.
C:\Windows\Fonts\MesloLGSDZNerdFont-Italic.ttf : No FontName. Skipping.
C:\Windows\Fonts\MesloLGSDZNerdFont-Regular.ttf : No FontName. Skipping.
C:\Windows\Fonts\MesloLGSDZNerdFontMono-Bold.ttf : No FontName. Skipping.
C:\Windows\Fonts\MesloLGSDZNerdFontMono-BoldItalic.ttf : No FontName. Skipping.
C:\Windows\Fonts\MesloLGSDZNerdFontMono-Italic.ttf : No FontName. Skipping.
C:\Windows\Fonts\MesloLGSDZNerdFontMono-Regular.ttf : No FontName. Skipping.
C:\Windows\Fonts\MesloLGSDZNerdFontPropo-Bold.ttf : No FontName. Skipping.
C:\Windows\Fonts\MesloLGSDZNerdFontPropo-BoldItalic.ttf : No FontName. Skipping.
C:\Windows\Fonts\MesloLGSDZNerdFontPropo-Italic.ttf : No FontName. Skipping.
C:\Windows\Fonts\MesloLGSDZNerdFontPropo-Regular.ttf : No FontName. Skipping.
C:\Windows\Fonts\MesloLGSNerdFont-Bold.ttf : No FontName. Skipping.
C:\Windows\Fonts\MesloLGSNerdFont-BoldItalic.ttf : No FontName. Skipping.
C:\Windows\Fonts\MesloLGSNerdFont-Italic.ttf : No FontName. Skipping.
C:\Windows\Fonts\MesloLGSNerdFont-Regular.ttf : No FontName. Skipping.
C:\Windows\Fonts\MesloLGSNerdFontMono-Bold.ttf : No FontName. Skipping.
C:\Windows\Fonts\MesloLGSNerdFontMono-BoldItalic.ttf : No FontName. Skipping.
C:\Windows\Fonts\MesloLGSNerdFontMono-Italic.ttf : No FontName. Skipping.
C:\Windows\Fonts\MesloLGSNerdFontMono-Regular.ttf : No FontName. Skipping.
C:\Windows\Fonts\MesloLGSNerdFontPropo-Bold.ttf : No FontName. Skipping.
C:\Windows\Fonts\MesloLGSNerdFontPropo-BoldItalic.ttf : No FontName. Skipping.
C:\Windows\Fonts\MesloLGSNerdFontPropo-Italic.ttf : No FontName. Skipping.
C:\Windows\Fonts\MesloLGSNerdFontPropo-Regular.ttf : No FontName. Skipping.
C:\Windows\Fonts\micross.ttf => C:/Users/Administrator/AppData/Local/R/cache/R/renv/cache/v5/windows/R-4.4/x86_64-w64-mingw32/extrafontdb/1.0/a861555ddec7451c653b40e713166c6f/extrafontdb/metrics/micross
C:\Windows\Fonts\MISTRAL.TTF => C:/Users/Administrator/AppData/Local/R/cache/R/renv/cache/v5/windows/R-4.4/x86_64-w64-mingw32/extrafontdb/1.0/a861555ddec7451c653b40e713166c6f/extrafontdb/metrics/MISTRAL
C:\Windows\Fonts\mmrtext.ttf => C:/Users/Administrator/AppData/Local/R/cache/R/renv/cache/v5/windows/R-4.4/x86_64-w64-mingw32/extrafontdb/1.0/a861555ddec7451c653b40e713166c6f/extrafontdb/metrics/mmrtext
C:\Windows\Fonts\mmrtextb.ttf => C:/Users/Administrator/AppData/Local/R/cache/R/renv/cache/v5/windows/R-4.4/x86_64-w64-mingw32/extrafontdb/1.0/a861555ddec7451c653b40e713166c6f/extrafontdb/metrics/mmrtextb
C:\Windows\Fonts\MOD20.TTF => C:/Users/Administrator/AppData/Local/R/cache/R/renv/cache/v5/windows/R-4.4/x86_64-w64-mingw32/extrafontdb/1.0/a861555ddec7451c653b40e713166c6f/extrafontdb/metrics/MOD20
C:\Windows\Fonts\monbaiti.ttf => C:/Users/Administrator/AppData/Local/R/cache/R/renv/cache/v5/windows/R-4.4/x86_64-w64-mingw32/extrafontdb/1.0/a861555ddec7451c653b40e713166c6f/extrafontdb/metrics/monbaiti
C:\Windows\Fonts\mriam.ttf => C:/Users/Administrator/AppData/Local/R/cache/R/renv/cache/v5/windows/R-4.4/x86_64-w64-mingw32/extrafontdb/1.0/a861555ddec7451c653b40e713166c6f/extrafontdb/metrics/mriam
C:\Windows\Fonts\mriamc.ttf => C:/Users/Administrator/AppData/Local/R/cache/R/renv/cache/v5/windows/R-4.4/x86_64-w64-mingw32/extrafontdb/1.0/a861555ddec7451c653b40e713166c6f/extrafontdb/metrics/mriamc
C:\Windows\Fonts\msuighub.ttf => C:/Users/Administrator/AppData/Local/R/cache/R/renv/cache/v5/windows/R-4.4/x86_64-w64-mingw32/extrafontdb/1.0/a861555ddec7451c653b40e713166c6f/extrafontdb/metrics/msuighub
C:\Windows\Fonts\msuighur.ttf => C:/Users/Administrator/AppData/Local/R/cache/R/renv/cache/v5/windows/R-4.4/x86_64-w64-mingw32/extrafontdb/1.0/a861555ddec7451c653b40e713166c6f/extrafontdb/metrics/msuighur
C:\Windows\Fonts\msyi.ttf => C:/Users/Administrator/AppData/Local/R/cache/R/renv/cache/v5/windows/R-4.4/x86_64-w64-mingw32/extrafontdb/1.0/a861555ddec7451c653b40e713166c6f/extrafontdb/metrics/msyi
C:\Windows\Fonts\MTCORSVA.TTF => C:/Users/Administrator/AppData/Local/R/cache/R/renv/cache/v5/windows/R-4.4/x86_64-w64-mingw32/extrafontdb/1.0/a861555ddec7451c653b40e713166c6f/extrafontdb/metrics/MTCORSVA
C:\Windows\Fonts\MTEXTRA.TTF => C:/Users/Administrator/AppData/Local/R/cache/R/renv/cache/v5/windows/R-4.4/x86_64-w64-mingw32/extrafontdb/1.0/a861555ddec7451c653b40e713166c6f/extrafontdb/metrics/MTEXTRA
C:\Windows\Fonts\mvboli.ttf => C:/Users/Administrator/AppData/Local/R/cache/R/renv/cache/v5/windows/R-4.4/x86_64-w64-mingw32/extrafontdb/1.0/a861555ddec7451c653b40e713166c6f/extrafontdb/metrics/mvboli
C:\Windows\Fonts\NIAGENG.TTF => C:/Users/Administrator/AppData/Local/R/cache/R/renv/cache/v5/windows/R-4.4/x86_64-w64-mingw32/extrafontdb/1.0/a861555ddec7451c653b40e713166c6f/extrafontdb/metrics/NIAGENG
C:\Windows\Fonts\NIAGSOL.TTF => C:/Users/Administrator/AppData/Local/R/cache/R/renv/cache/v5/windows/R-4.4/x86_64-w64-mingw32/extrafontdb/1.0/a861555ddec7451c653b40e713166c6f/extrafontdb/metrics/NIAGSOL
C:\Windows\Fonts\Nirmala.ttf => C:/Users/Administrator/AppData/Local/R/cache/R/renv/cache/v5/windows/R-4.4/x86_64-w64-mingw32/extrafontdb/1.0/a861555ddec7451c653b40e713166c6f/extrafontdb/metrics/Nirmala
C:\Windows\Fonts\NirmalaB.ttf => C:/Users/Administrator/AppData/Local/R/cache/R/renv/cache/v5/windows/R-4.4/x86_64-w64-mingw32/extrafontdb/1.0/a861555ddec7451c653b40e713166c6f/extrafontdb/metrics/NirmalaB
C:\Windows\Fonts\NirmalaS.ttf => C:/Users/Administrator/AppData/Local/R/cache/R/renv/cache/v5/windows/R-4.4/x86_64-w64-mingw32/extrafontdb/1.0/a861555ddec7451c653b40e713166c6f/extrafontdb/metrics/NirmalaS
C:\Windows\Fonts\nrkis.ttf => C:/Users/Administrator/AppData/Local/R/cache/R/renv/cache/v5/windows/R-4.4/x86_64-w64-mingw32/extrafontdb/1.0/a861555ddec7451c653b40e713166c6f/extrafontdb/metrics/nrkis
C:\Windows\Fonts\ntailu.ttf => C:/Users/Administrator/AppData/Local/R/cache/R/renv/cache/v5/windows/R-4.4/x86_64-w64-mingw32/extrafontdb/1.0/a861555ddec7451c653b40e713166c6f/extrafontdb/metrics/ntailu
C:\Windows\Fonts\ntailub.ttf => C:/Users/Administrator/AppData/Local/R/cache/R/renv/cache/v5/windows/R-4.4/x86_64-w64-mingw32/extrafontdb/1.0/a861555ddec7451c653b40e713166c6f/extrafontdb/metrics/ntailub
C:\Windows\Fonts\nyala.ttf => C:/Users/Administrator/AppData/Local/R/cache/R/renv/cache/v5/windows/R-4.4/x86_64-w64-mingw32/extrafontdb/1.0/a861555ddec7451c653b40e713166c6f/extrafontdb/metrics/nyala
C:\Windows\Fonts\OCRAEXT.TTF => C:/Users/Administrator/AppData/Local/R/cache/R/renv/cache/v5/windows/R-4.4/x86_64-w64-mingw32/extrafontdb/1.0/a861555ddec7451c653b40e713166c6f/extrafontdb/metrics/OCRAEXT
C:\Windows\Fonts\OLDENGL.TTF => C:/Users/Administrator/AppData/Local/R/cache/R/renv/cache/v5/windows/R-4.4/x86_64-w64-mingw32/extrafontdb/1.0/a861555ddec7451c653b40e713166c6f/extrafontdb/metrics/OLDENGL
C:\Windows\Fonts\ONYX.TTF => C:/Users/Administrator/AppData/Local/R/cache/R/renv/cache/v5/windows/R-4.4/x86_64-w64-mingw32/extrafontdb/1.0/a861555ddec7451c653b40e713166c6f/extrafontdb/metrics/ONYX
C:\Windows\Fonts\OUTLOOK.TTF => C:/Users/Administrator/AppData/Local/R/cache/R/renv/cache/v5/windows/R-4.4/x86_64-w64-mingw32/extrafontdb/1.0/a861555ddec7451c653b40e713166c6f/extrafontdb/metrics/OUTLOOK
C:\Windows\Fonts\pala.ttf => C:/Users/Administrator/AppData/Local/R/cache/R/renv/cache/v5/windows/R-4.4/x86_64-w64-mingw32/extrafontdb/1.0/a861555ddec7451c653b40e713166c6f/extrafontdb/metrics/pala
C:\Windows\Fonts\palab.ttf => C:/Users/Administrator/AppData/Local/R/cache/R/renv/cache/v5/windows/R-4.4/x86_64-w64-mingw32/extrafontdb/1.0/a861555ddec7451c653b40e713166c6f/extrafontdb/metrics/palab
C:\Windows\Fonts\palabi.ttf => C:/Users/Administrator/AppData/Local/R/cache/R/renv/cache/v5/windows/R-4.4/x86_64-w64-mingw32/extrafontdb/1.0/a861555ddec7451c653b40e713166c6f/extrafontdb/metrics/palabi
C:\Windows\Fonts\palai.ttf => C:/Users/Administrator/AppData/Local/R/cache/R/renv/cache/v5/windows/R-4.4/x86_64-w64-mingw32/extrafontdb/1.0/a861555ddec7451c653b40e713166c6f/extrafontdb/metrics/palai
C:\Windows\Fonts\PALSCRI.TTF => C:/Users/Administrator/AppData/Local/R/cache/R/renv/cache/v5/windows/R-4.4/x86_64-w64-mingw32/extrafontdb/1.0/a861555ddec7451c653b40e713166c6f/extrafontdb/metrics/PALSCRI
C:\Windows\Fonts\PAPYRUS.TTF => C:/Users/Administrator/AppData/Local/R/cache/R/renv/cache/v5/windows/R-4.4/x86_64-w64-mingw32/extrafontdb/1.0/a861555ddec7451c653b40e713166c6f/extrafontdb/metrics/PAPYRUS
C:\Windows\Fonts\PARCHM.TTF => C:/Users/Administrator/AppData/Local/R/cache/R/renv/cache/v5/windows/R-4.4/x86_64-w64-mingw32/extrafontdb/1.0/a861555ddec7451c653b40e713166c6f/extrafontdb/metrics/PARCHM
C:\Windows\Fonts\PER_____.TTF => C:/Users/Administrator/AppData/Local/R/cache/R/renv/cache/v5/windows/R-4.4/x86_64-w64-mingw32/extrafontdb/1.0/a861555ddec7451c653b40e713166c6f/extrafontdb/metrics/PER_____
C:\Windows\Fonts\PERB____.TTF => C:/Users/Administrator/AppData/Local/R/cache/R/renv/cache/v5/windows/R-4.4/x86_64-w64-mingw32/extrafontdb/1.0/a861555ddec7451c653b40e713166c6f/extrafontdb/metrics/PERB____
C:\Windows\Fonts\PERBI___.TTF => C:/Users/Administrator/AppData/Local/R/cache/R/renv/cache/v5/windows/R-4.4/x86_64-w64-mingw32/extrafontdb/1.0/a861555ddec7451c653b40e713166c6f/extrafontdb/metrics/PERBI___
C:\Windows\Fonts\PERI____.TTF => C:/Users/Administrator/AppData/Local/R/cache/R/renv/cache/v5/windows/R-4.4/x86_64-w64-mingw32/extrafontdb/1.0/a861555ddec7451c653b40e713166c6f/extrafontdb/metrics/PERI____
C:\Windows\Fonts\PERTIBD.TTF => C:/Users/Administrator/AppData/Local/R/cache/R/renv/cache/v5/windows/R-4.4/x86_64-w64-mingw32/extrafontdb/1.0/a861555ddec7451c653b40e713166c6f/extrafontdb/metrics/PERTIBD
C:\Windows\Fonts\PERTILI.TTF => C:/Users/Administrator/AppData/Local/R/cache/R/renv/cache/v5/windows/R-4.4/x86_64-w64-mingw32/extrafontdb/1.0/a861555ddec7451c653b40e713166c6f/extrafontdb/metrics/PERTILI
C:\Windows\Fonts\phagspa.ttf => C:/Users/Administrator/AppData/Local/R/cache/R/renv/cache/v5/windows/R-4.4/x86_64-w64-mingw32/extrafontdb/1.0/a861555ddec7451c653b40e713166c6f/extrafontdb/metrics/phagspa
C:\Windows\Fonts\phagspab.ttf => C:/Users/Administrator/AppData/Local/R/cache/R/renv/cache/v5/windows/R-4.4/x86_64-w64-mingw32/extrafontdb/1.0/a861555ddec7451c653b40e713166c6f/extrafontdb/metrics/phagspab
C:\Windows\Fonts\PLAYBILL.TTF => C:/Users/Administrator/AppData/Local/R/cache/R/renv/cache/v5/windows/R-4.4/x86_64-w64-mingw32/extrafontdb/1.0/a861555ddec7451c653b40e713166c6f/extrafontdb/metrics/PLAYBILL
C:\Windows\Fonts\POORICH.TTF => C:/Users/Administrator/AppData/Local/R/cache/R/renv/cache/v5/windows/R-4.4/x86_64-w64-mingw32/extrafontdb/1.0/a861555ddec7451c653b40e713166c6f/extrafontdb/metrics/POORICH
C:\Windows\Fonts\PRISTINA.TTF => C:/Users/Administrator/AppData/Local/R/cache/R/renv/cache/v5/windows/R-4.4/x86_64-w64-mingw32/extrafontdb/1.0/a861555ddec7451c653b40e713166c6f/extrafontdb/metrics/PRISTINA
C:\Windows\Fonts\RAGE.TTF => C:/Users/Administrator/AppData/Local/R/cache/R/renv/cache/v5/windows/R-4.4/x86_64-w64-mingw32/extrafontdb/1.0/a861555ddec7451c653b40e713166c6f/extrafontdb/metrics/RAGE
C:\Windows\Fonts\RAVIE.TTF => C:/Users/Administrator/AppData/Local/R/cache/R/renv/cache/v5/windows/R-4.4/x86_64-w64-mingw32/extrafontdb/1.0/a861555ddec7451c653b40e713166c6f/extrafontdb/metrics/RAVIE
C:\Windows\Fonts\REFSAN.TTF => C:/Users/Administrator/AppData/Local/R/cache/R/renv/cache/v5/windows/R-4.4/x86_64-w64-mingw32/extrafontdb/1.0/a861555ddec7451c653b40e713166c6f/extrafontdb/metrics/REFSAN
C:\Windows\Fonts\REFSPCL.TTF => C:/Users/Administrator/AppData/Local/R/cache/R/renv/cache/v5/windows/R-4.4/x86_64-w64-mingw32/extrafontdb/1.0/a861555ddec7451c653b40e713166c6f/extrafontdb/metrics/REFSPCL
C:\Windows\Fonts\ROCC____.TTF => C:/Users/Administrator/AppData/Local/R/cache/R/renv/cache/v5/windows/R-4.4/x86_64-w64-mingw32/extrafontdb/1.0/a861555ddec7451c653b40e713166c6f/extrafontdb/metrics/ROCC____
C:\Windows\Fonts\ROCCB___.TTF => C:/Users/Administrator/AppData/Local/R/cache/R/renv/cache/v5/windows/R-4.4/x86_64-w64-mingw32/extrafontdb/1.0/a861555ddec7451c653b40e713166c6f/extrafontdb/metrics/ROCCB___
C:\Windows\Fonts\ROCK.TTF => C:/Users/Administrator/AppData/Local/R/cache/R/renv/cache/v5/windows/R-4.4/x86_64-w64-mingw32/extrafontdb/1.0/a861555ddec7451c653b40e713166c6f/extrafontdb/metrics/ROCK
C:\Windows\Fonts\ROCKB.TTF => C:/Users/Administrator/AppData/Local/R/cache/R/renv/cache/v5/windows/R-4.4/x86_64-w64-mingw32/extrafontdb/1.0/a861555ddec7451c653b40e713166c6f/extrafontdb/metrics/ROCKB
C:\Windows\Fonts\ROCKBI.TTF => C:/Users/Administrator/AppData/Local/R/cache/R/renv/cache/v5/windows/R-4.4/x86_64-w64-mingw32/extrafontdb/1.0/a861555ddec7451c653b40e713166c6f/extrafontdb/metrics/ROCKBI
C:\Windows\Fonts\ROCKEB.TTF => C:/Users/Administrator/AppData/Local/R/cache/R/renv/cache/v5/windows/R-4.4/x86_64-w64-mingw32/extrafontdb/1.0/a861555ddec7451c653b40e713166c6f/extrafontdb/metrics/ROCKEB
C:\Windows\Fonts\ROCKI.TTF => C:/Users/Administrator/AppData/Local/R/cache/R/renv/cache/v5/windows/R-4.4/x86_64-w64-mingw32/extrafontdb/1.0/a861555ddec7451c653b40e713166c6f/extrafontdb/metrics/ROCKI
C:\Windows\Fonts\rod.ttf => C:/Users/Administrator/AppData/Local/R/cache/R/renv/cache/v5/windows/R-4.4/x86_64-w64-mingw32/extrafontdb/1.0/a861555ddec7451c653b40e713166c6f/extrafontdb/metrics/rod
C:\Windows\Fonts\SCHLBKB.TTF => C:/Users/Administrator/AppData/Local/R/cache/R/renv/cache/v5/windows/R-4.4/x86_64-w64-mingw32/extrafontdb/1.0/a861555ddec7451c653b40e713166c6f/extrafontdb/metrics/SCHLBKB
C:\Windows\Fonts\SCHLBKBI.TTF => C:/Users/Administrator/AppData/Local/R/cache/R/renv/cache/v5/windows/R-4.4/x86_64-w64-mingw32/extrafontdb/1.0/a861555ddec7451c653b40e713166c6f/extrafontdb/metrics/SCHLBKBI
C:\Windows\Fonts\SCHLBKI.TTF => C:/Users/Administrator/AppData/Local/R/cache/R/renv/cache/v5/windows/R-4.4/x86_64-w64-mingw32/extrafontdb/1.0/a861555ddec7451c653b40e713166c6f/extrafontdb/metrics/SCHLBKI
C:\Windows\Fonts\SCRIPTBL.TTF => C:/Users/Administrator/AppData/Local/R/cache/R/renv/cache/v5/windows/R-4.4/x86_64-w64-mingw32/extrafontdb/1.0/a861555ddec7451c653b40e713166c6f/extrafontdb/metrics/SCRIPTBL
C:\Windows\Fonts\segmdl2.ttf => C:/Users/Administrator/AppData/Local/R/cache/R/renv/cache/v5/windows/R-4.4/x86_64-w64-mingw32/extrafontdb/1.0/a861555ddec7451c653b40e713166c6f/extrafontdb/metrics/segmdl2
C:\Windows\Fonts\segoepr.ttf => C:/Users/Administrator/AppData/Local/R/cache/R/renv/cache/v5/windows/R-4.4/x86_64-w64-mingw32/extrafontdb/1.0/a861555ddec7451c653b40e713166c6f/extrafontdb/metrics/segoepr
C:\Windows\Fonts\segoeprb.ttf => C:/Users/Administrator/AppData/Local/R/cache/R/renv/cache/v5/windows/R-4.4/x86_64-w64-mingw32/extrafontdb/1.0/a861555ddec7451c653b40e713166c6f/extrafontdb/metrics/segoeprb
C:\Windows\Fonts\segoesc.ttf => C:/Users/Administrator/AppData/Local/R/cache/R/renv/cache/v5/windows/R-4.4/x86_64-w64-mingw32/extrafontdb/1.0/a861555ddec7451c653b40e713166c6f/extrafontdb/metrics/segoesc
C:\Windows\Fonts\segoescb.ttf => C:/Users/Administrator/AppData/Local/R/cache/R/renv/cache/v5/windows/R-4.4/x86_64-w64-mingw32/extrafontdb/1.0/a861555ddec7451c653b40e713166c6f/extrafontdb/metrics/segoescb
C:\Windows\Fonts\segoeui.ttf => C:/Users/Administrator/AppData/Local/R/cache/R/renv/cache/v5/windows/R-4.4/x86_64-w64-mingw32/extrafontdb/1.0/a861555ddec7451c653b40e713166c6f/extrafontdb/metrics/segoeui
C:\Windows\Fonts\segoeuib.ttf => C:/Users/Administrator/AppData/Local/R/cache/R/renv/cache/v5/windows/R-4.4/x86_64-w64-mingw32/extrafontdb/1.0/a861555ddec7451c653b40e713166c6f/extrafontdb/metrics/segoeuib
C:\Windows\Fonts\segoeuii.ttf => C:/Users/Administrator/AppData/Local/R/cache/R/renv/cache/v5/windows/R-4.4/x86_64-w64-mingw32/extrafontdb/1.0/a861555ddec7451c653b40e713166c6f/extrafontdb/metrics/segoeuii
C:\Windows\Fonts\segoeuil.ttf => C:/Users/Administrator/AppData/Local/R/cache/R/renv/cache/v5/windows/R-4.4/x86_64-w64-mingw32/extrafontdb/1.0/a861555ddec7451c653b40e713166c6f/extrafontdb/metrics/segoeuil
C:\Windows\Fonts\segoeuisl.ttf => C:/Users/Administrator/AppData/Local/R/cache/R/renv/cache/v5/windows/R-4.4/x86_64-w64-mingw32/extrafontdb/1.0/a861555ddec7451c653b40e713166c6f/extrafontdb/metrics/segoeuisl
C:\Windows\Fonts\segoeuiz.ttf => C:/Users/Administrator/AppData/Local/R/cache/R/renv/cache/v5/windows/R-4.4/x86_64-w64-mingw32/extrafontdb/1.0/a861555ddec7451c653b40e713166c6f/extrafontdb/metrics/segoeuiz
C:\Windows\Fonts\seguibl.ttf => C:/Users/Administrator/AppData/Local/R/cache/R/renv/cache/v5/windows/R-4.4/x86_64-w64-mingw32/extrafontdb/1.0/a861555ddec7451c653b40e713166c6f/extrafontdb/metrics/seguibl
C:\Windows\Fonts\seguibli.ttf => C:/Users/Administrator/AppData/Local/R/cache/R/renv/cache/v5/windows/R-4.4/x86_64-w64-mingw32/extrafontdb/1.0/a861555ddec7451c653b40e713166c6f/extrafontdb/metrics/seguibli
C:\Windows\Fonts\seguiemj.ttf => C:/Users/Administrator/AppData/Local/R/cache/R/renv/cache/v5/windows/R-4.4/x86_64-w64-mingw32/extrafontdb/1.0/a861555ddec7451c653b40e713166c6f/extrafontdb/metrics/seguiemj
C:\Windows\Fonts\seguihis.ttf => C:/Users/Administrator/AppData/Local/R/cache/R/renv/cache/v5/windows/R-4.4/x86_64-w64-mingw32/extrafontdb/1.0/a861555ddec7451c653b40e713166c6f/extrafontdb/metrics/seguihis
C:\Windows\Fonts\seguili.ttf => C:/Users/Administrator/AppData/Local/R/cache/R/renv/cache/v5/windows/R-4.4/x86_64-w64-mingw32/extrafontdb/1.0/a861555ddec7451c653b40e713166c6f/extrafontdb/metrics/seguili
C:\Windows\Fonts\seguisb.ttf => C:/Users/Administrator/AppData/Local/R/cache/R/renv/cache/v5/windows/R-4.4/x86_64-w64-mingw32/extrafontdb/1.0/a861555ddec7451c653b40e713166c6f/extrafontdb/metrics/seguisb
C:\Windows\Fonts\seguisbi.ttf => C:/Users/Administrator/AppData/Local/R/cache/R/renv/cache/v5/windows/R-4.4/x86_64-w64-mingw32/extrafontdb/1.0/a861555ddec7451c653b40e713166c6f/extrafontdb/metrics/seguisbi
C:\Windows\Fonts\seguisli.ttf => C:/Users/Administrator/AppData/Local/R/cache/R/renv/cache/v5/windows/R-4.4/x86_64-w64-mingw32/extrafontdb/1.0/a861555ddec7451c653b40e713166c6f/extrafontdb/metrics/seguisli
C:\Windows\Fonts\seguisym.ttf => C:/Users/Administrator/AppData/Local/R/cache/R/renv/cache/v5/windows/R-4.4/x86_64-w64-mingw32/extrafontdb/1.0/a861555ddec7451c653b40e713166c6f/extrafontdb/metrics/seguisym
C:\Windows\Fonts\SHOWG.TTF => C:/Users/Administrator/AppData/Local/R/cache/R/renv/cache/v5/windows/R-4.4/x86_64-w64-mingw32/extrafontdb/1.0/a861555ddec7451c653b40e713166c6f/extrafontdb/metrics/SHOWG
C:\Windows\Fonts\simpbdo.ttf => C:/Users/Administrator/AppData/Local/R/cache/R/renv/cache/v5/windows/R-4.4/x86_64-w64-mingw32/extrafontdb/1.0/a861555ddec7451c653b40e713166c6f/extrafontdb/metrics/simpbdo
C:\Windows\Fonts\simpfxo.ttf => C:/Users/Administrator/AppData/Local/R/cache/R/renv/cache/v5/windows/R-4.4/x86_64-w64-mingw32/extrafontdb/1.0/a861555ddec7451c653b40e713166c6f/extrafontdb/metrics/simpfxo
C:\Windows\Fonts\simpo.ttf => C:/Users/Administrator/AppData/Local/R/cache/R/renv/cache/v5/windows/R-4.4/x86_64-w64-mingw32/extrafontdb/1.0/a861555ddec7451c653b40e713166c6f/extrafontdb/metrics/simpo
C:\Windows\Fonts\simsunb.ttf => C:/Users/Administrator/AppData/Local/R/cache/R/renv/cache/v5/windows/R-4.4/x86_64-w64-mingw32/extrafontdb/1.0/a861555ddec7451c653b40e713166c6f/extrafontdb/metrics/simsunb
C:\Windows\Fonts\SitkaVF-Italic.ttf => C:/Users/Administrator/AppData/Local/R/cache/R/renv/cache/v5/windows/R-4.4/x86_64-w64-mingw32/extrafontdb/1.0/a861555ddec7451c653b40e713166c6f/extrafontdb/metrics/SitkaVF-Italic
C:\Windows\Fonts\SitkaVF.ttf => C:/Users/Administrator/AppData/Local/R/cache/R/renv/cache/v5/windows/R-4.4/x86_64-w64-mingw32/extrafontdb/1.0/a861555ddec7451c653b40e713166c6f/extrafontdb/metrics/SitkaVF
C:\Windows\Fonts\SNAP____.TTF => C:/Users/Administrator/AppData/Local/R/cache/R/renv/cache/v5/windows/R-4.4/x86_64-w64-mingw32/extrafontdb/1.0/a861555ddec7451c653b40e713166c6f/extrafontdb/metrics/SNAP____
C:\Windows\Fonts\STENCIL.TTF => C:/Users/Administrator/AppData/Local/R/cache/R/renv/cache/v5/windows/R-4.4/x86_64-w64-mingw32/extrafontdb/1.0/a861555ddec7451c653b40e713166c6f/extrafontdb/metrics/STENCIL
C:\Windows\Fonts\sylfaen.ttf => C:/Users/Administrator/AppData/Local/R/cache/R/renv/cache/v5/windows/R-4.4/x86_64-w64-mingw32/extrafontdb/1.0/a861555ddec7451c653b40e713166c6f/extrafontdb/metrics/sylfaen
C:\Windows\Fonts\symbol.ttf => C:/Users/Administrator/AppData/Local/R/cache/R/renv/cache/v5/windows/R-4.4/x86_64-w64-mingw32/extrafontdb/1.0/a861555ddec7451c653b40e713166c6f/extrafontdb/metrics/symbol
C:\Windows\Fonts\tahoma.ttf => C:/Users/Administrator/AppData/Local/R/cache/R/renv/cache/v5/windows/R-4.4/x86_64-w64-mingw32/extrafontdb/1.0/a861555ddec7451c653b40e713166c6f/extrafontdb/metrics/tahoma
C:\Windows\Fonts\tahomabd.ttf => C:/Users/Administrator/AppData/Local/R/cache/R/renv/cache/v5/windows/R-4.4/x86_64-w64-mingw32/extrafontdb/1.0/a861555ddec7451c653b40e713166c6f/extrafontdb/metrics/tahomabd
C:\Windows\Fonts\taile.ttf => C:/Users/Administrator/AppData/Local/R/cache/R/renv/cache/v5/windows/R-4.4/x86_64-w64-mingw32/extrafontdb/1.0/a861555ddec7451c653b40e713166c6f/extrafontdb/metrics/taile
C:\Windows\Fonts\taileb.ttf => C:/Users/Administrator/AppData/Local/R/cache/R/renv/cache/v5/windows/R-4.4/x86_64-w64-mingw32/extrafontdb/1.0/a861555ddec7451c653b40e713166c6f/extrafontdb/metrics/taileb
C:\Windows\Fonts\TCB_____.TTF => C:/Users/Administrator/AppData/Local/R/cache/R/renv/cache/v5/windows/R-4.4/x86_64-w64-mingw32/extrafontdb/1.0/a861555ddec7451c653b40e713166c6f/extrafontdb/metrics/TCB_____
C:\Windows\Fonts\TCBI____.TTF => C:/Users/Administrator/AppData/Local/R/cache/R/renv/cache/v5/windows/R-4.4/x86_64-w64-mingw32/extrafontdb/1.0/a861555ddec7451c653b40e713166c6f/extrafontdb/metrics/TCBI____
C:\Windows\Fonts\TCCB____.TTF => C:/Users/Administrator/AppData/Local/R/cache/R/renv/cache/v5/windows/R-4.4/x86_64-w64-mingw32/extrafontdb/1.0/a861555ddec7451c653b40e713166c6f/extrafontdb/metrics/TCCB____
C:\Windows\Fonts\TCCEB.TTF => C:/Users/Administrator/AppData/Local/R/cache/R/renv/cache/v5/windows/R-4.4/x86_64-w64-mingw32/extrafontdb/1.0/a861555ddec7451c653b40e713166c6f/extrafontdb/metrics/TCCEB
C:\Windows\Fonts\TCCM____.TTF => C:/Users/Administrator/AppData/Local/R/cache/R/renv/cache/v5/windows/R-4.4/x86_64-w64-mingw32/extrafontdb/1.0/a861555ddec7451c653b40e713166c6f/extrafontdb/metrics/TCCM____
C:\Windows\Fonts\TCM_____.TTF => C:/Users/Administrator/AppData/Local/R/cache/R/renv/cache/v5/windows/R-4.4/x86_64-w64-mingw32/extrafontdb/1.0/a861555ddec7451c653b40e713166c6f/extrafontdb/metrics/TCM_____
C:\Windows\Fonts\TCMI____.TTF => C:/Users/Administrator/AppData/Local/R/cache/R/renv/cache/v5/windows/R-4.4/x86_64-w64-mingw32/extrafontdb/1.0/a861555ddec7451c653b40e713166c6f/extrafontdb/metrics/TCMI____
C:\Windows\Fonts\TEMPSITC.TTF => C:/Users/Administrator/AppData/Local/R/cache/R/renv/cache/v5/windows/R-4.4/x86_64-w64-mingw32/extrafontdb/1.0/a861555ddec7451c653b40e713166c6f/extrafontdb/metrics/TEMPSITC
C:\Windows\Fonts\times.ttf => C:/Users/Administrator/AppData/Local/R/cache/R/renv/cache/v5/windows/R-4.4/x86_64-w64-mingw32/extrafontdb/1.0/a861555ddec7451c653b40e713166c6f/extrafontdb/metrics/times
C:\Windows\Fonts\timesbd.ttf => C:/Users/Administrator/AppData/Local/R/cache/R/renv/cache/v5/windows/R-4.4/x86_64-w64-mingw32/extrafontdb/1.0/a861555ddec7451c653b40e713166c6f/extrafontdb/metrics/timesbd
C:\Windows\Fonts\timesbi.ttf => C:/Users/Administrator/AppData/Local/R/cache/R/renv/cache/v5/windows/R-4.4/x86_64-w64-mingw32/extrafontdb/1.0/a861555ddec7451c653b40e713166c6f/extrafontdb/metrics/timesbi
C:\Windows\Fonts\timesi.ttf => C:/Users/Administrator/AppData/Local/R/cache/R/renv/cache/v5/windows/R-4.4/x86_64-w64-mingw32/extrafontdb/1.0/a861555ddec7451c653b40e713166c6f/extrafontdb/metrics/timesi
C:\Windows\Fonts\tradbdo.ttf => C:/Users/Administrator/AppData/Local/R/cache/R/renv/cache/v5/windows/R-4.4/x86_64-w64-mingw32/extrafontdb/1.0/a861555ddec7451c653b40e713166c6f/extrafontdb/metrics/tradbdo
C:\Windows\Fonts\trado.ttf => C:/Users/Administrator/AppData/Local/R/cache/R/renv/cache/v5/windows/R-4.4/x86_64-w64-mingw32/extrafontdb/1.0/a861555ddec7451c653b40e713166c6f/extrafontdb/metrics/trado
C:\Windows\Fonts\trebuc.ttf => C:/Users/Administrator/AppData/Local/R/cache/R/renv/cache/v5/windows/R-4.4/x86_64-w64-mingw32/extrafontdb/1.0/a861555ddec7451c653b40e713166c6f/extrafontdb/metrics/trebuc
C:\Windows\Fonts\trebucbd.ttf => C:/Users/Administrator/AppData/Local/R/cache/R/renv/cache/v5/windows/R-4.4/x86_64-w64-mingw32/extrafontdb/1.0/a861555ddec7451c653b40e713166c6f/extrafontdb/metrics/trebucbd
C:\Windows\Fonts\trebucbi.ttf => C:/Users/Administrator/AppData/Local/R/cache/R/renv/cache/v5/windows/R-4.4/x86_64-w64-mingw32/extrafontdb/1.0/a861555ddec7451c653b40e713166c6f/extrafontdb/metrics/trebucbi
C:\Windows\Fonts\trebucit.ttf => C:/Users/Administrator/AppData/Local/R/cache/R/renv/cache/v5/windows/R-4.4/x86_64-w64-mingw32/extrafontdb/1.0/a861555ddec7451c653b40e713166c6f/extrafontdb/metrics/trebucit
C:\Windows\Fonts\UbuntuMono-R.ttf => C:/Users/Administrator/AppData/Local/R/cache/R/renv/cache/v5/windows/R-4.4/x86_64-w64-mingw32/extrafontdb/1.0/a861555ddec7451c653b40e713166c6f/extrafontdb/metrics/UbuntuMono-R
C:\Windows\Fonts\UrdType.ttf => C:/Users/Administrator/AppData/Local/R/cache/R/renv/cache/v5/windows/R-4.4/x86_64-w64-mingw32/extrafontdb/1.0/a861555ddec7451c653b40e713166c6f/extrafontdb/metrics/UrdType
C:\Windows\Fonts\UrdTypeb.ttf => C:/Users/Administrator/AppData/Local/R/cache/R/renv/cache/v5/windows/R-4.4/x86_64-w64-mingw32/extrafontdb/1.0/a861555ddec7451c653b40e713166c6f/extrafontdb/metrics/UrdTypeb
C:\Windows\Fonts\verdana.ttf => C:/Users/Administrator/AppData/Local/R/cache/R/renv/cache/v5/windows/R-4.4/x86_64-w64-mingw32/extrafontdb/1.0/a861555ddec7451c653b40e713166c6f/extrafontdb/metrics/verdana
C:\Windows\Fonts\verdanab.ttf => C:/Users/Administrator/AppData/Local/R/cache/R/renv/cache/v5/windows/R-4.4/x86_64-w64-mingw32/extrafontdb/1.0/a861555ddec7451c653b40e713166c6f/extrafontdb/metrics/verdanab
C:\Windows\Fonts\verdanai.ttf => C:/Users/Administrator/AppData/Local/R/cache/R/renv/cache/v5/windows/R-4.4/x86_64-w64-mingw32/extrafontdb/1.0/a861555ddec7451c653b40e713166c6f/extrafontdb/metrics/verdanai
C:\Windows\Fonts\verdanaz.ttf => C:/Users/Administrator/AppData/Local/R/cache/R/renv/cache/v5/windows/R-4.4/x86_64-w64-mingw32/extrafontdb/1.0/a861555ddec7451c653b40e713166c6f/extrafontdb/metrics/verdanaz
C:\Windows\Fonts\VINERITC.TTF => C:/Users/Administrator/AppData/Local/R/cache/R/renv/cache/v5/windows/R-4.4/x86_64-w64-mingw32/extrafontdb/1.0/a861555ddec7451c653b40e713166c6f/extrafontdb/metrics/VINERITC
C:\Windows\Fonts\VIVALDII.TTF => C:/Users/Administrator/AppData/Local/R/cache/R/renv/cache/v5/windows/R-4.4/x86_64-w64-mingw32/extrafontdb/1.0/a861555ddec7451c653b40e713166c6f/extrafontdb/metrics/VIVALDII
C:\Windows\Fonts\VLADIMIR.TTF => C:/Users/Administrator/AppData/Local/R/cache/R/renv/cache/v5/windows/R-4.4/x86_64-w64-mingw32/extrafontdb/1.0/a861555ddec7451c653b40e713166c6f/extrafontdb/metrics/VLADIMIR
C:\Windows\Fonts\webdings.ttf => C:/Users/Administrator/AppData/Local/R/cache/R/renv/cache/v5/windows/R-4.4/x86_64-w64-mingw32/extrafontdb/1.0/a861555ddec7451c653b40e713166c6f/extrafontdb/metrics/webdings
C:\Windows\Fonts\wingding.ttf => C:/Users/Administrator/AppData/Local/R/cache/R/renv/cache/v5/windows/R-4.4/x86_64-w64-mingw32/extrafontdb/1.0/a861555ddec7451c653b40e713166c6f/extrafontdb/metrics/wingding
C:\Windows\Fonts\WINGDNG2.TTF => C:/Users/Administrator/AppData/Local/R/cache/R/renv/cache/v5/windows/R-4.4/x86_64-w64-mingw32/extrafontdb/1.0/a861555ddec7451c653b40e713166c6f/extrafontdb/metrics/WINGDNG2
C:\Windows\Fonts\WINGDNG3.TTF => C:/Users/Administrator/AppData/Local/R/cache/R/renv/cache/v5/windows/R-4.4/x86_64-w64-mingw32/extrafontdb/1.0/a861555ddec7451c653b40e713166c6f/extrafontdb/metrics/WINGDNG3
Found FontName for 351 fonts.
Scanning afm files in C:/Users/Administrator/AppData/Local/R/cache/R/renv/cache/v5/windows/R-4.4/x86_64-w64-mingw32/extrafontdb/1.0/a861555ddec7451c653b40e713166c6f/extrafontdb/metrics
Writing font table in C:/Users/Administrator/AppData/Local/R/cache/R/renv/cache/v5/windows/R-4.4/x86_64-w64-mingw32/extrafontdb/1.0/a861555ddec7451c653b40e713166c6f/extrafontdb/fontmap/fonttable.csv
Writing Fontmap to C:/Users/Administrator/AppData/Local/R/cache/R/renv/cache/v5/windows/R-4.4/x86_64-w64-mingw32/extrafontdb/1.0/a861555ddec7451c653b40e713166c6f/extrafontdb/fontmap/Fontmap...

***********************************************************************************************************************
Registration
***********************************************************************************************************************
# Register Fonts For Device (Windows in my case)

> loadfonts(device = "win")
Registering font with R using windowsFonts(): Agency FB
Registering font with R using windowsFonts(): Aharoni
Registering font with R using windowsFonts(): Aldhabi
Registering font with R using windowsFonts(): Algerian
Registering font with R using windowsFonts(): Andalus
Registering font with R using windowsFonts(): Arial Black
Registering font with R using windowsFonts(): Arial
Registering font with R using windowsFonts(): Arial Narrow
Registering font with R using windowsFonts(): Arial Rounded MT Bold
Registering font with R using windowsFonts(): Bahnschrift
Registering font with R using windowsFonts(): Baskerville Old Face
Registering font with R using windowsFonts(): Bauhaus 93
Registering font with R using windowsFonts(): Bell MT
Registering font with R using windowsFonts(): Berlin Sans FB
Registering font with R using windowsFonts(): Berlin Sans FB Demi
Registering font with R using windowsFonts(): Bernard MT Condensed
Registering font with R using windowsFonts(): Blackadder ITC
Registering font with R using windowsFonts(): Bodoni MT
Registering font with R using windowsFonts(): Bodoni MT Black
Registering font with R using windowsFonts(): Bodoni MT Condensed
Registering font with R using windowsFonts(): Bodoni MT Poster Compressed
Registering font with R using windowsFonts(): Book Antiqua
Registering font with R using windowsFonts(): Bookman Old Style
Registering font with R using windowsFonts(): Bookshelf Symbol 7
Registering font with R using windowsFonts(): Bradley Hand ITC
Registering font with R using windowsFonts(): Britannic Bold
Registering font with R using windowsFonts(): Broadway
Registering font with R using windowsFonts(): Brush Script MT
Registering font with R using windowsFonts(): Calibri
Registering font with R using windowsFonts(): Calibri Light
Registering font with R using windowsFonts(): Californian FB
Registering font with R using windowsFonts(): Calisto MT
Registering font with R using windowsFonts(): Cambria
Registering font with R using windowsFonts(): Candara
Registering font with R using windowsFonts(): Candara Light
Registering font with R using windowsFonts(): Cascadia Code
Registering font with R using windowsFonts(): Cascadia Mono
Registering font with R using windowsFonts(): Castellar
Registering font with R using windowsFonts(): Centaur
Registering font with R using windowsFonts(): Century
Registering font with R using windowsFonts(): Century Gothic
Registering font with R using windowsFonts(): Century Schoolbook
Registering font with R using windowsFonts(): Chiller
Registering font with R using windowsFonts(): Colonna MT
Registering font with R using windowsFonts(): Comic Sans MS
Registering font with R using windowsFonts(): Consolas
Registering font with R using windowsFonts(): Constantia
Registering font with R using windowsFonts(): Cooper Black
Registering font with R using windowsFonts(): Copperplate Gothic Bold
Registering font with R using windowsFonts(): Copperplate Gothic Light
Registering font with R using windowsFonts(): Corbel
Registering font with R using windowsFonts(): Corbel Light
Registering font with R using windowsFonts(): Courier New
Registering font with R using windowsFonts(): Curlz MT
Registering font with R using windowsFonts(): David
Registering font with R using windowsFonts(): Dubai
Registering font with R using windowsFonts(): Dubai Light
Registering font with R using windowsFonts(): Dubai Medium
Registering font with R using windowsFonts(): Ebrima
Registering font with R using windowsFonts(): Edwardian Script ITC
Registering font with R using windowsFonts(): Elephant
Registering font with R using windowsFonts(): Engravers MT
Registering font with R using windowsFonts(): Eras Bold ITC
Registering font with R using windowsFonts(): Eras Demi ITC
Registering font with R using windowsFonts(): Eras Light ITC
Registering font with R using windowsFonts(): Eras Medium ITC
Registering font with R using windowsFonts(): Felix Titling
Registering font with R using windowsFonts(): Footlight MT Light
Registering font with R using windowsFonts(): Forte
Registering font with R using windowsFonts(): Franklin Gothic Book
Registering font with R using windowsFonts(): Franklin Gothic Demi
Registering font with R using windowsFonts(): Franklin Gothic Demi Cond
Registering font with R using windowsFonts(): Franklin Gothic Heavy
Registering font with R using windowsFonts(): Franklin Gothic Medium
Registering font with R using windowsFonts(): Franklin Gothic Medium Cond
Registering font with R using windowsFonts(): FrankRuehl
Registering font with R using windowsFonts(): Freestyle Script
Registering font with R using windowsFonts(): French Script MT
Registering font with R using windowsFonts(): Gabriola
Registering font with R using windowsFonts(): Gadugi
Registering font with R using windowsFonts(): Garamond
Registering font with R using windowsFonts(): Georgia
Registering font with R using windowsFonts(): Gigi
Registering font with R using windowsFonts(): Gill Sans Ultra Bold
Registering font with R using windowsFonts(): Gill Sans Ultra Bold Condensed
Registering font with R using windowsFonts(): Gill Sans MT
Registering font with R using windowsFonts(): Gill Sans MT Condensed
Registering font with R using windowsFonts(): Gill Sans MT Ext Condensed Bold
Registering font with R using windowsFonts(): Gisha
Registering font with R using windowsFonts(): Gloucester MT Extra Condensed
Registering font with R using windowsFonts(): Goudy Old Style
Registering font with R using windowsFonts(): Goudy Stout
Registering font with R using windowsFonts(): Haettenschweiler
Registering font with R using windowsFonts(): Harlow Solid Italic
Registering font with R using windowsFonts(): Harrington
Registering font with R using windowsFonts(): High Tower Text
Registering font with R using windowsFonts(): Impact
Registering font with R using windowsFonts(): Imprint MT Shadow
Registering font with R using windowsFonts(): Informal Roman
Registering font with R using windowsFonts(): Ink Free
Registering font with R using windowsFonts(): Javanese Text
Registering font with R using windowsFonts(): Jokerman
Registering font with R using windowsFonts(): Juice ITC
Registering font with R using windowsFonts(): Kristen ITC
Registering font with R using windowsFonts(): Kunstler Script
Registering font with R using windowsFonts(): Wide Latin
Registering font with R using windowsFonts(): Leelawadee
Registering font with R using windowsFonts(): Leelawadee UI
Registering font with R using windowsFonts(): Leelawadee UI Semilight
Registering font with R using windowsFonts(): Levenim MT
Registering font with R using windowsFonts(): Lucida Bright
Registering font with R using windowsFonts(): Lucida Calligraphy
Registering font with R using windowsFonts(): Lucida Console
Registering font with R using windowsFonts(): Lucida Fax
Registering font with R using windowsFonts(): Lucida Handwriting
Registering font with R using windowsFonts(): Lucida Sans
Registering font with R using windowsFonts(): Lucida Sans Typewriter
Registering font with R using windowsFonts(): Lucida Sans Unicode
Registering font with R using windowsFonts(): Magneto
Registering font with R using windowsFonts(): Maiandra GD
Registering font with R using windowsFonts(): Malgun Gothic
Registering font with R using windowsFonts(): Malgun Gothic Semilight
Registering font with R using windowsFonts(): Marlett
Registering font with R using windowsFonts(): Matura MT Script Capitals
Registering font with R using windowsFonts(): Microsoft Himalaya
Registering font with R using windowsFonts(): Microsoft Yi Baiti
Registering font with R using windowsFonts(): Microsoft New Tai Lue
Registering font with R using windowsFonts(): Microsoft PhagsPa
Registering font with R using windowsFonts(): Microsoft Sans Serif
Registering font with R using windowsFonts(): Microsoft Tai Le
Registering font with R using windowsFonts(): Microsoft Uighur
Registering font with R using windowsFonts(): Miriam
Registering font with R using windowsFonts(): Miriam Fixed
Registering font with R using windowsFonts(): Mistral
Registering font with R using windowsFonts(): Modern No. 20
Registering font with R using windowsFonts(): Mongolian Baiti
Registering font with R using windowsFonts(): Monotype Corsiva
Registering font with R using windowsFonts(): MS Outlook
Registering font with R using windowsFonts(): MS Reference Sans Serif
Registering font with R using windowsFonts(): MS Reference Specialty
Registering font with R using windowsFonts(): MT Extra
Registering font with R using windowsFonts(): MV Boli
Registering font with R using windowsFonts(): Myanmar Text
Registering font with R using windowsFonts(): Narkisim
Registering font with R using windowsFonts(): Niagara Engraved
Registering font with R using windowsFonts(): Niagara Solid
Registering font with R using windowsFonts(): Nirmala UI
Registering font with R using windowsFonts(): Nirmala UI Semilight
Registering font with R using windowsFonts(): Nyala
Registering font with R using windowsFonts(): OCR A Extended
Registering font with R using windowsFonts(): Old English Text MT
Registering font with R using windowsFonts(): Onyx
Registering font with R using windowsFonts(): Palace Script MT
Registering font with R using windowsFonts(): Palatino Linotype
Registering font with R using windowsFonts(): Papyrus
Registering font with R using windowsFonts(): Parchment
Registering font with R using windowsFonts(): Perpetua
Registering font with R using windowsFonts(): Perpetua Titling MT
Registering font with R using windowsFonts(): Playbill
Registering font with R using windowsFonts(): Poor Richard
Registering font with R using windowsFonts(): Pristina
Registering font with R using windowsFonts(): Rage Italic
Registering font with R using windowsFonts(): Ravie
Registering font with R using windowsFonts(): Rockwell
Registering font with R using windowsFonts(): Rockwell Condensed
Registering font with R using windowsFonts(): Rockwell Extra Bold
Registering font with R using windowsFonts(): Rod
Registering font with R using windowsFonts(): Sakkal Majalla
Registering font with R using windowsFonts(): Script MT Bold
Registering font with R using windowsFonts(): Segoe MDL2 Assets
Registering font with R using windowsFonts(): Segoe Print
Registering font with R using windowsFonts(): Segoe Script
Registering font with R using windowsFonts(): Segoe UI
Registering font with R using windowsFonts(): Segoe UI Light
Registering font with R using windowsFonts(): Segoe UI Semibold
Registering font with R using windowsFonts(): Segoe UI Semilight
Registering font with R using windowsFonts(): Segoe UI Black
Registering font with R using windowsFonts(): Segoe UI Emoji
Registering font with R using windowsFonts(): Segoe UI Historic
Registering font with R using windowsFonts(): Segoe UI Symbol
Registering font with R using windowsFonts(): Showcard Gothic
Registering font with R using windowsFonts(): Simplified Arabic
Registering font with R using windowsFonts(): Simplified Arabic Fixed
Registering font with R using windowsFonts(): SimSun-ExtB
Registering font with R using windowsFonts(): Sitka Text
Registering font with R using windowsFonts(): Snap ITC
Registering font with R using windowsFonts(): Stencil
Registering font with R using windowsFonts(): Sylfaen
Registering font with R using windowsFonts(): Symbol
Registering font with R using windowsFonts(): Tahoma
Registering font with R using windowsFonts(): Tempus Sans ITC
Registering font with R using windowsFonts(): Times New Roman
Registering font with R using windowsFonts(): Traditional Arabic
Registering font with R using windowsFonts(): Trebuchet MS
Registering font with R using windowsFonts(): Tw Cen MT
Registering font with R using windowsFonts(): Tw Cen MT Condensed
Registering font with R using windowsFonts(): Tw Cen MT Condensed Extra Bold
Registering font with R using windowsFonts(): Ubuntu Mono
Registering font with R using windowsFonts(): Urdu Typesetting
Registering font with R using windowsFonts(): Verdana
Registering font with R using windowsFonts(): Viner Hand ITC
Registering font with R using windowsFonts(): Vivaldi
Registering font with R using windowsFonts(): Vladimir Script
Registering font with R using windowsFonts(): Webdings
Registering font with R using windowsFonts(): Wingdings
Registering font with R using windowsFonts(): Wingdings 2
Registering font with R using windowsFonts(): Wingdings 3

***********************************************************************************************************************
Now you will be able to specify the fonts on the corresponding argument of the graphical function you are going to use with the name appearing on the fonts() list that corresponds to the font you want to set.
***********************************************************************************************************************



# Specify the font family with the name displayed on the fonts() output
plot(trees$Volume,
     main = "Custom fonts in base R",
     xlab = "",
     ylab = "Volume",
     pch = 21, col = 4, bg = 4,
     family = "Algerian") # We are setting the "Algerian" font
Add Windows fonts with extrafont package in R


The same will apply for a ggplot2 chart:

# install.packages("ggplot2")
library(ggplot2)

ggplot(trees, aes(1:length(Volume), Volume)) +
      ggtitle("Custom fonts in ggplot2") +
      geom_point(col = 4) + 
      xlab("") +
      theme(text = element_text(family = "Algerian")) # Custom font
Use custom fonts in R ggplot2

# For charts that don't have an explicit option you have to work with the layouts
# Save the current graphical parameters
op <- par(no.readonly = TRUE)

# Set the font globally
par(family = "Algerian") # Specify the name of the font

# Create the histogram
hist(trees$Height,
     main = "All Fonts",
     ylab = "Frequency",
     xlab = "",
     col = 4)

# Restore the graphical parameters
on.exit(par(op))
# dev.off()

********** bonus   ********************
# Adding a Google Font
Google Fonts can be added with the font_add_google function of the package. For instance, if you want to add the Pacifico font you can type:

Load Pacifico font from Google Fonts
# install.packages("showtext")
library(showtext)

# You will need to have internet connection
# If you restart R you will need to execute this code again to use the font
font_add_google(name = "Pacifico",   # Name of the font on the Google Fonts site
                family = "pacifico") # Name you want to use to call the font





