# SI_2025_lab2_226138

Стефан Петрушевиќ 226138

--------------------ОДГОВОРИ-----------------------

1. Во ред
2. Поставено е како датотека со име <Dijagram.jpg>
![dijagram](https://github.com/user-attachments/assets/3869ae9b-f526-4aa1-9e90-a0fc5f24d459)

3. Има цикломатска комплексност 9, го добив со V(G) = P + 1, има и слика < Dijagram.jpg>, има 8 предикатни јазли
4. Минимално мора да има 5 тест случаи, може да се види во прикачената датотека со име testovi
![Screenshot (311)](https://github.com/user-attachments/assets/d82b7ea1-a2b5-4ca0-8d53-5496720b14e2)

5. Тестирање на if (item.getPrice() > 300 || item.getDiscount() > 0 || item.getQuantity() > 10) според multiple condition
   TXX- Кога цена на продукт е поголема од 300 , пример Сирење со цена 480 попуст 43 количина 2
   FTX- Кога имаме продукт со цена помала од 300, ама кој е на попуст, пример Бомбоњера цена 200 попуст 20 количина 3
   FFT- Кога имаме продукт со цена помала од 300, кој нема попуст, ама купуваме повеќе од 10 такви продукти, пример Смоки цена 20 попуст 0 количина 12
   FFF- Кога имаме продукт со цена помала од 300, кој нема попуст и не купуваме повеќе од 10 такви продукти, пример Чоколада цена 60, попуст 0, количина 5 

