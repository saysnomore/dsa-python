1. THE 'count()' METHOD
- This method is used to determine how many times an item appears in a tuple. Here is an example of checking how many times the string Rust appears in a tuple named programming_languages:
      programming_languages = ('Rust', 'Java', 'Python', 'C++', 'Rust')
      programming_languages.count('Rust') # 2
- Since Rust appears twice in the tuple, the count() method returns the number 2.
- If the specified item in the count() method is not present at all in the tuple, then the return value is 0:
      programming_languages = ('Rust', 'Java', 'Python', 'C++', 'Rust')
      programming_languages.count('JavaScript') # 0
- If no arguments are passed into the count() method, then Python raises a TypeError:
      programming_languages = ('Rust', 'Java', 'Python', 'C++', 'Rust')
      programming_languages.count()
      
      """
      Traceback (most recent call last):
        File "<stdin>", line 2, in <module>
      TypeError: tuple.count() takes exactly one argument (0 given)
      """

2. THE 'index()' METHOD
- This method is used to find the index where a particular item is present in a tuple.
- Here is an example of using the index() method to find the index for the string Java:
      programming_languages = ('Rust', 'Java', 'Python', 'C++', 'Rust')
      programming_languages.index('Java') # 1
- If the specified item cannot be found, then Python raises a ValueError:
      programming_languages = ('Rust', 'Java', 'Python', 'C++', 'Rust')
      programming_languages.index('JavaScript')
      
      """
      Traceback (most recent call last):
        File "<stdin>", line 2, in <module>
      ValueError: tuple.index(x): x not in tuple
      """
