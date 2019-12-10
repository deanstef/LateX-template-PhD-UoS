# LateX-template-PhD-UoS
PhD thesis and reports LateX template - ECS University of Southampton

Last Update 02/09/2019

(To be compiled with XeLateX or LuaTeX)

Nomenclature with nomencl package --> \nom{ABR.}{Explanation}
nomenclature must be complied with Nomenclature engine.

Structure:

--> templates - contains the classes needed for a UoS PhD thesis/report

 - ecsprogress.cls --> Template class for 9-month report
 - ecsminithesis.cls --> Template class for 18-month report
 - ecsthesis.cls --> Template class for final PhD thesis


--> tex - folder with a plain document for thesis. Just copy and paste the .cls needed and start writing.

Copy the template required in tex folder and compile from the main/Progress.tex 


In the *Progress.tex* document:   

The `\authorshipdeclaration{}` takes no argument. It only produces a declaration page if you are using the `ecsthesis` class.   

The abbreviations list has been substituted by the `nomencl` package. To define abbreviations in your text use:   

            \nom{ABRV.}{Explanation}   
          
For example, `\nom{ID}{Identification}` will produce an entry:    

            Abbreviations   
            --------------
            
              ID            Identification    
