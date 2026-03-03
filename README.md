# Test-case-
# TEST CASE – https://www.kapitalbank.az/
# Suite 1: Kart sifariş etmək
## Case 1: “Birbank Star” kartının sifariş etmək
**Title:** İstifadəçinin online şəkildə “Birbank Star” kart sifariş edə bilməsi  
**Description:** İstifadəçi düzgün məlumatlar daxil edərək “Birbank Star” kartını online sifariş edir.  
**Severity:** Major  
**Priority:** High  
**Type:** Functional  
**Is Flaky:** No  
**Behavior:** Positive  
**Automation Status:** Manual  
**Pre-conditions:** İstifadəçi sayta login edib  
### Test Steps:
1. https://www.kapitalbank.az/ saytına daxil ol  
2. Kart sifariş et bölməsinə klik et  
3. “Birbank Star” kartını sifariş et bölməsinə klik et  
4. Nömrə daxil et  
5. FİN daxil et  
6. Nömrəyə gələn kodu daxil et  
7. Təsdiq et butonuna klik et  
### Test Data:
- Nömrə: 055-555-55-55  
- FİN: 5t4fdy1  
- Kod: 4321  
**Expected Result:** Birbank Star kartı sifariş edildi  
**Status:** Pass

  
# Suite 1: Kart sifariş etmək
## Case 2: “Birbank Cashback” kartının sifariş etmək
**Title:** İstifadəçinin online şəkildə “Birbank Star” kart sifariş edə bilməsi  
**Description:** İstifadəçi düzgün məlumatlar daxil edərək “Birbank Star” kartını online sifariş edir.  
**Severity:** Major  
**Priority:** High  
**Type:** Functional  
**Is Flaky:** No  
**Behavior:** Positive  
**Automation Status:** Manual  
**Pre-conditions:** İstifadəçi sayta login edib  
### Test Steps:
1. https://www.kapitalbank.az/ saytına daxil ol  
2. Kart sifariş et bölməsinə klik et  
3. “Birbank Star” kartını sifariş et bölməsinə klik et  
4. Nömrə daxil et  
5. FİN daxil et  
6. Nömrəyə gələn kodu daxil et  
7. Təsdiq et butonuna klik et  
### Test Data:
- Nömrə: 055-555-55-55  
- FİN: 5t4fdy1  
- Kod: 4321  
**Expected Result:** Birbank Cashback kartı sifariş edildi  
**Status:** Pass

# Suite 1: Kart sifariş etmək
## Case 3: “Birbank Miles” kartının sifariş etmək
**Title:** İstifadəçinin online şəkildə “Birbank Star” kart sifariş edə bilməsi  
**Description:** İstifadəçi düzgün məlumatlar daxil edərək “Birbank Star” kartını online sifariş edir.  
**Severity:** Major  
**Priority:** High  
**Type:** Functional  
**Is Flaky:** No  
**Behavior:** Positive  
**Automation Status:** Manual  
**Pre-conditions:** İstifadəçi sayta login edib  
### Test Steps:
1. https://www.kapitalbank.az/ saytına daxil ol  
2. Kart sifariş et bölməsinə klik et  
3. “Birbank Star” kartını sifariş et bölməsinə klik et  
4. Nömrə daxil et  
5. FİN daxil et  
6. Nömrəyə gələn kodu daxil et  
7. Təsdiq et butonuna klik et  
### Test Data:
- Nömrə: 055-555-55-55  
- FİN: 5t4fdy1  
- Kod: 4321  
**Expected Result:** Birbank Miles kartı sifariş edildi  
**Status:** Pass  

# Suite 1: Kart sifariş etmək
## Case 4: “Birbank Star” kartının sifariş edə bilməmək (Yanlış nömrə)
**Title:** İstifadəçinin online şəkildə “Birbank Star” kart sifariş edə bilməməsi  
**Description:** İstifadəçi yanlış məlumatlar daxil edərək “Birbank Star” kartını online sifariş edə bilmir.  
**Severity:** Major  
**Priority:** High  
**Type:** Functional  
**Is Flaky:** No  
**Behavior:** Negative  
**Automation Status:** Manual  
**Pre-conditions:** İstifadəçi sayta login edib  
### Test Steps:
1. https://www.kapitalbank.az/ saytına daxil ol  
2. Kart sifariş et bölməsinə klik et  
3. “Birbank Star” kartını sifariş et bölməsinə klik et  
4. Nömrə daxil et  
5. "Number is incorrect" erroru görünür 
### Test Data:
- Nömrə: 065-555-55-55    
**Expected Result:** "Number is incorrect" erroru ekranda görünməlidir 
**Status:** Pass  

# Suite 1: Kart sifariş etmək
## Case 5: “Birbank Star” kartının sifariş edə bilməmək (Yanlış FİN)
**Title:** İstifadəçinin online şəkildə “Birbank Star” kart sifariş edə bilməməsi  
**Description:** İstifadəçi yanlış məlumatlar daxil edərək “Birbank Star” kartını online sifariş edə bilmir.  
**Severity:** Major  
**Priority:** High  
**Type:** Functional  
**Is Flaky:** No  
**Behavior:** Negative  
**Automation Status:** Manual  
**Pre-conditions:** İstifadəçi sayta login edib  
### Test Steps:
1. https://www.kapitalbank.az/ saytına daxil ol  
2. Kart sifariş et bölməsinə klik et  
3. “Birbank Star” kartını sifariş et bölməsinə klik et  
4. Nömrə daxil et  
5. FİN kodu daxil et
6. "FİN number is incorrect" erroru görünür 
### Test Data:
- Nömrə: 055-555-55-55
- FİN kod: 665433    
**Expected Result:** "FİN number is incorrect" erroru ekranda görünməlidir 
**Status:** Pass

# Suite 2: Nağd kredit pul götürmək
## Case 1: Nağd kredit pul götürmək 
**Title:** İstifadəçinin online şəkildə Kapital Bankdan nağd kredit pul götürə bilməsi  
**Description:** İstifadəçi doğru məlumatlar daxil edərək Kapital Bankdan nağd kredit pul götürə bilir
**Severity:** Major  
**Priority:** High  
**Type:** Functional  
**Is Flaky:** No  
**Behavior:** Positive 
**Automation Status:** Manual  
**Pre-conditions:** İstifadəçi sayta login edib
### Test Steps:
1.	https://www.kapitalbank.az/ saytına daxil ol
2.	Kredit sifariş et böloməsinə click et
3.	“Nömrə daxil et” bölməsinə nömrəni yaz
4.	“FİN daxil et” bölməsinə fini yaz
5.	Nömrəyə gələn kodu açılan xanaya yaz
6.	“Təsdiq et” butonuna click et
7.	Kredit məbləğini daxil et
8.	Kredit müddətini daxil et
9.	Sifariş et butonuna click et
10.Kredit götürülməsi başa çatdı
### Test Data:
- Nömrə: 055-555-55-55  
- FİN: 5t4fdy1  
- Kod: 4321  
- Məbləğ: 1000  
- Müddət: 12 ay
**Expected Result:** Nağd kredit prosesi yerinə yetirildi  
**Status:** Pass  

# Suite 2: Nağd kredit pul götürmək
## Case 2: Nağd kredit pul götürə bilməmək
**Title:** İstifadəçinin online şəkildə Kapital Bankdan nağd kredit pul götürə bilməməsi  
**Description:** İstifadəçi yanlış məlumatlar daxil edərək Kapital Bankdan nağd kredit pul götürə bilmir
**Severity:** Major  
**Priority:** High  
**Type:** Functional  
**Is Flaky:** No  
**Behavior:** Negative 
**Automation Status:** Manual  
**Pre-conditions:** İstifadəçi sayta login edib
### Test Steps:
1.	https://www.kapitalbank.az/ saytına daxil ol
2.	Kredit sifariş et böloməsinə click et
3.	“Nömrə daxil et” bölməsinə nömrəni yaz
4.	“FİN daxil et” bölməsinə fini yaz
5.	Nömrəyə gələn kodu açılan xanaya yaz
6.	“Təsdiq et” butonuna click et
7.	Kredit məbləğini daxil et
8.	Kredit müddətini daxil et
9.	Sifariş et butonuna click et
10.Kredit götürülməsi yerinə yetirilmədi ekranda görünür
### Test Data:
- Nömrə: 055-555-55-55  
- FİN: 5t4fdy1  
- Kod: 4321  
- Məbləğ: 2000  
- Müddət: 12 ay
**Expected Result:** Nağd kredit prosesi yerinə yetirilmir
**Status:** Pass

# Suite 3: Pul köçürmək
## Case 1: Birbankdan başqa karta pul köçürmək 
**Title :** İstifadəçinin online şəkildə Birbankdan başqa karta pul köçürə bilməsi
**Description :** İstifadəçi Birbankdan online olaraq başqa karta pul köçürə bilir
**Severity :** Major
**Priority :** High 
**Type :** Functional 
**İs flaky :** No
**Behavior :** Positive
**Automation status :** Manual
**Pre-conditions :** İsitfadəçi https://www.kapitalbank.az/ saytina login edib
### Test steps :
1.	https://www.kapitalbank.az/ saytına daxil ol
2.	Pul köçürmələri böloməsinə click et
3.	Birbank ilə pul köçürün bölməsinə daxil ol
4.	İstənilən karta pul köçür bölməsinə click et
5.	Kartını seç
6.	Card number yerinə number ı qeyd et
7.	Amount bölməsinə məbləği yaz
8.	Continue butonuna click et
9.	Confirm butonuna click et
   10.Pul köçürülməsi başa çatdı
### Test data :
   6. card number : 4169738809097878
   7. amount : 20.00
**Expected result :** Birbank vasitəsilə başqa karta pul köçürmə prosesi yerinə yetirildi.
**Status :**  Pass

# Suite 3: Pul köçürmək
## Case 2: Pul köçürə bilməmək
**Title :** İstifadəçinin online şəkildə Birbankdan başqa karta pul köçürə bilməməsi
**Description :** İstifadəçi Birbankdan online olaraq başqa karta pul köçürə bilmir
**Severity :** Major
**Priority :** High 
**Type :** Functional 
**İs flaky :** No
**Behavior :** Negative
**Automation status :** Manual
**Pre-conditions :** İsitfadəçi https://www.kapitalbank.az/ saytina login edib
### Test steps :
1.	https://www.kapitalbank.az/ saytına daxil ol
2.	Pul köçürmələri böloməsinə click et
3.	Birbank ilə pul köçürün bölməsinə daxil ol
4.	İstənilən karta pul köçür bölməsinə click et
5.	Kartını seç
6.	Card number yerinə number ı qeyd et
7.	Amount bölməsinə məbləği yaz
8.	Continue butonuna click et
9.	“Should be less than or equal value” erroru görünür
### Test data :
   6. card number : 4169738809097878
   7. amount : 40.00
**Expected Result:** “Should be less than or equal value” erroru ekranda görünür  
**Status:** Pass  

# Suite 3: Pul köçürmək
## Case 3: Pul köçürə bilməmək
**Title :** İstifadəçinin online şəkildə Birbankdan başqa karta pul köçürə bilməməsi
**Description :** İstifadəçi Birbankdan online olaraq başqa karta pul köçürə bilmir
**Severity :** Major
**Priority :** High 
**Type :** Functional 
**İs flaky :** No
**Behavior :** Negative
**Automation status :** Manual
**Pre-conditions :** İsitfadəçi https://www.kapitalbank.az/ saytina login edib
### Test steps :
1.	https://www.kapitalbank.az/ saytına daxil ol
2.	Pul köçürmələri böloməsinə click et
3.	Birbank ilə pul köçürün bölməsinə daxil ol
4.	İstənilən karta pul köçür bölməsinə click et
5.	Kartını seç
6.	Card number yerinə number ı qeyd et
7.  “Card number is incorrect” erroru gəldi
### Test data :
   6. card number : 4058738809097878
**Expected Result:** “Card number is incorrect” erroru ekranda görünür  
**Status:** Pass  
