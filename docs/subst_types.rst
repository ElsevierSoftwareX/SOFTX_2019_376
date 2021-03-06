.. |range_init| replace:: This is the range object description

.. |limits_init| replace:: A tuple containing the limits (as tuple) per dimension. So a tuple of the shape (n_obs, n_lower_upper) is expected. The limits within one dimension are specified by a tuple like (lower1, upper1, lower2, upper2,...). This example contains two ranges, from lower1 to upper1 and from lower2 to upper 2 (+ ,... more). Example: ((-1, 5), (-4, 1, 2, 5)) translates to: first dimension goes from -1 to 5, the second dimension from -4 to 1 and from 2 to 5.

.. |limits_arg_descr| replace:: If a :py:class:~`zfit.Space` is given, it is used as limits. Otherwise arguments to instantiate a Range class can be given as follows.|limits_init|

.. |lower_arg_descr| replace:: The lower bounds of the intervall. Has to be of the form (n_intervalls, n_obs). The intervall is the differenz to the upper bounds. Example: ((-1, 4), (1, 6), (3, 10),...)  # 2-d function

.. |upper_arg_descr| replace:: The upper bounds of the intervall. Has to be of the form (n_intervalls, n_obs). The intervall is the differenz to the lower bounds. Example: ((-0.1, 5), (2, 8), (7, 14),...)  # 2-d function

.. |dims_arg_descr| replace:: The dimensions given as a tuple of integers.

.. |dtype_arg_descr| replace:: The DType of the return value. Defaults to the zfit default (usually float64).

.. |norm_range_arg_descr| replace:: The normalization range over which the function will be normalized (to 1).

.. |Space_ref| replace:: :py:class:`~zfit.Space`

