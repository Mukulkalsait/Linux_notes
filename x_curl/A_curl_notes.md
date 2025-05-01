<!--G: By Default its a get request: -->

curl <options/Arrtibutes> <url>

<!--Y: ============================================================== -->

OPTIONS/{Arrtibutes}:

# -L = follow route/redirecting

# -o = save op in file

# -O = create file with same name as on server and save.

# -i = include heaader {server cache etc.}

# -v = host/ ipv4 ipv6/ TLSv / certification/ server / + WEBPAGE

# -I = SERVER BACKEND {NO BODY} {if location shown its redirected + 302 or somthing redirecting protocol will be shown.} (but curl didnt went ther just tell info.)

<!-- Y: WEATHER API -->

|----------------------------------
|
| curl https://wttr.in/nagpur
| curl https://wttr.in/<cityName>
|
|----------------------------------

<!--|G: USAGE: ---------------------------------------------------------------------------------------------------------------------->
<!--|                                                                                                                              -->
<!--| curl https://example.com/[1..20].html                          ==> will give all 1.html to 20.html                           -->
<!--| curl https://example.com/[1..20:3].html                        ==> will give all 1.html to 20.html in steps of 3             -->
<!--| curl https://example.com/[1..20].html -o save_#1.html          ==> will save them in the respective files.                   -->
<!--| curl https://example.com/{abc,mno,xyz}.html -o save_#1.html    ==> will save them in the respective files.                   -->
<!--|                                                                                                                              -->
<!--|-------------------------------------------------------------------------------------------------------------------------------->
