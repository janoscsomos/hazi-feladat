# BINX DevOps házi feladat

Kedves Jelentkező!
Üdvözöllek a Binx DevOps csapat felvételi folyamatának a technikai körén. Arra szeretnénk megkérni, hogy az alábbi feladatokat  legjobb tudásod szerint kitöltsd. Ha bármi kérdésed/problémád adódna a kitöltés során, keress minket nyugodtan. Sok sikert!

## Pipeline CI
A webapp könyvtár egy egyszerű NodeJS alkalmazást tartalmaz, amihez egy githubos pipelinet kéne elkészítened az alábbi követelmények alapján:
 1. A pipeline buildeljen egy docker imaget a webes applikációból a megadott Dockerfile alapján.
 2. Ezt az imaget töltse fel egy általad választott image repositoryba.
 3. Bónusz: Köss be a pipelineba egy általad preferált container security scannert.

## Pipeline CD
A pipeline folytatásaként szeretnénk a lebuildelt webes applikációt kitelepíteni egy általad preferált cloudos környezetbe az alábbi megkötések szerint:
 1. Minden cloudos erőforrást, amire ehhez szükséged van, Terraform segítségével hozzon létre a pipeline.
 2. Bónusz: Köss be a pipelineba egy általad preferált IaC security scannert.

## Helm
Keszíts egy helm chartot a webes applikációnak. Ez a pipelinetól független feladat, így bőven elég ha a chartokat minikubeon teszteled, nem szükséges emiatt egy cloudos k8s clustert kitelepítened.

## Terragrunt hibakereső
A terragrunt könyvtárban egy terragruntos deployment kódja található, ahol elrejtettünk egy pár hibát. A feladatod megtalálni és kijavítani a hibákat.
Bőven elég a ``` terragrunt plan ``` parancsnak sikeresen lefutnia, nem szükséges kitelepítened a modult.

