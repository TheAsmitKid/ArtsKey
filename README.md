# ArtsKey   by BoyWhileCoding
[![ArtsKey](./files/icon.ico)](https://www.github.com/BoyWhileCoding/ArtsKey/)

[![Buymeacoffee](./files/bmc-button-yellow.png)](https://www.buymeacoffee.com/BoyWhileCoding)

ArtsKey: Easiest Image to ASCII Conversion Software

Artskey Converts images to ASCII art very accurately, the length of ASCII charaters in each line is given by the user as 'Image Clearance Level' which includes 5 levels i.e, [128,256,512,1024,2048]. For Live Image to ASCII Conversion(GUI) there is additional level '0.765625' i.e, [98]. For Live Image to ASCII Conversion(CLI) the level is automatically generated according to the number of columns of console
#
ArtsKey is programmed in [python](https://www.python.org).

![starting](https://user-images.githubusercontent.com/89507875/176726997-748142d1-abd2-4ddc-9491-95f8f17b38e0.png)

As the image shows, there are 5 available commands:

<table>
  <tr>
    <th>Command</th>
    <td>Usage</td>
  </tr>
  <tr>
    <th>gui</th>
    <td>Starts the Graphical User Interface for ASCII Conversion</td>
  </tr>
  <tr>
    <th>convert(or cvt)</th>
    <td>Starts Command Line Session for ASCII Conversion</td>
  </tr>
  <tr>
    <th>live convert, camera(or cam)</th>
    <td>Starts live ASCII to image convertion, shows it in the Command Prompt (Using camera)</td>
  </tr>
  <tr>
    <th>quit, exit, off(or bye)</th>
    <td>Exits the Application</td>
  </tr>
  <tr>
    <th>example(or ex)</th>
    <td>Converts Example Image into ASCII art</td>
  </tr>
</table>

![gui_a](https://user-images.githubusercontent.com/89507875/176729189-09dd8c7b-db78-412c-aa5b-ec5c81593cdf.png)

By Entering 'GUI', a new window pops up

![gui_b](https://user-images.githubusercontent.com/89507875/176729674-4ce83bc8-a7e4-4798-8510-e6ea42230120.png)

This is a custom tabbed window.
Now as you can there is a big black rectangle, followed by some text and buttons.

Now, we type 'example' in the 'Path to Image' entry as directed in the status box and click 'Select'. A notification comes saying

![gui_c](https://user-images.githubusercontent.com/89507875/176730858-56070640-e267-4fc8-9195-62c9b81b1d4e.png)

Now, we click 'Ok' followed by 'Done'.

![gui_d](https://user-images.githubusercontent.com/89507875/176732479-c023a4ca-a423-4476-96e6-cb7f1e74f7c1.png)

This time a photo pops up into the black box, which is the example image, and the Image Path entry changes to {The path to ArtsKey.exe}/files/example_input.png which is generated by the program.
As the default Image Clearance Level is already set to 2, we'll leave it as it is and click 'Generate'.

![gui_e](https://user-images.githubusercontent.com/89507875/176733321-902d5243-23ba-49a7-9a2e-f94f029861bc.png)

After a few moments the Image Path entry is empty and the statusbox says 'Done', which depicts that the Conversion is sucessful

![result_lvl_2](./files/results/example_ascii_art_level_2.png)

Now, we open {The path to ArtsKey.exe}/files/results/, there is a new file named 'example_ascii_art_level_2.png'

![gui_f](https://user-images.githubusercontent.com/89507875/176830900-43530ff5-bac1-48df-a5b7-e3c9a187782b.png)

When we click the second Tab 'ArtsKey Camera', the the contents changes, a bigger black box appears with the level options.
This box contains live converted ASCII art. The level '0.765625' shows the Image-less conversion at 98px/line, because there is no image process involved, the conversion is ~90% faster than other levels.

![gui_g](https://user-images.githubusercontent.com/89507875/176831356-5822a506-05cd-458a-a569-a918b324a244.png)

The Third and the lase tab, with title "Created By BoyWhileCoding" displays the release notes and my BMC and Github links

![cli_a](https://user-images.githubusercontent.com/89507875/176835805-8136c9ab-1b87-49d2-9e8d-22f81b60c74b.png)

CLI: The second command in CLI is 'convert', which Takes 'Path to image', 'Image Clearance Level' and choice to create ASCII Image or the ASCII HTML page.
When the conversion is complete, we get '[Debug]> Done' as debug, the result image and HTML page is stored in {The path to ArtsKey.exe}/files/results/.

![image.tests.png result](./files/results/image.tests_ascii_art_level_2.png)
[image.tests.html result](./files/results/image.tests_ascii_art_level_2.html)

CLI: The Third command in CLI is 'live convert'(or convert live) or 'camera'. It starts a command line camera session.

![cli_b](https://user-images.githubusercontent.com/89507875/176835922-6a2dbbbe-41a8-49d6-8457-67ab5d20e519.png)

We get a Note, saying to press ctrl+c to end the camera session.

![cli_c](https://user-images.githubusercontent.com/89507875/176835941-f0080036-f3bc-4897-a20a-6cddf0306e1f.png)

After a few seconds the art shows up, updates at ~16fps.
Result: Constantly captures pictures from the user's camera, then convert it into ASCII art, and displays it into the command prompt(Image-less).

![cli_d](https://user-images.githubusercontent.com/89507875/176835959-dde90b74-e06b-4d31-b7eb-97f0273e4dba.png)

The moment we click ctrl+c, the image disappears, we get '[Debug]> Session ended' as debug.

CLI: The fifth command converts example image to ASCII art, to the levels given by user.
![cli_e](https://user-images.githubusercontent.com/89507875/176836051-21b2b22e-2f5c-4d63-bb48-4cb093736a60.png)

CLI: The fourth command exits the program

Releases:
<table>
  <tr>
    <th>Version</th>
    <td>1.4.0'1.0.0</td>
  </tr>
  <tr>
    <th>Link
    <td>https://github.com/BoyWhileCoding/ArtsKey/releases/tag/1.4.0</td>
  </tr>
</table>

Support me:
[![Buymeacoffee](./files/bmc-button-yellow.png)](https://www.buymeacoffee.com/BoyWhileCoding)
