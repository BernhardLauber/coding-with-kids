
JustCode
========
Key Goals
-----------
The main goals are to learn how to use a language and write and understand your own program.

Options
-------

Scratch
~~~~~~~

KidsRuby
~~~~~~~~

Python
~~~~~~

Here is some code::

    def countAdjacent(p, c, r, yChange, xChange):
        global board
        adjacentCount = 0

        while True :
            c = c + xChange
            if c < 0 or c > 7:
                return adjacentCount
          
            r = r + yChange
            if r < 0 or r > 7:
                return adjacentCount
            
            if board[c][r] == p:
                adjacentCount = adjacentCount + 1
            else:
                return adjacentCount


And here is some C# code just in case 
you wanted to see it:

.. code-block:: csharp

    private static string GetMessageFromException(Exception ex)
    {
        if (ex == null) return "";
        if (ex.InnerException != null)
        {
            return GetMessageFromException(ex.InnerException);
        }
        return ex.Message;
    }    

Und here some SQL Code:

.. code-block:: sql
    :linenos:

    SELECT * FROM Customers

Hopscotch
~~~~~~~~~


