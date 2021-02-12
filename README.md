
Whatt is "THE My-VONE-6502" 
===============================================================================

  "THE My-VONE-6502" is rebuild from "My First One" how I call this computer now.
  This build in time I whas still playing with flip-flops (Professer fixed) Rond that that time i'm talking about where some kits to build your your computer your self ("junior computer", "Kim1" and more).
  But I'm from Holland i have subscription to "Electuur" ("Elektor") in maart 1980 start using part of "Electuur junior computer" to build my version of how computer most look and work.
  Ibuild not very fast because of buget don't for get small boy small wallet parts not cheap (like now)

  When i get Vic20 (a year befor stop saling in here) after that i change hardware so will work the Vic20 

How "My First One" differences in follow ways One plain computers
===============================================================================
    * Key-board is hexadecimal is internal 4 bit 
      Dispaly Have 4 Adress & 2 Data hexadecimal 7 segment display is not controld CPU controlt by logic chips & Eprom have 2 modes CPU/Program Mode(Run-Mode) & Debug-Mode.
   
      * CPU/Program Mode
          Key-board info locate 3 adress All 4 bits combi to 8 bits Data , Low-Adress  , High-Adress 
            [1] is (Read)key-board Value/(write)D0/D7 Data display
            [2] is (Read)key-Board Command/(write)A0/A7 Low-Adress display
            [3] is (write)A0/A7 High-Adress display

      * Debug mode the CPU play dead(not running) 
            So you work right to left type first value then adress and this 
            mode is build to my way of thinken and how type quick data in 
            if you type all need to change you press "PUT" 
            if need load adress Press "GET" and then adress
            ther where Arrow keys Up,Down,Left,Right Up(+1) & Down(-1) control
            adress count and  Left(+1) & Right(-1) Position off edit cursor
            if cursor<DS0 then cursor=DS5 or if cursor>DS5 then cursor=DS0 
            (This i used flipFlops)

    * "My First One" have begin a bus because found in scrapyard a 19" case with a backplain and some card in there i remove card And backplain,
      put connectors in as i need then make my bus by hand all pins as i need it put more connectors in 
      The funny part afer "Electuur junior computer" come out i don't need to change mutch my bus and cards have same pin assignment this ment change 8 wires 1 power rail 
      I used same connector Din41612 A,C Not the Din411617 I want start use the hardware that "Electuur" goto make .
    
    * My kernel whas very small only handel basic function 
        "Get Keyboard Char" 
        "Put Display char" 
        "Typeing function" 
        "RS Get input" 
        "RS Put output"
        "Burn Eprom" 
        "Read Eprom"
        "Check Eprom"

    * Uses software from "Electuur" or other places don't know any more  

    * All programming i don on paper by hand and then type in on keyboard

    * I build on card program Eproms (old syle 18/21/25 volts) locate in D000 
      (i wish still have this card i can't remember how i build it i think i somelse plan)

  After i get VIC20 i make interfase to 19" Case and remove CPU-card and key-board because VIC20 can't play dead so only memory-card(some small change the adress and VIC20 have more memory)


"THE My-VONE-6502" 
===============================================================================
  I start building computer here under describe whatt i go or plan to uses .

    I have OLD 19" case and 3 Backboard for euro-bus pcb's the layout is made for Din-41612 row A,B,C 
    Pin assignment from "junior computer" Din41612 A,C rows connectors the B row for extend version extra adress space see Bus pin assignment (This will be made soon)
    The Main CPU-BOARD can have extends-board on in that connect the A0/A16 to A0/A16 But when 74612 extend-board is on ther you can adress many more memory for this use Iuses B row
    * "THE My-VONE-6502 KeyBoard"
        * Debug mode
        * CPU/Program Mode

    * CPU-Card 
        * THE My-VONE-6502 Kernel
        * Direct Flascard reader/writer
    
    *   VGA/HDMI output (The veraboard yes same as X16 this waiting on guy how make that board get back to me) 
    
    * Rom-Card
        *   Basic (same thing close to commodore basic)
        *   Pascal (hey i'm delphi programmer)
    
    * Ram-Card 
      * Unkow 
    
    *   Like connect a commdore flopie drive (sim version or real) 
    *   Via Card plain I.O

P.s.
===============================================================================
  I writing this as i remember it me because there not bit left from "My First One" i build only what remember 

  Please please forgive for spelling errors I have dyslexia from when whass born.

  If can use any of my stuff is oke but drop me a E-mail or somthing


Handy resouces
===============================================================================
  retro.hansotten.nl/6502-sbc/elektuur-junior/elektor-junior-literature/junior-dutch/
  www.retro-lab.nl/?p=618
