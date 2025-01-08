# My Digital Garden

https://binarydigit.city

<img src="https://codeberg.org/BinaryDigit/website/raw/branch/main/assets/seedling-animated.gif" alt="Animated seedling graphic" width="15%">

Run locally:

```hugo server --baseURL=https://binarydigit.city/ --appendPort=false```

Then git hook

```printf '#!/bin/sh\nneocities push public' >.git/hooks/pre-push && \ chmod u+x .git/hooks/pre-push```