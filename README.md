# denkstrap-grid
denkwerk standard grid
https://www.denkwerk.com


## Example without gutter

```
.grid-example--gutterless {
    @include grid(
        $width: 3
    )
}
```

## Example with gutter

```
.grid-example--gutter {
    @include grid(
        $width: 3,
        $gutter: true
    )
}
```

## Example with breakpoints

```
.grid-example--breakpoints {
    @include grid(
        $width: (
            default: 12,
            medium: 6,
            large: 3
        ),
        $gutter: true
    )
}
```
