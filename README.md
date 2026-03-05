# Barnacle Board Rev 2

Rev 2 is gonna be quite a bit different from the original (from here on, I will refer to this as just **Barnacle Board**), LEDs are a separate board, and there are holes that go all the way through the breadboard (a cool side effect of having spring clips with holes for 5 LEDs), and the connector pinout is changed so you can plug stuff in the wrong way and it just swaps the top and bottom halves of the breadboard.

The idea here is to make an *a la carte* Jumperless, where you can both use this as a luxurious regular breadboard, or plug in a cople Barnacles and turn it into a full-on Jumperless. And you can stack them side-by-side to create the long-awaited full sized Jumperless. 

Or use the card edge connector to plug in other stuff, like solderable protoboards or SMD breakouts and have them mapped 1:1 with the breadboard.


Right now I'm just dumping stuff here. But these will be launching soon in my [store](https://shop.jumperless.org/)

![IMG_2591](https://github.com/user-attachments/assets/ce8eeeff-4704-4f76-bbc3-0a24cd25ade8)
![IMG_2592](https://github.com/user-attachments/assets/b56f9a4c-b306-452d-95a7-f34f68b119c3)
![IMG_2593](https://github.com/user-attachments/assets/6ff5c654-d0ce-4ece-95a3-a4828a121120)
![IMG_2594](https://github.com/user-attachments/assets/2147c7b2-27a4-4784-918b-756bfd216528)

![ws-1](https://github.com/user-attachments/assets/6513c78a-9c70-41fe-a45b-28dd6181bb21)
![ws-3](https://github.com/user-attachments/assets/989e80a4-54d9-4ea9-897d-aabdb40f9f79)
![ws-4](https://github.com/user-attachments/assets/8c985b33-47a5-4073-a6be-cdd71c1c6db9)
![barn-5](https://github.com/user-attachments/assets/5271995f-7d87-4dcd-ace6-dc54e89675ef)
![barn-6](https://github.com/user-attachments/assets/0ef41126-5555-4f31-8dcb-da8478fbf984)


<img width="2802" height="3356" alt="Proto" src="https://github.com/user-attachments/assets/d0747aea-1509-42fe-9cff-ffa93ace0150" />
<img width="2802" height="3356" alt="Proto9" src="https://github.com/user-attachments/assets/175f656b-2ce7-46a5-82ff-7bd829b2a522" />
<img width="2802" height="3356" alt="Proton9" src="https://github.com/user-attachments/assets/77a6ef40-e375-458a-b368-356fccd8add2" />

<img width="2482" height="1760" alt="BarnacleBoardback" src="https://github.com/user-attachments/assets/cfc375a5-27f2-4d0c-b530-f575938f7603" />










# Barnacle Board
###### an RGB'd out breadboard you can stick things to

The Barnacle Board is a half-size breadboard with RGB LEDs under each row and a 70-pin card edge connector at the top.

![TxRx00089](https://github.com/Architeuthis-Flux/Barnacle_Board/assets/20519442/a3bab266-83e3-4b2e-a942-23591e9d55d6)

This repo will contain all the various Barnacles I come up with. Feel free to submit a PR to add your own!

You can plug in (or stack multiple) Barnacles to do add new functionality to you breadboarding experience without cluttering the part your're working on.


The next few I'm working on are (in a vague chronological order):
 - Proto Barnacle - a cheap solderable protoboard that maps 1:1 to the breadboard ([done, shown here](https://kicanvas.org/?github=https://github.com/Architeuthis-Flux/Barnacle_Board/blob/main/ProtoBarnacle/ProtoBarnacle.kicad_pcb))
 - Sense Barnacle - a thing to continuously measure the voltage on every row and display it as a color/brightness on that row and on the built in OLED ([rough draft of the schematic is here](https://kicanvas.org/?github=https://github.com/Architeuthis-Flux/Barnacle_Board/blob/main/SenseBarnacle/SenseBarnacle.kicad_sch))
 - Dumb Barnacle - a very simple LED driver where row colors can be manually selected, and also a simple, selectable breadboard power supply
 - Internacle - a passive routing hub for multiple barnacles to pass connections between boards
 - SMD Barnacle - a bunch of SMD footprints, similar to the top part of a [Jumperlux](https://github.com/Architeuthis-Flux/JumperLUX) (this project is basically Jumperlux Rev 2 with a new name)
 - Professor Barnacle - wirelessly control the LEDs on any number (or subset of) of boards to help guide students through electronics labs
 - Nixie Barnacle - a nixie tube power supply and footprints for various nixie tube sockets
 - Jumperless Barnacle - a [Jumperless](https://github.com/Architeuthis-Flux/Jumperless) with an edge connector instead of an integrated breadboard





![TxRx00087](https://github.com/Architeuthis-Flux/Barnacle_Board/assets/20519442/a09d111b-5562-4daf-bbf6-17a57371504a)

If you think of any new ones that might be useful or if you disagree with the order I've put these in and think one should be prioritized, let me know!

Here's the spec for the edge connector in case you want to make your own Barnacles
![edgeConnectorScpecSmall](https://github.com/Architeuthis-Flux/Barnacle_Board/assets/20519442/753425f5-d782-427f-bf4b-7e35cc46b006)
