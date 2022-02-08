# Toolbox Extension Template


## English description
[Link zur deutschen Beschreibung](#deutsche-beschreibung)

- Create a new git repository and copy all the stuff from this template to it.
- Run `npm install` first time
- Run `npm test` to run all the tests
- To add a new tool just edit ``extension.js``.
  There is an example tool called ``niceFunction``. The tools are written in JavaScript.


![](https://chioro.ams3.digitaloceanspaces.com/images_toolbox/function_overview.png)

1. Here is the function itself. JavaScript is fully available, tools from the base package can be used with a prefix ``base.``. In this example ``upperCaseText`` and ``lowerCaseText`` from the base package are used.
   With ``return`` the calculated value is returned.
2. Following is the information for chioro to manage the function:

   ``id`` and ``impl`` are the name of the function and must match the name in javascript

   ``aliases`` are the names of the function in the respective language. These names are displayed in the toolbox.

3. ``args`` are the input variables in the respective language.

4. ``tags`` any tags can be added. Tags are optional.
5. ``tests`` any number of tests can be added. With ``npm test`` the validity of the function is checked.





## Deutsche Beschreibung

- Erstellen Sie ein neues Repository in GitLab und kopieren Sie alles aus dieser Vorlage dorthin.
- Führen Sie `npm install` einmalig aus um die Abhängigkeiten zu laden (Basic-Paket)
- Führen Sie `npm test` aus, um alle Tests zu starten. Damit kann, nach jeder Ergänzung der Toolbox, die Validität überprüft werden.
- Um ein neues Werkzeug hinzuzufügen, editieren Sie einfach ``extension.js``.
  Es gibt ein Beispielwerkzeug namens ``niceFunction``. Die Werkzeuge sind in JavaScript geschrieben.


![](https://chioro.ams3.digitaloceanspaces.com/images_toolbox/function_overview.png)

1. Hier steht die Funktion selber. JavaScript steht in vollem Umfang zur Verfügung, Werkzeuge aus dem Basis-Paket können mit einem vorangestellten ``base.`` verwendet werden. In diesem Beispiel werden ``upperCaseText``und ``lowerCaseText`` aus dem Basis-Paket verwendet.
   Mit return wird der berechnete Wert zurückgegeben.
2. Es folgen die Informationen für chioro um die Funktion zu verwalten:

   ``id`` und ``impl`` enthalten den Namen der Funktion und müssen dem Namen in Javascript entsprechen

   ``aliases`` sind die Namen der Funktion in der jeweiligen Sprache. Diese Namen werden in der Toolbox angezeigt.

3. ``args`` sind die Eingabe-Variablen in der jeweiligen Sprache

4. ``tags`` beliebige Tags können hinzugefügt werden. Tags sind optional.
5. ``tests`` Es können beliebig viele Tests hinzugefügt werden. Mit ``npm test`` wird die Gültigkeit der Funktion überprüft.
