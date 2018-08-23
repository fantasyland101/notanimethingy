ideer: 2d wiev av skolan ,länk till ssis.nu och canvas, länk till andras i skolans hämsidor
WEBBSIDOIDÉER: Vi kan göra ett schema för varje dag för varje klass (A till D) men att, när vi klickar på ämnet, så står det hela namnet på läraren. När man klickar på lärarens namn så skickas man till sidan med information om varje lärare. När man klickar på ett ämne så står det även vilket klassrum man ska till, och när man klickar på klassrummets namn så kommer man till en bild med en "bird's eye view" av skola, i ett 2D-format.
Vi kan även lägga till en länk till ssis.nu och canvas, men även en lista på länkar till andra elevers webbsidor.

<!DOCTYPE Html>
<html lang="sv">
Det är starten.

Man börjar varje del av en webbsida med <[något]> och sedan avslutar med </[något]>.
Ex: <head>
	<meta charset="utf-8" />
	<title> det du vill säga </title>
</head>

<title> är det som visas på fliken, inte på sidan.
<body> är det som visas på själva sidan.
<h1> gör att en text blir relativt stor, som en rubrik.
<h2> gör en text lite mindre än med h1 men ändå relativt stor. Passar som en underrubrik.
<p> betyder "paragraf" och det kan man lägga mellan en text man vill skriva.
<body bgcolor="yellow"> gör att bakgrunden till hemsidan är gul. Man kan skriva ungefär vilken färg man vill.
<font face="tahoma"> gör att textfonten är "Tahoma".
<img src="mysmiley.png"> söker upp en bild i din dator. I detta fall söker den upp en bild som har namnet "mysmiley.png".
<a href="[en länk]"> gör att man kan lägga in en länk i sin webbsida. Man behöver skriva en text precis efter bracket:en när man har skrivit in URL:en

FONTS:
Comic sans MS
Times New Roman
Arial
Tahoma
Kan skriva <font size="[en siffra från 1 till 7]"> och sedan det man vill skriva för att ändra font storleken.

Kan skriva <br /> vid slutet av en <font size>-text för att byta rad.

Om man skriver <center> framför <p> så kan man göra att texten sätts i mitten av sidan. Man kan även skriva <left> och <right>.

Man kan byta font från en font till en annan genom att skriva <font face="[det man vill ha]"> men sedan så måste man även ha med </font>

<strong> gör en text fetskriven (t.ex <p> This statement is <strong>bold</strong>.</p>).

<acronym> gör att du kan sätta en förklaring för något ord eller någon förkortning, t.ex om du skriver Html så kan man sväva musen över den och så står det "Hypertext markup language". 
(Ex. <p>The <acronym title="Internal Revenue Service">IRS</acronym> collects tax revenue.</p>.

<meta name="description" content="[Vad som ska skrivas under länken till webbsidan när man söker på den]">
<meta name="keywords" content="[Vilka nyckelord som måste sökas på för att webbsidan ska visas på söksidan]">

Anledningen till att man skriver <meta charset="utf-8"> under <head> är för att "charset" betyder "character set", och ska säga vilket set av karaktärer som man använder (ASCII hade 128 karaktärer, ANSI hade 256 karaktärer. UTF-8 är namnet på ett karaktär-set, och är det set som man använder med HTML5.).

För att lägga till GIFs så använder du dig av <IMG SRC="exempel.gif"> i <body>. IMG står för image oc SRC står för source. Taggen letar efter GIFen med det specifikaa namnet i mappen www och om den hittar den så visas GIFen på sidan.
