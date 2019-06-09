# Introduction

This is an example of how to sync GitHub with GitBook. Here you will find documentation of all projects.

Ut at est a dui efficitur finibus. Pellentesque ex massa, cursus non sagittis quis, porta vitae nunc. Mauris sodales quis purus nec dapibus. Nam nec arcu ac est dapibus rutrum. Donec pellentesque, libero a egestas pellentesque, justo nibh eleifend lectus, vitae bibendum est nulla ut ex. In scelerisque volutpat ligula. Suspendisse sodales mi sed dui aliquam, eu feugiat massa malesuada. Nullam odio arcu, maximus non ex vel, semper tristique lectus. Vivamus consectetur enim felis, sed posuere velit lacinia et. Sed at eros sodales diam egestas efficitur fermentum eget nisl. Suspendisse id tempus ligula. Aliquam in dignissim eros. Fusce aliquet purus turpis, sit amet vestibulum metus volutpat vel. Ut finibus gravida nulla et vehicula.

## Configuration

Create a YAML config file in root directory

```yaml
root: ./gitbook/
structure:
  readme: README.md
  summary: SUMMARY.md
```

Create a `gitbook` directory to hold introduction page and book summary.

```text
gitbook/
    README.md
    SUMMARY.md
```

The summary creates an outline of the book.

```text
# Summary

## Active Projects

* [Project A](../project_a/README.md)
* [Project B](../project_b/README.md)

## Past Projects

* [Project C](../project_c/README.md)
```

