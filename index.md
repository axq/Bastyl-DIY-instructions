## How to use this guide

The DIY kit is currently in beta. This guide is meant to help you go
through a build. You can click on the pictures to look at a full-res
version of them

## Kit contents

Before beginning, please check that your kit has all the elements you will need. Should something be missing, please contact us immediately. 

Use the kit paper you got with your order.

## Required tools and material


You will need to buy yourself :

- 1 Usb-C cable
- 1 Standard audio cable

To build this keyboard, you will need:

- Soldering iron
- M4 torx or flathead screwdriver
- Soldering tin
- (Optional) Wire stripper
- (Optional) Hot glue gun
- (Optional) Heat gun

## Screw inserts

There are 12 screw inserts to install, 6 on each side of the keyboard

- Set your soldering iron temperature to 300 degrees if you can.
- Using the soldering iron, place the heated insert inside the hole
- *Apply little to no pressure, let the gravity do the work*. Otherwise, you might push them too far
- Once the insert is 2/3 of the way in, stop 
- Flip over the case and push it against a flat surface, to make the insert flush with the case

![Figure 2](https://github.com/HID-Technologies/Bastyl-DIY-instructions/blob/gh-pages/images/insert3.PNG)

## Diodes and cables

**Pay attention to the orientation of the PCBs: you need two "right", and two "left"**

- Solder all the diodes on the four PCBs (flexyls and thumb clusters)
- Check the orientation of the diodes: use the indications on the PCB

## Ribbon cables

Cut the ribbon cables using scissors or a cutter:

- 4 * ribbons of 6 cables
- 2 * ribbons of 5 cables

- Solder the 6-cable ribbon cables on the thumb cluster PCB
- Solder the other end on the flexyl PCB, at the bottom - **make sure the legends align !** C5 should be connected to C5, C6 to C6, and so on
- Solder the 6-cable ribbon cable to the bottom part of the top connector of the Flexyl - R4 to R5
- Solder the 5-cable ribbon cable to the top part of the top connector of the Flexyl - C3 to R2


- Solder the 5-cable ribbon to the right part of the MCU. **Use the table under** to double-check the correct orientation
- **Make sure the cable is coming out of the top part of the MCU** (with the components). Look at the picture to double-check

| MCU  | Flexyl PCB |
| ------------- | ------------- |
| C6 | C3  |
| D7  | R1  |
| E6  |  C2 |
| B4  | C1  |
| B5  | R2  |


- Solder the 6-cable ribbon to the left part of the MCU. **Use the table under** to double-check the correct orientation
- **Make sure the cable is coming out of the top part of the MCU** (with the components). Look at the picture to double-check

| MCU  | Flexyl PCB |
| ------------- | ------------- |
| F5 | R4  |
| F7  | R3  |
| B1  |  C4 |
| B3  | C5  |
| B2  | C6  |
| B6  | R5  |


![Figure 2](https://github.com/HID-Technologies/Bastyl-DIY-instructions/blob/gh-pages/images/cab.PNG)



## Installing the switches

**Carefully install the switches in the specified order, using the pictures for help**

- Insert the assembled PCBs into the case
- Starting with the top row, install the two switches in the middle columns and solder them
- Then, install the two switches around it. You will have to push the PCB so it aligns, and then insert the switches. This is by design, and once the switches inserted the PCB won't move. Solder these switches
- Finish the top row
- Do the bottom row in the same way. The PCB won't hold on the switches, you can hold it with the soldering iron and then add the tin
- Finish the top part of the keyboard
- Install the switches on the thumb cluster


![Figure 2](./images/mont1.jpg)




## Welcome to GitHub Pages

You can use the [editor on GitHub](https://github.com/HID-Technologies/Bastyl-DIY-cinstructions/edit/gh-pages/index.md) to maintain and preview the content for your website in Markdown files.

Whenever you commit to this repository, GitHub Pages will run [Jekyll](https://jekyllrb.com/) to rebuild the pages in your site, from the content in your Markdown files.

### Markdown

Markdown is a lightweight and easy-to-use syntax for styling your writing. It includes conventions for

```markdown
Syntax highlighted code block

# Header 1
## Header 2
### Header 3

- Bulleted
- List

1. Numbered
2. List

**Bold** and _Italic_ and `Code` text

[Link](url) and ![Image](src)
```

For more details see [GitHub Flavored Markdown](https://guides.github.com/features/mastering-markdown/).

### Jekyll Themes

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/HID-Technologies/Bastyl-DIY-cinstructions/settings). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://docs.github.com/categories/github-pages-basics/) or [contact support](https://github.com/contact) and we’ll help you sort it out.
