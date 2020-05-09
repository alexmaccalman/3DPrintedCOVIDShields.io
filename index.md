# 3D Printing COVID-19 Face Shield Instructions  
### The purpose of this website is to outline the steps needed to 3D print face shields for hospitals that need them during the pandemic crisis.
![Making Face Shields](/assests/mask.png)
  
## Step 1: Buy a 3D printer and materials.   
I brought a RepRap type 3D printer made by [Sovol on Amazon](https://www.amazon.com/dp/B07TMLJS8Z/ref=cm_sw_r_apa_i_YAZKEbT34FYV3)  

Other RepRap types include [Ender 3](https://www.amazon.com/Comgrow-Creality-Printer-Upgrade-Certified/dp/B07GYRQVYV) and [CR 10](https://www.amazon.com/Official-Creality-3D-Printer-12x12x15-5/dp/B07LG2K55Q/ref=sr_1_2?dchild=1&keywords=cr10+3d+printer&qid=1588033169&s=industrial&sr=1-2). There are many others.   

[Buy PLA filament](https://www.amazon.com/dp/B07R1SJCL6/ref=cm_sw_r_apa_i_xHZKEbFY30JT3)  

Buy transparent sheets: [UNV21010 - Universal Transparent Sheets](https://www.amazon.com/gp/product/B074QXD918/ref=ppx_yo_dt_b_asin_title_o00_s00?ie=UTF8&psc=1)  

(You may find other sites selling UNV21010 sheets that are cheaper than Amazon).  
## Step 2: Learn to print.  
[This video](https://www.youtube.com/watch?v=T-Z3GmM20JM) teaches you about setting up a printer and doing a first print job. 
[This video](https://www.youtube.com/watch?v=3LBTkLsjHGQ) goes into more detail on 3D printing with the tools used to create the software needed to print. Generally, Computer Aided Design Software designs 3D objects and slicing software sets up the printing parameters in a .stl file and converts to a .gcode file that is loaded onto the printer.  

## Step 3: Assemble printer and download the slicing software.    
If you have a Sovol, [this user manual](https://drive.google.com/file/d/1Jwcd8sjB3ZGyrze-Ci5c0DzP0ElAvcmj/view) was more helpful than the one that came with the box.   
Download the slicing software [Cura](https://ultimaker.com/software/ultimaker-cura).    

## Step 4: Print test objects. 
The Sovol printer came with an .stl file to test print a 3D XYZ cube. Once that works, try printing a toy boat that is a more complicated design. You can download the 3DBenchy.stl file for the boat [here](https://www.thingiverse.com/thing:763622/files). You will need to use the Cura software to convert .stl files into a .gcode file used by the printer.   

## Step 5: Print Mask Frames.
First print one mask frame. Download the .stl file for one frame [here]( https://github.com/alexmaccalman/3DPrintedCOVIDShields.io/raw/master/assests/1_letter_3-hole.stl
).    
Some of the printer settings are unique to the printer type, like the bed size and retraction settings. Some settings are unique to the object you are printing. For the frames, I used the printer settings in Cura shown in the figure below. The rest of the settings should be the defaults.
![Settings](/assests/settings.png)  

Once you can print one frame, try printing a stack of two to ensure the spacing between the them is correct. Download the .stl file for the two stack model [here]( https://github.com/alexmaccalman/3DPrintedCOVIDShields.io/raw/master/assests/2_stack_24mm.stl).  

[This video](https://www.youtube.com/watch?v=MHKBvk8IAc0) talks about how to design a mutli-layered stack of frames.  
When the bed is not level or the printer settings are off, you will encounter problems with the print job. The figure below show examples of a bad print job. Expect that this will happen.  
![Bad Printing](/assests/bad.png)

Once ready, use the 8 stack for production mode. Download the .stl file for the eight stack model [here]( https://github.com/alexmaccalman/3DPrintedCOVIDShields.io/raw/master/assests/8_stack_24mm.stl). The 8 stack takes approximatley 14 hours to print.     

Use a knife to split the frames into their individual pieces. Then using a standard 3 hole punch, create 3 holes in the transparent sheets and insert them onto the frames. If the frame is not even at the top, the transparent sheet will appear crooked. Move the frame so that it is even at the top to ensure the transparent sheet is straight.
![Assembling](/assests/assemble.png)  

There are several resources that allow anyone to find hospitals in need. Here is one website: [masksforheros](https://www.masksforheroes.com/)  

Other websites have designs for other equipment and bridge the need for medical equipment with 3D manufacturers.  
[NIH 3D Print Exchange](https://3dprint.nih.gov/)    
[America Makes](https://www.americamakes.us/statement-on-covid-19/)  

Thank you for your contributions.   
Alex MacCalman

