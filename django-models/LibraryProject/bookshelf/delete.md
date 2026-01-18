```python
<<<<<<< HEAD
from bookshelf.models import Book

book = Book.objects.get(title="Nineteen Eighty-Four")
book.delete()
Book.objects.all()
=======

from bookshelf.models import Book



book = Book.objects.get(title="Nineteen Eighty-Four")

book.delete()

Book.objects.all()



>>>>>>> c09e741 (Move CRUD documentation into bookshelf app and ignore generated files)
