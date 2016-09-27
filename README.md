# Jak vaříme šťavnaté weby v manGowebu

Quick Start Guide WIP

- Oblíbený editor https://www.sublimetext.com
- IDE https://www.jetbrains.com/phpstorm/
- Prohlížeč dokumentace http://devdocs.io
- Používané frontend technologie [Stylus](http://stylus-lang.com), [Jade](http://naltatis.github.io/jade-syntax-docs), [mango-cli](http://mangocli.org), [Browsersync](https://www.browsersync.io), ...

## Nastavení vývojového prostředí

1. instalace Git klienta (verzovací systém) https://git-scm.com/downloads
2. instalace Node.js (JavaScript běhové prostředí) https://nodejs.org/en/download/current/
3. instalace build tools (závislosti na Windows) https://github.com/felixrieseberg/windows-build-tools
4. instalace mango-cli nástroje https://github.com/manGoweb/mango-cli

Pokud všechny kroky proběhnou s úspěchem, bude v příkazové řádce dostupný nový příkaz `mango`. Přes něj dále funguje naše dev workflow...

## Vývojové workflow

Nastartování práce na novém projektu

1. `mango init nazevprojektu` - založení nového projektu do adresáře, využívá se kostra https://github.com/manGoweb/mango-cli-example
2. `cd nazevprojektu`
3. `mango dev` - spuštění vývojového režimu, který sám kompiluje CSS, HTML, JS po změně souboru a zároveň spouští vývojový server na localhostu
4. pro skončení vývojového režimu slouží klávesová zkratka CTRL+C

## Projektové workflow

### Nastavení git a GitHub účtu

Předávání zdrojových kódů probíhá přes verzovací systém [git](https://git-scm.com), který hostujeme na firemním [GitHub účtu](https://github.com/manGoweb).

1. [Zaregistruj si účet](https://github.com/join) na GitHubu, pokud ještě nemáš
2. Nastav si git klienta https://help.github.com/articles/set-up-git/
3. Vygeneruj SSH klíč https://help.github.com/articles/generating-a-new-ssh-key-and-adding-it-to-the-ssh-agent/
4. Přidej klíč do tvého GitHub účtu https://help.github.com/articles/adding-a-new-ssh-key-to-your-github-account/ 

Další odkazy

- Pěkný [interaktivní tutoriál přímo od GitHubu](https://try.github.io/levels/1/challenges/1)
- Oficiální [Getting started](https://git-scm.com/book/en/v2/Getting-Started-Git-Basics)

### Práce s repositářem

Nejčastější git operace, které používáme

- `git pull --rebase` - stažení a začlenění nových změn ze serveru. Nesmí být žádné lokální změny a občas se mohou objevit konflikty. Pokud se něco takového stane **DON'T PANIC** a vyhledej zkušenějšího kolegu.
- `git add -all` - označení všech změn v pracovním adresáři pro commit
- `git commit -m "strucny popis zmeny, ktere se commit tyka"` - vytvoření commitu z připravených změn
- `git push origin` - poslání commitnutých změn na server

### GUI klienti pro git

- Git Extensions (Windows) https://gitextensions.github.io/
- GitX-dev (MacOS) http://rowanj.github.io/gitx/
- GitHub Desktop (Win, Mac) https://desktop.github.com/

## Organizace kódu

*wip*

## Frontend

*wip*

## Backend

*wip*

## Deploy a hosting

*wip*
