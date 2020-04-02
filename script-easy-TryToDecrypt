def diccionario(argument):
    switcher = {
        "2A": "a",
        "2D": "b",
        "12": "c",
        "11": "d",
        "10": "e",
        "0F": "f",
        "0E": "g",
        "0D": "h",
        "0C": "i",
        "0B": "j",
        "0A": "k",
        "09": "l",
        "08": "m",
        "07": "n",
        "06": "o",
        "05": "p",
        "04": "q",
        "03": "r",
        "02": "s",
        "01": "t",
        "00": "u",
        "FF": "v",
        "FE": "w",
        "FD": "x",
        "FC": "y",
        "FB": "z",
        "DE": " ",
        "14": "A",
        "13": "B",
        "12": "C",
        "11": "D",
        "10": "E",
        "0F": "F",
        "0E": "G",
        "0D": "H",
        "0C": "I",
        "0B": "J",
        "0A": "K",
        "09": "L",
        "08": "M",
        "07": "N",
        "06": "O",
        "05": "P",
        "04": "Q",
        "03": "R",
        "02": "S",
        "01": "T",
        "00": "U",
        "FF": "V",
        "FE": "W",
        "FD": "X",
        "FC": "Y",
        "FB": "Z",
        "02": "-",
        "01": "_",
        "00": ".",
        "FF": ",",
        "FE": ";",
        "FD": ":",
        "FC": "?",
        "FB": "!"
    }
    return switcher.get(argument, "No esta")
#- _ . , ; : ? !
encrypt = "0C02D8010D0C02D8010606D8101402FCD80F0603D8FC0600DA"
letraEncrypt = encrypt[2:4]
a = 0
b = 2
c = len(encrypt)
d = c/2
text = ""

for y in range(int(d)):
  ff= encrypt[a:b]
  a = a+2
  b = b+2
  text = text + diccionario(ff)
  print (diccionario(ff))
print (text)
