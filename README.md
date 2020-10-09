# epochadd

add year, month, day to unix epoch timestamp

- supports year, month, day in positive and negative integers
- supports seconds, milliseconds or nanoseconds timestamps
- all datetimes in UTC

# download
`curl https://raw.githubusercontent.com/Luke31/epochadd/main/epochadd --output ~/bin/epochadd`

# usage
```
epochadd <inputepoch> <years> <months> <days>
```

[![asciicast](https://asciinema.org/a/i1Csv27G94PjQuHxKNAohbVb5.svg)](https://asciinema.org/a/i1Csv27G94PjQuHxKNAohbVb5)

# Hint
Doesn't work for dates after `2286-11-20 17:46:39` (epoch 9999999999)
