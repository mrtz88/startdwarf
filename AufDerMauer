
output = ""
zeichen = 5
wanze_str = "Wanze"
tanzen_str = "tanzen"


def tanzen(zeichen):
    if zeichen == 5:
        return "tanzen"
    else: 
        return f"{tanzen_str[:zeichen]}"

while zeichen > -1:
    output += f"Auf der Mauer auf der Lauer\n"
    output += f"Sitzt 'ne kleine {wanze_str[:zeichen]}\n"
    output += f"Auf der Mauer auf der Lauer\n"
    output += f"Sitzt 'ne kleine {wanze_str[:zeichen]}\n"
    output += f"Seht euch mal die {wanze_str[:zeichen]} an\n"
    output += f"Wie die {wanze_str[:zeichen]} {tanzen(zeichen)} kann\n"
    output += f"Auf der Mauer auf der Lauer\n"
    output += f"Sitzt 'ne kleine {wanze_str[:zeichen]}\n"
    if zeichen == -1:
        break
    zeichen = zeichen - 1
  


f = open("AufDerMauer.txt", "w")
f.write(output)
