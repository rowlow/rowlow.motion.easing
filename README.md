# rowlow.motion.easing

A easing module with loads of easing functions for ROW LOW framework

## Install

```
    bower install --save rowlow.motion.easing
```


## Functions

```
    rowlow-ease() // Returns the easing function by a given name
```

## Usage

### SCSS

```
    a:hover{
        transition: all .1s rowlow-ease("in-out-quad") .2s;
    }
```

### Easing Functions

```
    linear
    ease
    in
    out
    in-out
    in-sine
    out-sine
    in-out-sine 
    in-quad
    out-quad
    in-out-quad
    in-cubic  
    out-cubic 
    in-out-cubic
    in-quart 
    out-quart  
    in-out-quart 
    in-quint
    out-quint  
    in-out-quint
    in-expo
    out-expo 
    in-out-expo 
    in-circ
    out-circ
    in-out-circ
    in-back"
    out-back 
    in-out-back
```