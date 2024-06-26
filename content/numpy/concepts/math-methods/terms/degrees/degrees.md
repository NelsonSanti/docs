---
Title: '.degrees()'
Description: 'Converts angles expressed in radians into degrees.'
Subjects:
  - 'Computer Science'
  - 'Data Science'
Tags:
  - 'Arrays'
  - 'Functions'
  - 'NumPy'
CatalogContent:
  - 'learn-python-3'
  - 'paths/computer-science'
  - 'paths/data-science'
  - 'paths/data-science-foundations'
---

In NumPy, the **`.degrees()`** function converts angles expressed in radians into degrees.

## Syntax

```pseudo
numpy.degrees(x, out=None, where=True)
```

- `x`: The number or array of numbers in radians that must be converted.
- `out`: An optional parameter specifying where the result is stored.
- `where`: An optional parameter specifying a condition to filter which elements to convert.

## Example 1

```py
# Importing the 'numpy' library as 'np'
import numpy as np

# Convert a single number from radians to degrees
radNum = 4
result = np.degrees(radNum)
print(result)
```

Below is the output generated by the above code snippet:

```shell
229.1831180523293
```

## Example 2

```py
# Importing the 'numpy' library as 'np'
import numpy as np

# Convert an array of numbers from radians to degrees
radArray = [np.pi/2, np.pi/6, 5, 8]
result = np.degrees(radArray)
print(result)
```

> **Note:** `np.pi` represents the mathematical constant approximately equal to `3.141592653589793`.

The output generated by the above code snippet is as follows:

```shell
[ 90.          30.         286.47889757 458.3662361 ]
```

## Codebyte Example

Experiment with the `.degrees()` function using the Codebyte below:

```codebyte/python
import numpy as np

radArray = [1, 32, 100]
result = np.degrees(radArray)
print(result)
```
