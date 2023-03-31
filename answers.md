# CMPS 2200 Recitation 6
## Answers

**Name:**_________________________


Place all written answers from `recitation-06.md` here for easier grading.



- **d.**

File | Fixed-Length Coding | Huffman Coding | Huffman vs. Fixed-Length
----------------------------------------------------------------------
f1.txt    |                     |                |
alice29.txt    |                     |                |
asyoulik.txt    |                     |                |
grammar.lsp    |                     |                |
fields.c    |                     |                |

| File|   Fixed-Length Coding |   Huffman Coding |   Huffman vs. Fixed-Length |
|-----|---------------------|----------------------|------------------|
|   f1.txt |               1340 |                826 |            0.616418 |
|  alice29.txt |               1039367 |                676374 |            0.650756 |
|  asyoulik.txt |              876253 |                606448 |            0.692092 |
| grammar.lsp |               26047 |                17356 |            0.666334 |
| fields.c |               78050 |                56206 |            0.720128 |

The consistent trend I see is that the Huffman Coding algorithm has significatnly less cost than the Fixed-Length Coding algorithm for all five files. The ratio of Huffman Coding cost to Fixed-Length Coding cost for all five files is around 0.6-0.7. The ratio of Huffman Coding cost to Fixed-Length Coding cost also seems to increase when the file size increases, although this increase is not directly proportional.

- **e.**

If every character has the same frequency, the Huffman tree is balanced. The expected cost would be nlogn because the tree will have n leaves and the tree is balanced. This cost is consistent across documents.
