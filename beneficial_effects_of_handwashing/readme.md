### Background on the Hand-Washing Analysis Project
This is my first project in the process of learning Python and data analytics using Python libraries.

I had learned about Dr. Semmelweis in a school science exhibition and I became very interested in his pioneering work in the use of antiseptic procedures for the treatment of postpartum infections in the early 19th century.

Hand-washing was not practiced by doctors treating mothers in the maternity wards of hospitals. This resulted in bacterial infections to both the mother and the baby and caused too much suffering and fatalities.

Dr. Semmelweis showed that washing hands prior to any maternity procedure would save lives, and he became a vocal proponent of the idea. 

As the hand-washing practice spread to hospitals in Europe the incidents of child bed fever and fatalities dropped significantly.

You can read more about Dr. Semmelweis here: https://en.wikipedia.org/wiki/Ignaz_Semmelweis

### About the data used in this project

The data simulates a hospital situation similar to the one Dr. Semmelweis worked in, in Vienna. 

There were 2 maternity clinics - Clinic 1 and Clinic 2.

He observed that the incidents of child bed fever was significantly higher in Clinic 1 compared to Clinic 2.

After a careful analysis, he noticed that the vast number of nurses working in Clinic 1 also worked on postmortem of corpses in the autopsy room.

The nurses did not wash hands after working on corpses and would then treat pregnant mothers in Clinic 1 thus bringing their infected hands from corpse handling to the birthing mothers.

However, the nurses in Clinic 2 worked exclusively in the maternity ward.

There are 2 datafiles -
1. monthly_deaths.csv ---> This file has the date, the number of births, and the number of deaths
2. yearly_deaths_by_clinic.csv ---> This file has the date, the number of births, the number of deaths, and the name of the Clinic.

### How to install and run the project

1. Make sure Python 3 is installed and works fine on your machine.
2. Create a Python virtual env
   `python -mvenv venv`
3. Activate the virtual env
    `source venv/bin/activate` ---> This an example for MacOS
4. Use pip to install the requirements.txt file
   `pip install -r requirements.txt`
5. Run the commands in the Jupyter notebook - *handwashing.ipynb*


