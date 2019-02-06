### textillate
---
https://github.com/jschr/textillate

```js
$(function(){
  $('.tlt').textillate();
})

$('.tlt').on('inAnimationBegin.tlt', function(){
});

$('.tlt').textillate({ in: { effect: 'rollIn' } });

$('.tlt').texttillate();

$('.tlt').textillate({
  selector: '.texts',
  loop: false,
  minDisplayTime: 2000,
  initialDalay: 0,
  autoStart: true,
  inEffects: [],
  outEffects: [ 'hinge' ],
  in: {
    effect: 'fadeinLeftBig',
    delayScale: 1.5,
    delay: 50,
    sync: false,
    shuffle: false,
    reverse: false,
    callback: function(){}
  },
  out: {
    effect: 'hinge',
    delayScale: 1.5,
    delay: 50,
    sync: false,
    shuffle: false,
    reverse: false,
    callback: function(){}
  },
  callback: function(){},
  type: 'char'
});
```

```
<h1 class="tlt">
  <ul class="texts">
    <li data-out-effect="fadeOut" data-out-shuffle="true"></li>
    <li data-in-effect="fadeIn"></li>
  </ul>
</h1>
```

```
```

