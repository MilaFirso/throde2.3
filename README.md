Задание 3
Защищённый обмен данными

    Создайте класс Data, содержащий в качестве полей скалярные данные и мьютекс.
    Создайте функцию swap, которая принимает ссылки на два объекта класса Data и обменивает их местами.
    В функциях нужно сначала захватить мьютексы обоих объектов, а затем выполнить обмен данными.
    Реализуйте три варианта этой функции: при помощи lock, scoped_lock и unique_lock.
