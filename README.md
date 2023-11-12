def gruen():
    print("farb_nr = 1")
    print("farbe = GRÜN")
    print("angriff = 1000")
    print("verteidigung = 300")
    print("name = Ogeron der Zerströrer")
    print("herkunftsland = Ödland von Blorch")


def rot():
    print("farb_nr = 2")
    print("farbe = ROT")
    print("angriff = 700")
    print("verteidigung = 500")
    print("name = Agrina die Drachenreiterin")
    print("herkunftsland = Ebenen von Sarbia")


def weiss():
    print("farb_nr = 3")
    print("farbe = WEISS")
    print("angriff = 55")
    print("verteidigung = 300")
    print("name = Gerald der Schöne")
    print("herkunftsland = Hochland von Agadirien")


kartenziffer = input("Welche Kartenziffer: ")
neue_Karten = input("Anzahl neuer Karten? ansonsten x: ")

if kartenziffer == "1":
    gruen()
    anzahl1 = 3
    if neue_Karten != "x":
        anzahl1 += int(neue_Karten)
    print("Anzahl der Karten = ", anzahl1)

elif kartenziffer == "2":
    rot()
    anzahl2 = 7
    if neue_Karten != "x":
        anzahl2 += int(neue_Karten)
    print("Anzahl der Karten = ", anzahl2)

elif kartenziffer == "3":
    weiss()
    anzahl3 = 2
    if neue_Karten != "x":
        anzahl3 += int(neue_Karten)
    print("Anzahl der Karten = ", anzahl3)
