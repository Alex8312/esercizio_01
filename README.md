# esercizio_001

spesa = {
  "banane": {"quantita": 7, "prezzo_unitario": 1.98},
  "farina": {"quantita": 1, "prezzo_unitario": 1.5},
  "nutella": {"quantita": 2, "prezzo_unitario": 5.69}
}

for k in spesa.items():
    print(k, "\n")
   
print("Spesa totale quantitativo:", spesa['banane']['quantita'] + spesa['farina']['quantita'] + spesa['nutella']['quantita'], "€")

print("Prezzo totale della spesa:", spesa['banane']['prezzo_unitario'] + spesa['farina']['prezzo_unitario'] + spesa['nutella']['prezzo_unitario'], "€")
