"Imagine we're writing some code for a printer and we need to tell the printer how to print the pages for a book by giving it an array with pairs of page numbers to be printed. The book is bound in the middle so the first page is printed on the same sheet of paper as the last page, then the second page is printed on the same sheet of paper as the second to last page and so forth. Write a function that takes in an integer argument n and then returns an array of pairs of integers representing the page numbers to be printed. For simplicity we can assume that n is a multiple of 2."

E.g:

n = 4
[[1, 4], [2, 3]]

n = 32
[[1, 32], [2, 31], [3, 30], [4, 29], [5, 28], [6, 27], [7, 26], [8, 25], [9, 24], [10, 23], [11, 22], [12, 21], [13, 20], [14, 19], [15, 18], [16, 17]]
