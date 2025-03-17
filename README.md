# README  

**Markdown** to prosty język znaczników do formatowania tekstu. Używany w dokumentacji, blogach i README.  

### **Podstawy składni**  

#### **Nagłówki**  
Użyj `#`:  
```markdown
# Nagłówek 1  
## Nagłówek 2  
### Nagłówek 3  
```

#### **Tekst**  
- **Pogrubienie**: `**tekst**` -> **tekst**  
- *Kursywa*: `*tekst*` -> *tekst*  
- ***Pogrubiona kursywa***: `***tekst***`  -> ***tekst***

#### **Listy**  
- **Nienumerowana**:  
  ```markdown
  - Element 1  
  - Element 2  
  - Element 3
  ```
- **Numerowana**:  
  ```markdown
  1. Pierwszy  
  2. Drugi  
  ```

#### **Linki i obrazy**  
- `[Tekst](https://adres.com)` -> [Tekst](https://adres.com)  
- `![Opis](https://adres.com/obraz.png)` 


#### **Kod w MD** 
```javascript
// Funkcja dodająca dwie liczby
function dodaj(a, b) {
  return a + b;
}

// Wywołanie funkcji
let wynik = dodaj(3, 4);
console.log(wynik);  // Wynik: 7
```

### Wyjaśnienie:
- W pliku Markdown używamy potrójnych apostrofów (```) do zapisania bloków kodu.
- Możemy określić język (np. `javascript`), co pozwala na odpowiednie podświetlanie składni w edytorach.

W ten sposób cały plik zawiera zarówno dokumentację, jak i przykład kodu w JavaScript.

#### **Tabele**  
```markdown
| Kolumna 1 | Kolumna 2 | Kolumna 3 |
|-----------|-----------|-----------| 
| Wartość 1 | Wartość 2 | Wartość 3 |
```

#### **Linia pozioma**  
`--------------------`  

