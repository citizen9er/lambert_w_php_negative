
# PHP Lambert W Function
PHP extension to compute the negative branch of the [Lambert W(x) function](https://en.wikipedia.org/wiki/Lambert_W_function).

# Installation
```
git clone https://github.com/citizen9er/lambert_w_php_negative;
cd php_lambertw;
phpize;
./configure;
make -j2;
```

# Run The Test
```
php -dextension=$(pwd)/modules/lambertw.so test.php
```

# Thanks to

#### ammarfaizi2 
 - php extension of LambertW function for primary branch

#### Lambert W Function for Applications in Physics
- https://dx.doi.org/10.1016/j.cpc.2012.07.008
- https://arxiv.org/abs/1209.0735

#### C++ implementation of the Lambert W(x) function
- https://github.com/DarkoVeberic/LambertW

# License
This package is licensed under the MIT license.
