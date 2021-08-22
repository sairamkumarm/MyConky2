# MyConky
This is my new conky config file

![Conkyone](https://user-images.githubusercontent.com/88662373/128711092-239cbbac-bcf2-4d52-aac9-4cdc7dbd17c8.png)
Dock not included

### **Prerequisites**

* Git set up in you computer
* Basic know-how of linux(prevents confusion)

## **Set Up**

### **Preperation**

1. Clone repo into a directory of your choice 
    * If you're new to all this then create a directory for you cloned repositories(or put in the downloads folder)
    * The directory you are in before cloning the repo(in the terminal) is the directory where the repository clones 
    * so for the sake of this tutorial move into the downloads folder `cd /Downloads/`
    * Then use `git clone <link>` the link to this repo is under 'code'(It's a green button next to about)

1. Install conky-all (available in more system repositories)
   * **BONUS TIP**(for apt package manager)
   * To check whether a package is available in the official repo use `apt search <keywords>`

1. Install all the fonts included, I recomend using a font manager for faster installs in the future

1. Create a new directory called **.conky** at `$HOME or ~/` (aliases for /home/username/)

1. Create a new folder in ~/.conky (say conky1) and copy the conkyrc files(both) and the conkystart.sh into it

If you have been folowing along, you should now have the following
* **MyConky2** that you cloned in a directory of your choice
* The included **fonts** (EarthOrbiter and UnitedKingdom) installed 
* A **~/.conky/conky1** directory with .conkyrc1, .conkyrc2 and conkystart.sh  

### **Configuration**

#### **conkyrc files**

1.Now we edit the conkyrc files

  a. Change the **minimum_size**, **maximum_width**, **maximum_height** values to match you screen size
  b. Change the **<network_name>** in the code to match your network name
     you can find you network name by using `ip link show`
  c. You will find pieces of code resembling `${font EarthOrbiter:size=8}` with nothing after them.
     When I was messing around I found that the size you put in said code can change the size of the spaces between lines in the conky. 
     So if you need things from different conkys to align when they are already as close as possible, just change the size of the spaces on one of the conkyrc files
  
  
  

## Thank you for visiting
