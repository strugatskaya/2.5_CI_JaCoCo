### **Counters**

*INSTRUCTION*   
    
Предоставляет информацию о количестве кода, который был выполнен или пропущен. Эта метрика полностью независима от исходного форматирования и всегда доступна даже в отсутствие отладочной информации в файлах классов.

*LINE*
            

Рассчитывает информацию о покрытии для отдельных строк. Исходная строка считается выполненной тогда, когда была выполнена хотя бы одна команда, назначенная этой строке.

*BRANCH*        
    
(в данном случае выбран этот counter, т.к. в коде есть оператор if)
Вычисляет охват веток для всех операторов if и switch. Эта метрика подсчитывает общее количество таких ветвей в методе и определяет количество выполненных или пропущенных ветвей.

*COMPLEXITY*
    
Вычисляют циклическую сложность для каждого не абстрактного метода и суммирует сложность для классов, пакетов и групп. Циклическая сложность - это минимальное количество путей, которые могут в (линейной) комбинации генерировать все возможные пути с помощью метода. Таким образом, значение сложности может служить указанием на количество единичных тестовых случаев для полного покрытия определенного программного обеспечения. Показатели сложности всегда можно вычислить даже в отсутствие отладочной информации в файлах классов.