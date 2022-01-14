

Задание1 Переписать банкомат из ЛЗ #3 на работу с классами. Класс должен называться - CashMachine. Программа должна запускаться с помощью метода класса init, создавать экземпляр класса и взаимодействовать с пользователем согласно условиям задачи.

Задание2 Пользователь запускает программу и отвечает на вопрос, с каким ресурсом он хочет взаимодействовать:

    После чего он может передать тип запроса GET/POST/PUT/DELETE
    GET index - должен возвращать все посты из памяти и их индекс в массиве (прим. 0. Hello World \n 1. Hello (again))
    GET show - должен запрашивать идентификатор поста и показывать пост по переданному идентификатору (как в index только 1 пост)
    POST create - должен запрашивать текст поста, добавлять его в массив постов и возвращать в ответ идентификатор поста и сам пост
    PUT update - должен запрашивать идентификатор поста, потом новый текст поста и заменить его. В результате выводить пост (как в экшене index)
    DELETE destroy - должен запрашивать идентификатор поста, затем удалять его из массива постов
    Нужно реализовать логику для PostsController
    Добавить CommentsController самостоятельно В отчете по заданию расписать, понимание работы класса Router, причины, по которым используется extend для модуля Resource В случае неправильного ввода (команды), ваша программа должна выдать соответствующее сообщение об ошибке, которое говорит клиенту, как ее исправить. Нельзя просто выводить "Error!" - это не поможет.

