---
title: Code
order: 40
icon: lucide/braces
---

## Code "en ligne"

Le **code en ligne** (*inline code*) est délimité par un simple *backtick*, caractère : \`

=== "📄 Code"

	```md
	Sous Linux, tapez `ls -la` pour lister le contenu d'un dossier,  
	y compris les fichiers cachés.
	```

=== "➡️ Résultat"

	Sous Linux, tapez `ls -la` pour lister le contenu d'un dossier,  
	y compris les fichiers cachés.

## Listing de code

Les listings de code source sont créés à l'aide de *code fences*, c'est-à-dire par un blocs délimités par des *triple backticks*.

```js title="Javascript"
function hello() {
	console.log("Hello World!");
}
```

```csharp title="C#"
void hello(string who) {
	Console.WriteLine("Hello " + who);
}
```