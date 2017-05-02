# ctestl
A simple script to run ctest easily with multiple labels

# Usage
How to run ctest on tests that have multiple labels?
For example with three labels (there can be any number):

```bash
$ ctestl label1 label2 label3
```

The script picks all those tests that have all the labels.

Thanks to David C. who proposed a bash script in http://cmake.3232098.n2.nabble.com/Running-test-who-have-two-labels-td7595208.html
