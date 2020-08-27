# What is this?

Get a backdrop shadow for images.

## Installation 

`npm i pictureBillboard --save`

Then...

...
import { pictureBillboard } from 'pictureBillboard';

pictureBillboard({
    shadow_type:'soft',
    padding: false;
});

## Options

pictureBillboard supports 2 options, both of which are optional:

* *shadow_type* - _hard / soft_ (defaults to soft)
* *padding* - _boolean_ (Defaults to false)