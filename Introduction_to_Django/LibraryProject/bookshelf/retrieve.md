Book.objects.all()

<<<<<<< HEAD
# Expected Output:
# <QuerySet [<Book: 1984>]>

book = Book.objects.get(title="1984")
book.title, book.author, book.publication_year

# Expected Output:
# ('1984', 'George Orwell', 1949)
=======


\# Expected Output:

\# <QuerySet \[<Book: 1984>]>



book = Book.objects.get(title="1984")

book.title, book.author, book.publication\_year



\# Expected Output:

\# ('1984', 'George Orwell', 1949)



>>>>>>> c09e741 (Move CRUD documentation into bookshelf app and ignore generated files)
