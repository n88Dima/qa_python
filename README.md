# Описание тестов

1. test_add_new_book_invalid_name
   Проверяет, что нельзя добавить книгу с недопустимым названием (пустое или слишком длинное имя).

2. test_set_book_genre_valid_case
   Проверяет успешное назначение жанра книге, если жанр допустимый.

3. test_set_book_genre_invalid_genre  
   Проверяет, что при назначении недопустимого жанра книга остается без жанра.

4. test_get_books_with_specific_genre  
   Проверяет, что функция возвращает список книг определенного жанра.

5. test_get_books_for_children  
   Проверяет, что функция возвращает список книг, подходящих для детей.

6. test_add_book_in_favorites_valid_case  
   Проверяет успешное добавление книги в список избранных, если книга есть в коллекции.

7. test_add_book_in_favorites_not_in_books_genre  
   Проверяет, что невозможно добавить книгу в избранное, если она не была добавлена в коллекцию.

8. test_delete_book_from_favorites  
   Проверяет успешное удаление книги из списка избранных.

9. test_get_book_genre  
   Проверяет, что у только что добавленной книги жанр пустой (значение по умолчанию).