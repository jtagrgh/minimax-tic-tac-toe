I can't beat this guy 😡!

```
Move x,y: 1,1
|   |   |   |
|   | 1 |   |
|   |   |   |

| 0 |   |   |
|   | 1 |   |
|   |   |   |

Move x,y: 0,1
| 0 |   |   |
| 1 | 1 |   |
|   |   |   |

| 0 |   |   |
| 1 | 1 | 0 |
|   |   |   |

Move x,y: 2,0  
| 0 |   | 1 |
| 1 | 1 | 0 |
|   |   |   |

| 0 |   | 1 |
| 1 | 1 | 0 |
| 0 |   |   |

Move x,y: 1,2
| 0 |   | 1 |
| 1 | 1 | 0 |
| 0 | 1 |   |

| 0 | 0 | 1 |
| 1 | 1 | 0 |
| 0 | 1 |   |

Move x,y: 2,2
| 0 | 0 | 1 |
| 1 | 1 | 0 |
| 0 | 1 | 1 |

Draw.
```

A Tic Tac Toe opponent that's unbeatable! It uses the [Minimax algorithm](https://en.wikipedia.org/wiki/Minimax).

I've noticed that it become unbeatable at a max depth of two. Why is that true?