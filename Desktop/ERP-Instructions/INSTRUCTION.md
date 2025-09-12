# 🏭 PRODUKCJA – URUCHOMIENIE ZLECEŃ PRODUKCYJNYCH

---

## 1️⃣ Przejście do menu zleceń produkcyjnych
Menu: **Production → Production orders → Executive orders**

### Screenshot
![New order](images/new_order.png)
---

## 2️⃣ Tworzenie nowego zlecenia

1. 🖱️ Kliknij **New object**, aby dodać nowe zlecenie.  

### Screenshot
![New object](images/new_object.png)

2. W oknie **Executive order [new from model]** uzupełnij pola: **series, item, quantity, start/end date**.

### Screenshot
![Executive_order](images/executive_order.png)

| Pole | Co wpisać | Uwagi |
|------|-----------|-------|
| **Series** | OP – Ordini produzione | Zlecenie produkcyjne |
| **Item** | numer detalu | np. 12345 |
| **Quantity** | ilość sztuk | np. 100 |
| **Start date** | planowany start | np. 08/09/2025 |
| **End date** | planowany koniec | np. 12/09/2025 |

3. 🖱️ Kliknij **Confirm**, aby zatwierdzić.

---

## 3️⃣ Wydruk karty zlecenia

1. Po zatwierdzeniu nowego zlecenia pojawia się okno z modelem produkcyjnym wybranego detalu.  

### Screenshot
![New object](images/processing_bill1.png)

2. Dwukrotnie kliknij na aktywność po lewej stronie (np. strefa kontroli + pakowanie).  

3. 🖱️ Kliknij **Print processing bill** w górnym menu okna.  

4. W oknie **Processing bill printing [new]**:  
   - Zaznacz elementy do wydruku  
   - Przenieś je strzałką z lewej strony (**Titleleft**) na prawą  
   - Ustaw:  
     - **Processing bill status → Both**  
     - **Labels status → Both**  

### Screenshot
![New object](images/processing_bill2.png)

5. 🖱️ Kliknij **Print preview**, aby sprawdzić wydruk.  

### Screenshot
![New object](images/processing_bill3.png)

6. Wybierz dodatkowe opcje wydruku i rodzaj drukarki.  

### Screenshot
![New object](images/print_processing_bill.png)

7. 🖱️ Kliknij **Ok**, aby zatwierdzić wydruk.  

### Screenshoty
![Processing bill example](images/example_processing_bill.png)  


---

## 4️⃣ Zapis zlecenia produkcyjnego

- 🖱️ Kliknij **Save and close**, aby zapisać zlecenie.

![Save executive order](images/save_executive_order.png)  


- Zlecenie pojawi się w tabeli **Executive orders**  

### Screenshot
![Save executive order](images/table_executive_order.png)  

---

## 5️⃣ Statusy zleceń (Completion status)

| Status | Znaczenie |
|--------|-----------|
| **Confirmed** | Zlecenie prawidłowo wypełnione / zatwierdzone |
| **In progress** | Zlecenie rozpoczęte |
| **Completed** | Zlecenie zakończone |

---
