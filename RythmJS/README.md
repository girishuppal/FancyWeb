Basic usage

♫
            use css class 'rythm-bass'
          
♫
            use css class 'rythm-medium'
          
♫
            use css class 'rythm-high'

 ---           
          
Added in v2.2.4

Font-size
Font-dance !
                  rythm.addRythm('fontSize1', 'fontSize', 0, 2)
              
Font-dance !
                  rythm.addRythm('fontSize', 'fontSize', 0, 2, {
                    min: 0.5,
                    max: 2
                  })
                
Added in v2.2.3
Border-Width
                  rythm.addRythm('borderWidth1', 'borderWidth', 0, 2)
                
                  rythm.addRythm('borderWidth2', 'borderWidth', 0, 2, {
                    min: 2,
                    max: 10
                  })
---
Added in v2.2.2

Neon
            rythm.addRythm('neon1', 'neon', 0, 10)
          
            rythm.addRythm('neon2', 'neon', 0, 10, {
              from: [0,0,255],
              to:[255,0,255]
            })
          
            rythm.addRythm('neon3', 'neon', 0, 10, {
              from: [255,255,0],
              to:[255,0,0]
            })
Border-Color
            rythm.addRythm('borderColor1', 'borderColor', 0, 10)
          
            rythm.addRythm('borderColor2', 'borderColor', 0, 10, {
              from: [0,0,255],
              to:[255,0,255]
            })
          
            rythm.addRythm('borderColor3', 'color', 0, 10, {
              from: [255,255,0],
              to:[255,0,0]
            })
          
Kern
𐇑🕪 rythm.js
            rythm.addRythm('kern1', 'kern', 0, 10 , {
              min: -5,
              max: 5
            })
          
𐇑🕪 rythm.js
            rythm.addRythm('kern2', 'kern', 0, 10 , {
              min: -5,
              max: 5,
              reverse: true,
            })

---
Added in v2.2.1

Blur
♫
            rythm.addRythm('blur1', 'blur', 0, 10)
          
♫
            rythm.addRythm('blur2', 'blur', 0, 10, {
              reverse: true
            })
          
♫
            rythm.addRythm('blur3', 'color', 0, 10, {
              max: 16
            })
Swing
♫
            rythm.addRythm('swing1', 'swing', 0, 10)
          
♫
            rythm.addRythm('swing2', 'swing', 0, 10, {
              curve: 'up',
            })
          
♫
            rythm.addRythm('swing3', 'swing', 0, 10, {
              direction: 'left',
            })
          
♫
            rythm.addRythm('swing4', 'swing', 0, 10, {
              radius: 10,
            })

---
Added in v2.2.0

Border-Radius
            rythm.addRythm('radius1', 'radius', 0, 10, {
              min: 0,
              max: 30
            })
          
            rythm.addRythm('radius1', 'radius', 0, 10, {
              reverse: true,
              min: 0,
              max: 30
            })
          
---
Added in v2.0.0

Pulse
♫
            rythm.addRythm('pulse1', 'pulse', 0, 10)
          
♫
            rythm.addRythm('pulse2', 'pulse', 0, 10, {
              min: 0.1,
              max: 1
            })
          
♫
            rythm.addRythm('pulse3', 'pulse', 0, 10, {
              min: 1,
              max: 1.75
            })
          
Jump
♫
            rythm.addRythm('jump1', 'jump', 0, 10)
          
♫
            rythm.addRythm('jump2', 'jump', 150, 40, {
              min: -20,
              max: 20
            })
          
Shake
♫
            rythm.addRythm('shake1', 'shake', 0, 10)
          
♫
            rythm.addRythm('shake2', 'shake', 150, 40, {
              min: 0,
              max: 20
            })
          
♫
            rythm.addRythm('shake3', 'shake', 0, 10, {
              direction: 'left'
            })
          
Twist
♫
            rythm.addRythm('twist1', 'twist', 0, 10)
          
♫
            rythm.addRythm('twist2', 'twist', 0, 10, {
              min: 20,
              max: 180
            })
          
♫
            rythm.addRythm('twist3', 'twist', 0, 10, {
              direction: 'left'
            })
          
Vanish
♫
            rythm.addRythm('vanish1', 'vanish', 0, 10)
          
♫
            rythm.addRythm('vanish2', 'vanish', 0, 10, {
              reverse: true
            })
          
Background-Color
            rythm.addRythm('color1', 'color', 0, 10)
          
            rythm.addRythm('color2', 'color', 0, 10, {
              from: [0,0,255],
              to:[255,0,255]
            })
          
            rythm.addRythm('color3', 'color', 0, 10, {
              from: [255,255,0],
              to:[255,0,0]
            })