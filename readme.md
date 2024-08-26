# Mimic40

A tiny ortho board that is pretending to be a fullsize. I have not ordered any pcbs yet so consider these files *under development* until i can order some to test if they work.
![photo of the layout](./layout.png)

<!-- ![image](https://preview.redd.it/kx884bndy0a61.jpg?width=960&crop=smart&auto=webp&s=1fa6bec5f84a0ee9537d982a2f033d2a1d11c4e5) -->

## tools used to build

1. [KLE](http://www.keyboard-layout-editor.com/##@_name=compact%20%22fullsize%22%20ortho%3B&@_y:0.25&c=%23393b3b&t=%23ffffff&p=DSA&a:7&f:4%3B&=Home&_x:0.25&c=%23c87e74&t=%23000000%3B&=Tab&_c=%23d0ccc0%3B&=Q&=W&=E&=R&=T&=Y&=U&=I&=O&=P&_c=%23c87e74%3B&=Back%20Space&=Delete&_x:0.5&c=%23d0ccc0%3B&=1&=2&=3%3B&@_c=%23393b3b&t=%23ffffff%3B&=End&_x:0.25&c=%23c87e74&t=%23000000%3B&=Esc&_c=%23d0ccc0%3B&=A&=S&=D&_n:true%3B&=F&=G&=H&_n:true%3B&=J&=K&=L&=%2F%3B&='&_c=%23c87e74%3B&=Return&_x:0.5&c=%23d0ccc0%3B&=4&=5&=6%3B&@_c=%23393b3b&t=%23ffffff%3B&=Vol%20+&_x:0.25&c=%23c87e74&t=%23000000%3B&=Shift&_c=%23d0ccc0%3B&=Z&=X&=C&=V&=B&=N&=M&=,&=.&=%2F%2F&_c=%23c87e74%3B&=Shift&_x:1.5&c=%23d0ccc0%3B&=7&=8&=9%3B&@_y:-0.75&x:13.5&c=%23393b3b&t=%23ffffff%3B&=%2F&uarr%2F%3B%3B&@_y:-0.25%3B&=Vol%20-&_x:0.25&c=%23c87e74&t=%23000000&w:1.25%3B&=Ctrl&_w:1.25%3B&=Alt&_w:1.25%3B&=Super&_c=%23393b3b&t=%23ffffff&w:1.25%3B&=%2F&dArr%2F%3B&_c=%23d0ccc0&t=%23000000&w:2%3B&=&_c=%23393b3b&t=%23ffffff&w:1.25%3B&=%2F&uArr%2F%3B&_c=%23c87e74&t=%23000000&w:1.25%3B&=Alt&_w:1.25%3B&=Fn&_x:3.75&c=%23d0ccc0%3B&=0&_c=%23c87e74%3B&=Enter%3B&@_y:-0.75&x:12.5&c=%23393b3b&t=%23ffffff%3B&=%2F&larr%2F%3B&=%2F&darr%2F%3B&=%2F&rarr%2F)
2. [kicad](https://www.kicad.org/download/) EDA
3. [pcb design guide](https://wiki.ai03.com/books/pcb-design)
4. [pcb generator](https://github.com/jeroen94704/klepcbgen) to setup the locations for components and initialise the KiCad project
5. [cherry mx datasheet](https://imgur.com/a/XMoHF)
<!-- x. [keyboard firmware builder](https://builder.mrkeebs.com/) for the matrix (if handwired) -->

These may be helpful for future in the design of a case

1. [builder.swillkb](builder.swillkb.com/) for the case
2. [ai03 plate generator](https://kbplate.ai03.com/)

## screenshots

![photo of layout](./3d_2.png)

![photo of layout](./3d_1.png)

![photo of layout](./PCB.png)

![photo of layout for RP2040](./PCB_2.png)

## references

> this was in part inspired by  [This reddit post](https://www.reddit.com/r/MechanicalKeyboards/comments/ksto32/chocolate_bar/?utm_source=share&utm_medium=web2x&context=3).

# to do

- [x] define outer geometry
- [x] per key rgb
- [x] route rows and columns
- [x] switch to rp2040 based design (no dev board)
- [ ] make plate cutout file (remember to add a 2u plate mount stabiliser)
- [ ] design a case (acrlic laser cut or possible 3d printed)
- [ ] order pcbs to test
- [ ] firmware
- [ ] take it from there
