# Arduino Clone
This project involves creating a microcontroller similar to the Arduino UNO. The design and implementation were based on the guidance provided by the Robert Feranec. The project includes PCB layout design using Altium Designer, soldering the components, checking the soldered connections, programming, and testing the microcontroller.

  
![Arduino Clone](https://github.com/user-attachments/assets/ef1879f8-106a-4f77-97d0-3fa135d964d2)

## Designing PCB layout and 3D model in Altium Designer

I developed the PCB layout design and the board's 3D model using Altium Designer. All necessary documents for circuit manufacturing have been uploaded to the repository. For guidance on creating the schematic and PCB layout, I followed Robert Feranec's instructional videos.

Link to the guide:
https://www.udemy.com/course/learn-to-design-your-own-boards


![3D_model_side](https://github.com/user-attachments/assets/1b55edcb-aaf1-433e-909e-a591001d5ce3)
<p align="center">
  3D model in Altium Designer
</p>









## Soldering the components

![Arduino Clone without components](https://github.com/user-attachments/assets/2be04e06-dffd-4367-baf8-fb202165b220)

<p align="center">
  PCB without components
</p>

After designing the PCB layout, I had the board manufactured by JLCPCB. I ordered the components from Digi-Key, which I soldered on the PCB by hand. For the soldering process, I used the following tools:
* Flux: EDSYN FL 22 R & Stannol 165018 F-SW 26
* Solder: STANNOL HF32
* Tweezers
* Soldering Station: Hakko FX888D
* Soldering Tip: Hakko T18-D24
* Desoldering Wire

(I worked with a soldering iron heated to 350 degrees Celsius.)

 ![tools](https://github.com/user-attachments/assets/a18f79c0-9cfc-4297-8dea-78d1f986ac8a)
<p align="center">
  Tools used
</p>

![Arduino Clone without connectors](https://github.com/user-attachments/assets/1b32d16d-f6b8-4050-adc0-0c11530b55bf)

I started with the soldering of the ATmega16U2 component, as it proved to be the most challenging. After soldering, I inspected the connections using a magnifying glass to check for any short circuits between the individual pins, followed by verification with a multimeter.

Next, I moved on to soldering smaller components, such as SOD-323 and 0603 size-code components. I used the following method for soldering these components:

1. I first applied a small amount of flux to one pad of the component.
2. Then, I placed solder on that pad.
3. After that, I applied more flux to the pad and soldered the component's corresponding lead on the pad where the solder had previously been applied.
4. Finally, I soldered the other lead(s) of the component.

To check if the component was properly soldered, I pushed one of its leads with the hot soldering iron tip. If the component did not move, it indicated that the other lead was secured, confirming that the connection had been made.

However, this method was not practical, because is some cases the solder mask came off during the pushing process.

After soldering all the components, I checked each soldered connection using a multimeter to ensure that all connections were properly made. Afterward, I soldered the connectors and checked them as well to ensure proper connections. Fortunately, all the soldered joints were correct, so no further adjustments were needed.

![Arduino Clone compared to Arduino UNO](https://github.com/user-attachments/assets/3747f3fa-b0d8-47f7-8aa0-9a67a52f108f)
<p align="center">
  Arduino Clone compared to Arduino UNO
</p>
