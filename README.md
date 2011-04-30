# Delicious Cake

_The Enrichment Center is committed to the well being of all participants. 
Cake and grief counseling will be available at the conclusion of the test. 
Thank you for helping us help you help us all._

                  .,-:;//;:=,               
              . :H@@@MM@M#H/.,+%;,          
           ,/X+ +M@@M@MM%=,-%HMMM@X/,       
         -+@MM; $M@@MH+-,;XMMMM@MMMM@+-     
        ;@M@@M- XM@X;. -+XXXXXHHH@M@M#@/.   
      ,%MM@@MH ,@%=            .---=-=:=,.  
      =@#@@@MX .,              -%HX$$%%%+;  
     =-./@M@M$                  .;@MMMM@MM: 
     X@/ -$MM/                    .+MM@@@M$ 
    ,@M@H: :@:                    . =X#@@@@-
    ,@@@MMX, .                    /H- ;@M@M=
    .H@@@@M@+,                    %MM+..%#$.
     /MMMM@MMH/.                  XM@MH; =; 
      /%+%$XHH@$=              , .H@@@@MX,  
       .=--------.           -%H.,@@@@@MX,  
       .%MM@@@HHHXX$$$%+- .:$MMX =M@@MM%.   
         =XMMM@MM@MM#H;,-+HMM@M+ /MMMX=     
           =%@M@M#@$-.=$@MM@@@M; %M%=       
             ,:+$+-,/H#MMMMMMM@= =,         
                   =++%%%%+/:-.             

# Usage

Download Delicious Cake and ensure it is somewhere on your Python path 
or within your Django project. Then add `delicious_cake` to your installed
apps. It doesn't use any models so no need to run `syncdb` or anything.

To output on your page load the tag `{% load delicious_cake %}` and then 
call it somewhere in your template `{% delicious_cake %}` it will automatically 
be wrapped in HTML comments, `<!-- -->`
