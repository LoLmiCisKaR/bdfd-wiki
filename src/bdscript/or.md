# $or
Returns 'true' if at least one of the provided conditions is true, otherwise 'false' is returned.

## Usage
```
$or[confitions;...]
```

### Parameters
- `conditions `(Type: String || Flag: Required)`: Conditions to check. Separate conditions using `;`.

## Example
```
$nomention
$if[$or[$message==hi;$message==hey;$message==hello]==true]
Hello $username!
$endif
```

![example](https://user-images.githubusercontent.com/69215413/128616191-44fad868-fdd2-460b-8c32-89e92f32cc7a.png)
