# View and Pure Functions

Getter functions can be declared `view` or `pure`.

## View function

`View` function declares that no state will be changed.

```
    function addToX(uint y) public view returns (uint) {
        return x + y;
    }
```

## Pure function

`Pure` function declares that no state variable will be changed or read.

```
    function add(uint i, uint j) public pure returns (uint) {
        return i + j;
    }
```
