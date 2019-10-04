# Hentehylle
Group project in the course [IN1060 Use Oriented Design at the Department of Informatics, University of Oslo](https://www.uio.no/studier/emner/matnat/ifi/IN1060/), spring 2018 - grade: A.

Our task was to plan, implement and execute a project in which we
          designed and built a tangible digital prototype using Arduino and
          without the use of a screen, for a selected user group. We chose
          public libraries as the research domain and developed a digital
          prototype for the public libraries' existing shelf solution for
          retrieving reserved books. This involved to plan and conduct several
          types of usage context studies and to identify and formulate design
          requirements based on our own use studies. Furthermore we had to
          collaborate with users on design proposals, prototypes and evaluation
          throughout the entire design process, as well as characterize and
          evaluate what and how users have influenced in the design result. Click [here](https://www.uio.no/studier/emner/matnat/ifi/IN1060/v18/prosjekter-2018/spade/index.html) to read more about our project.

The prototype design is a standard shelf equipped with two RFID readers. One RFID reader is integrated into the bookshelf and reads the ID of the books, while the other RFID reader is integrated into a card reader that reads the RFID card ID. The card reader is equipped with a light which flashes green if the book is in the shelf and red if not. If the book is in the shelf and the correct loan card is registered, the shelf section where the book can be found will light up. 

Main components: 
- 3 x Arduino Uno. 
- 2 x MFRC522 RFID-readers. 
- 2 x RFID-cards. 
- 2 x powerbank. 
- Luxorparts Adressable RGB LED-list 5 m.
- NeoPixel Stick 8 - 8X 5050 RGB LED
- 2 x Electrolytic Capacitor.
- 2 x 220Ω resistor for RGB LED.

The code is written in the Arduino programming language.

