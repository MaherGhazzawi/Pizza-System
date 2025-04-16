# Pizza Delivery System

Dies ist ein einfaches Pizza-Bestellsystem, das in Python geschrieben wurde. Es ermöglicht den Benutzer, eine Pizza in drei Größen (S, M, L) auszuwählen und zusätzliche Optionen wie **Peperoni** und **extra Käse** hinzuzufügen. Das System berechnet den Gesamtpreis basierend auf der gewählten Größe und den Extras.

## Funktionen

- Auswahl der Pizza-Größe: S, M oder L
- Hinzufügen von Extras: Peperoni und extra Käse
- Berechnung des Gesamtpreises basierend auf der Auswahl der Größe und Extras

## Installation

Choice = input("Hallo hier ist delevery Pizza System, wir haben S,M,L \n")
pepperonie = input("Hallo willst du peppetonie ja oder nein\n")
extra_cheese = input("Hallo willst du Kässe ja oder nein\n")
bill = 0
if Choice == "S" or Choice == "s":
    bill += 5
elif Choice == "m" or Choice == "M":
    bill += 10
elif Choice == "l" or Choice == "L":
    bill += 15
else:
    print("Es git einen flaschen Wert.")

if pepperonie =="ja":
    if Choice == "S" or Choice == "s":
        bill += 1.99
    else:
        bill += 2.99

if extra_cheese =="ja":
    if Choice == "S" or Choice == "s":
        bill += 1.99
    else:
        bill += 2.99
print(f"Deine Rechnung {bill:.2f} €")


