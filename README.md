<img  src="https://github.com/auroracreation/frontend-recruitment-task-header-with-menu/blob/master/logo.png"  alt="Aurora Creation logo"/>

# Zadanie rekrutacyjne Magento Developer


## Treść

Twoim zadaniem będzie stworzenie prostego modułu dodającego labele do produktów. Labele będą przechowywane w oddzielnej tabeli Mysql, o następującej strukturze:
- label_id
- label_text
- options

Do powiązań labeli z produktami powinna byc stworzona tabela "product_labels" zawierająca:
- product_id
- label_id

Celem ćwiczenia jest sprawdzenie jak radzisz sobie z kodem Magento, tworzeniem modułów, oraz stosowaniem dobrych praktyk w programowaniu.

## Co musi być zawarte w rozwiązaniu?

1. Tabela "labels" i "product_labels" dodana za pomocą db_schema
2. Formularz edycji, dodawania labeli (UiComponents).
3. W edycji produktu możliwość przypisania kilku labeli do jednego produktu
4. Od strony sklepu, wyświetlanie labeli (w dowolnym miejscu) zarówno na karcie produktu jak i w kategoriach 

## Co może (ale nie musi) być zawarte w rozwiązaniu

1. Testy PHPUnit
2. Opcje dla labeli (np. kolor)
3. Inne możliwości przypisania labeli do produktów / poza formularzem edycji produktu

## Na co warto zwrócić uwagę?

1. Kod zgodny z wytycznymi PSR i Magento.
2. Strukturę projektu.
3. Strukturę bazy danych (indeksy, klucze obce, typy pól itd.).
4. Praktyczną umiejętność wykorzystania wzorców SOLID, DI, DRY, KISS.
5. Kod zgodny z wytycznymi Magento
5. Uprawnienia ACL

## Na co zwrócimy uwagę przy ocenie?

1. Poprawność ze standardami kodowania PSR-2 i Magento MEQP2.
2. Łatwość rozbudowy modułu.
3. Dobre praktyki programistyczne.
4. Reużywalny kod.
5. Używanie design patterns.
6. Testy PHPUnit
