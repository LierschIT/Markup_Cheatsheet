# Plugin Mermaid
[toc]

## Flowchart
```mermaid
graph TD
		A-->B
		A-->C
		B-->D
		C-->D
```

	```mermaid
	graph TD
	    A-->B
	    A-->C
	    B-->D
	    C-->D
	```

## Squenzdiagramm
````mermaid
sequenceDiagram
participant Ulf
participant Jesus
Ulf->>Alf: Hallo Alf, hören Sie uns?
loop Sprache
	Alf->>Alf: Lernt Sprache beim Hören.
end
note right of Alf: Kommt von Mars, mit Wurzeln von der Venus
Alf-->>Ulf: Jaaaa.
Alf->>Jesus: Du bist nicht unser Messiahs!
Jesus-->>Alf: Für diesen Schwefel wirst du sterben.
````

	````mermaid
	sequenceDiagram
	participant Ulf
	participant Jesus
	Ulf->>Alf: Hallo Alf, hören Sie uns?
	loop Sprache
		Alf->>Alf: Lernt Sprache beim Hören.
	end
	note right of Alf: Kommt von Mars, mit Wurzeln von der Venus
	Alf-->>Ulf: Jaaaa.
	Alf->>Jesus: Du bist nicht unser Messiahs!
	Jesus-->>Alf: Für diesen Schwefel wirst du sterben.
	````

## Gantt Diagram
````mermaid
gantt
dateFormat YYYY-MM-DD
title GANTT Diagramm hinzufügen
excludes weekdays 2022-02-08,2022-02-15

section A
Completed task	:done,	des1, 2022-02-04,2022-02-05
active task	:active, des2, 2022-02-07, 6d
future task :	des3, after des2, 4d
future task2 : des4, after des3, 10d
````

	````mermaid
	gantt
	dateFormat YYYY-MM-DD
	title GANTT Diagramm hinzufügen
	excludes weekdays 2022-02-08,2022-02-15

	section A
	Completed task	:done,	des1, 2022-02-04,2022-02-05
	active task	:active, des2, 2022-02-07, 6d
	future task :	des3, after des2, 4d
	future task2 : des4, after des3, 10d
	````
	
## Klassendiagramm
````mermaid
classDiagram
Class01 <|-- AveryLongClass : Cool
Class03 *-- Class4
Class05 o-- Class06
Class07 .. Class08
Class09 --> C2 : Wo bin ich?
Class09 --* C3
Class09 --|> Class07
Class07 : equals()
Class07 : Object[] elementData
Class01 : size()
Class01 : int chimp
Class01 : int gorilla
Class08 <--> C2 : Cool label
````

	````mermaid
	classDiagram
	Class01 <|-- AveryLongClass : Cool
	Class03 *-- Class4
	Class05 o-- Class06
	Class07 .. Class08
	Class09 --> C2 : Wo bin ich?
	Class09 --* C3
	Class09 --|> Class07
	Class07 : equals()
	Class07 : Object[] elementData
	Class01 : size()
	Class01 : int chimp
	Class01 : int gorilla
	Class08 <--> C2 : Cool label
	````

## User Journey Diagram
````mermaid
journey
	title Mein Arbeitstag
	section Zur Arbeit
		Wasser trinken: 5: Me
		Arbeitsfahrt: 3: Me, Olga
		Arbeit: 1: Me, Others
	section Nach Hause
		Arbeitsfahrt: 3: Me
		Schlafen: 5: Me
````

	````mermaid
	journey
		title Mein Arbeitstag
		section Zur Arbeit
			Wasser trinken: 5: Me
			Arbeitsfahrt: 3: Me, Olga
			Arbeit: 1: Me, Others
		section Nach Hause
			Arbeitsfahrt: 3: Me
			Schlafen: 5: Me
	````
