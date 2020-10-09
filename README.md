# epochadd

add year, month, day to unix epoch timestamp

- supports year, month, day in positive and negative integers
- supports seconds, milliseconds or nanoseconds timestamps

# download
`curl https://raw.githubusercontent.com/Luke31/epochadd/main/epochadd --output ~/bin/epochadd`

# usage
```
epochadd <inputepoch> <years> <months> <days>
```

[![asciicast](https://asciinema.org/a/i1Csv27G94PjQuHxKNAohbVb5.svg)](https://asciinema.org/a/i1Csv27G94PjQuHxKNAohbVb5)

# Hint
Stops working at `2033-05-18 03:33:19` (epoch 1999999999)
