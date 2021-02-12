===============================================================================
Whatt is "THE My-VONE-6502" 
===============================================================================

"THE My-VONE-6502" is rebuild from "My First One" how I call this computer now 
i build in time I whass playing with flip-flops (Profeser fix)
Rond that that time i'm talking about ther where some kits to build your your
computer your self ("junior computer", "Kim1" and more) But I'm from Holland i
have subscription to "Electuur" ("Elektor") in maart 1980 start using part of 
"Electuur junior computer" to build my version of how computer most look don't
for get small boy small wallet parts not cheap (like now) 

When i get Vic20 (a year befor stop saling in here) after that i change 
hardware so will work the Vic20 

===============================================================================
How "My First One" differences in follow ways One plain computers
===============================================================================
    * key-board is 4 bit internel & Hex and 4 adress 2 vaule 7 segment display
      is not controld but self runing have 2 modes Run-Mode & Debug-Mode
        In running mode 3 adress and the display and keyboard available to 
        CPU/Program
            [1] is (Read)keyboard Value/(write)D0/D7 value display
            [2] is (Read)keyboard Status/(write)A0/A7 Adress display
            [2] is (Read)keyboard Command/(write)A0/A7 Adress display
        In Debug mode the CPU play dead(not running) 
            So you work right to left type first value then adress and this 
            mode is build to my way of thinken and how type quick data in 
            if you type all need to change you press "PUT" 
            if need load adress Press "GET" and then adress
            ther where Arrow keys Up,Down,Left,Right Up(+1) & Down(-1) control
            adress count and  Left(+1) & Right(-1) Position off edit cursor
            if cursor<DS0 then cursor=DS5 or if cursor>DS5 then cursor=DS0 
            (This i used flipFlops)

    * My have from begin a bus because found in scrapyard a 19" case with a 
      backplain and some card in there i remove card end backplain
      Don't ask whatt on this cards i don't know any more put connectors in 
      as i need then make my bus by hand all pins as i need then funny afer 
      "Electuur junior computer" i change my bus and cards have same 
      pin assignment this ment change 8 wires 1 power rail 
      I used same connector Din41612 A,C Not the Din411617 I want use the 
      hardware that "Electuur" make 
    
    * My kernel whas very small only handel basic function 
        "Get Keyboard Char" 
        "Put Display char" 
        "Typeing function" 
        "RS Get input" 
        "RS Put output"
        "Burn Eprom" 
        "Read Eprom"
        "Check Eprom"  

    * All programming i don on paper by hand and then type in on keyboard

    * i build on card program Eproms (old syle 18/21/25 volts) locate in D000
     (i wish still have this card i can't remember how i build it i think i 
      uses some other plan)

after i get Vic20 i make connect from VIC20 TO 19" Case and remove cpu-card 
and key-board because vic20 can't play dead so only memory-card(some small 
change the adress and vic20 have more memory)

===============================================================================
"THE My-VONE-6502" 
===============================================================================
I start building computer here under describe whatt i go or plan to uses .

    I have OLD 19" case and 3 backplain for euro-bus Din-41612 row A,B,C on PCB
    see Bus pin assignment (This will be made soon) This follow the 
    Pin assignment from "junior computer" Din41612 A,C rows connectors 
    the B row for extend version (extra adress space)
    Main CPU-BOARD have extends board on in that yust connect 
    the A0/A16 to A0/A16 But when 74612 extend-board is on ther you can adress
    many more memory for this use B row

    It get real keyboard (usb) and VGA/HDMI output (The veraboard 
    yes same as X16 this waiting on guy how make that board get back to me) 
    Like connect a commdore flopie drive (sim version) 
    Direct Flascard reader/writer

P.s.
I writing this as i remember it me because there not bit left from "My First One" 
i build only what remember 

Please please forgive for spelling errors I have dyslexia from when whass born.


>>>>>If can use any of my stuff is oke but drop me a E-mail or somthing<<<<
===============================================================================
Handy resouces
===============================================================================
retro.hansotten.nl/6502-sbc/elektuur-junior/elektor-junior-literature/junior-dutch/
www.retro-lab.nl/?p=618