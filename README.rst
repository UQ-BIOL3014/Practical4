BIOL3014/BINF700 Practical 4: Bioimaging introductory training
================================================

* Due: 11 AM Wednesday 02/09/2015
* Revision: 1
* Marks: BIOL3014 - 8 marks total. BINF7000 - 12 marks total.

Important!
------------------
This practical has many images embedded in the notebook, demonstrating 
commands and expected results. These images may not render properly if 
you are using Canopy or Anaconda. If you see lots of ? in boxes instead 
of images, open the IPython file in your web browser using the GitHub 
link:
https://github.com/UQ-BIOL3014/Practical4/blob/master/notebook/BIOL3014_Prac4_2015.ipynb
The images should now display properly.


Bioimaging introductory training
------------------

This practical familiarises you with general applications of bioimaging
techniques. You will implement bioinformatics software to process and 
analyse image data to solve frequent biological questions. You will also 
use basic python scripts to plot results.

Instructions
------------

**We expect this practical to be performed on the UQ ILC computers using the 
OSX Yosemite image.**

In Practical 1 you installed the IPython notebook tool. Once you have logged 
into the ILC computer you need to tell Python where to find the previous 
install of the IPython notebook tool. In the *terminal application*, execute 
the following commands:

    export PYTHONPATH=$PYTHONPATH:/Users/local_user/Library/Python/2.7/ib/python/site-packages/
    export PATH=$PATH:/Users/local_user/Library/Python/2.7/bin/

This practical does **not** use the uqbinfpy Python library, therefore you do
not need to fetch the latest version.

Finally, the IPython Notebook for Practical 4 and all associated data can be 
downloaded using the following commands::
    
    cd ~/BIOL3014
    git clone https://github.com/UQ-BIOL3014/Practical4
    cd Practical4/notebook
    ipython notebook

Both the BIOL3014 and the BINF7000 practicals are in the same file
(BIOL3014_Prac4_2015.ipynb), however, undergraduates should only 
complete Part I.


Submission Requirements
-----------------------

Please submit your IPython Notebook with the completed code blocks and 
written answers where requested via the BIOL3014/BINF7000 Blackboard 
submission system. Use the format *STUDENT_NUMBER_P4.ipynb*. Detailed 
instructions are provided at the start of Practical 1.

Late submissions without sufficient reason will incur a 20% loss of the total 
score per late day.