

page_type: reference
<style> table img { max-width: 100%; } </style>


<!-- DO NOT EDIT! Automatically generated file. -->

# tf.keras.callbacks.ProgbarLogger

## Class `ProgbarLogger`

Inherits From: [`Callback`](../../../tf/keras/callbacks/Callback)



Defined in [`tensorflow/python/keras/callbacks.py`](https://www.github.com/tensorflow/tensorflow/blob/r1.9/tensorflow/python/keras/callbacks.py).

Callback that prints metrics to stdout.

#### Arguments:

* <b>`count_mode`</b>: One of "steps" or "samples".
        Whether the progress bar should
        count samples seen or steps (batches) seen.
* <b>`stateful_metrics`</b>: Iterable of string names of metrics that
        should *not* be averaged over an epoch.
        Metrics in this list will be logged as-is.
        All others will be averaged over time (e.g. loss, etc).


#### Raises:

* <b>`ValueError`</b>: In case of invalid `count_mode`.

## Methods

<h3 id="__init__"><code>__init__</code></h3>

``` python
__init__(
    count_mode='samples',
    stateful_metrics=None
)
```



<h3 id="on_batch_begin"><code>on_batch_begin</code></h3>

``` python
on_batch_begin(
    batch,
    logs=None
)
```



<h3 id="on_batch_end"><code>on_batch_end</code></h3>

``` python
on_batch_end(
    batch,
    logs=None
)
```



<h3 id="on_epoch_begin"><code>on_epoch_begin</code></h3>

``` python
on_epoch_begin(
    epoch,
    logs=None
)
```



<h3 id="on_epoch_end"><code>on_epoch_end</code></h3>

``` python
on_epoch_end(
    epoch,
    logs=None
)
```



<h3 id="on_train_begin"><code>on_train_begin</code></h3>

``` python
on_train_begin(logs=None)
```



<h3 id="on_train_end"><code>on_train_end</code></h3>

``` python
on_train_end(logs=None)
```



<h3 id="set_model"><code>set_model</code></h3>

``` python
set_model(model)
```



<h3 id="set_params"><code>set_params</code></h3>

``` python
set_params(params)
```




