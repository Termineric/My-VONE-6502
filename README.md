What is "THE My-VONE-6502"?
===============================================================================

  "THE My-VONE-6502" is a rebuild from "My First One" how I call this computer now.
  This build in time I whas still playing with flip-flops (Professer fixed) at that time there where some kits you could build your yourself ("junior computer", "Kim1" and more).
  I'm from Holland and I have a subscription to "Electuur" ("Elektor") in March 1980 start using part of "Electuur junior computer" to build my own version of how a computer most look and work.
  I took my time to build, because of budget. I was still a young boy and these things weren't as cheap, like they are now.

  When I got Vic20 (a year before stop they stopped selling it here) after that I changde hardware so it would work with the Vic20 

How "My First One" differences in ways from plain computers
===============================================================================
    * Key-board is hexadecimal is internal 4 bit 
      Display has 4 Address & 2 Data hexadecimal 7 segment display is not controlled CPU controlled by logic chips & Eprom have 2 modes CPU/Program Mode(Run-Mode) & Debug-Mode.
   
      * CPU/Program Mode
          Keyboard info locate 3 address all 4 bits combi to 8 bits Data, Low-Address, High-Address 
            [1] is (Read)key-board Value/(write)D0/D7 Data display
            [2] is (Read)key-Board Command/(write)A0/A7 Low-Adress display
            [3] is (write)A0/A7 High-Adress display

      * Debug mode the CPU play dead (not running) 
            So you work right to left type first value then adress and this 
            mode is build to my way of thinken and how type quick data in 
            if you type all need to change you press "PUT" 
            if need load adress Press "GET" and then adress
            ther where Arrow keys Up,Down,Left,Right Up(+1) & Down(-1) control
            adress count and  Left(+1) & Right(-1) Position off edit cursor
            if cursor<DS0 then cursor=DS5 or if cursor>DS5 then cursor=DS0 
            (This i used flipFlops)

    * "My First One" have begin a bus because found in scrapyard a 19" case with a backplain and some card in there I remove card And backplain,
      put connectors in as i need then make my bus by hand all pins as I need it put more connectors in 
      The funny part afer "Electuur junior computer" came out I didn't needed to change much as my bus and cards have the same pin assignment this ment change 8 wires 1 power rail.
      I used the same connector Din41612 A,C Not the Din411617 I wanted to start using the hardware that "Electuur" got to make .
    
    * My kernel was very small only handle basic functions 
        "Get Keyboard Char" 
        "Put Display char" 
        "Typeing function" 
        "RS Get input" 
        "RS Put output"
        "Burn Eprom" 
        "Read Eprom"
        "Check Eprom"

    * Uses software & Hardware from "Electuur" or other places don't know anymore like 
        Ben Eater he is the best Youtuber around. I like how he explains things in a way anyone can get into it. "THANKS Ben Eater & "8 bit Guy" you make me love my electronics again!"

    * All programming I don't do on paper, but by hand and then type in on keyboard

    * I build on card program Eproms (old syle 18/21/25 volts) locate in D000 
      (I wish still have this card I can't remember how I build it.)

    After i got the VIC20 I made an interface to 19" Case and remove CPU-card and keyboard because VIC20 can't play dead, so only memory-card (some small changes to the address and the VIC20 has more memory)


"THE My-VONE-6502" 
===============================================================================
    I started building the computer and below I describe what my plans are and what I've done.

    *I have OLD 19" case and 3 Backboard for euro-bus pcb's the layout is made for Din-41612 row A,B,C 
      Pin assignment from "junior computer" Din41612 A,C rows connectors the B row for extend version extra adress space see Bus pin assignment (this will be made soon).
      The Main CPU-BOARD can have extends-board on in that connect the A0/A16 to A0/A16 But when 74612 extended-board is there so you can address many more memory for this use I use the B row

    * "THE My-VONE-6502 KeyBoard"
        * Debug mode
        * CPU/Program Mode

    * CPU-Card 
        * THE My-VONE-6502 Kernel
        * Direct Flascard reader/writer
    
    *   VGA/HDMI output (The veraboard. Yes same as X16. I am waiting on someone who can tell me how make that board to get back to me) 
    
    * Rom-Card
        *   Basic (same thing close to commodore basic)
        *   Pascal (hey i'm delphi programmer)
    
    * Ram-Card 
      * Unkown
    
    *   Like connect a commdore floppy drive (sim version or real) 
    *   Via Card plain I.O

P.s.
===============================================================================
  I am writing this down from memory. It's because there's not much left from the "My First One" I build only what remember 

  Please forgive my spelling errors, I have dyslexia since I was born.

  You can use any of my stuff, that's ok, but drop me a E-mail or something so I there's more people loving this.


Handy resouces
===============================================================================
  retro.hansotten.nl/6502-sbc/elektuur-junior/elektor-junior-literature/junior-dutch/

  www.retro-lab.nl/?p=618
