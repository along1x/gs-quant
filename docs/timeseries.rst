
Timeseries Package
==================

Algebra
-------

.. currentmodule:: gs_quant.timeseries.algebra

.. autosummary::
   :toctree: functions

   abs_
   add
   and_
   ceil
   divide
   exp
   filter_
   floor
   floordiv
   if_
   log
   multiply
   not_
   or_
   power
   repeat
   sqrt
   subtract


Analysis
--------

.. currentmodule:: gs_quant.timeseries.analysis

.. autosummary::
   :toctree: functions

   diff
   first
   last
   count
   lag


Backtesting
-----------

.. currentmodule:: gs_quant.timeseries.backtesting

.. autosummary::
   :toctree: functions

   basket


Date / Time
-----------


.. currentmodule:: gs_quant.timeseries.datetime

.. autosummary::
   :toctree: functions

   align
   interpolate
   value
   day
   weekday
   month
   year
   quarter
   date_range


Econometrics
------------


.. currentmodule:: gs_quant.timeseries.econometrics

.. autosummary::
   :toctree: functions

   annualize
   beta
   change
   correlation
   excess_returns_
   index
   max_drawdown
   prices
   returns
   sharpe_ratio
   volatility


Statistics
----------

.. currentmodule:: gs_quant.timeseries.statistics

.. autosummary::
   :toctree: functions

   cov
   exponential_std
   generate_series
   max_   
   mean
   median   
   min_
   mode
   percentile
   percentiles
   product
   range_
   std
   sum_
   var
   winsorize
   zscores

.. autosummary::
   :toctree: classes

   LinearRegression
   SIRModel
   SEIRModel

Technical Analysis
------------------


.. currentmodule:: gs_quant.timeseries.technicals

.. autosummary::
   :toctree: functions

   bollinger_bands
   moving_average
   exponential_moving_average
   smoothed_moving_average
   relative_strength_index
   