# Selling Test Kits to Clinics 
**Background:**  
  
A fictional company called Einfach Medical Supplies (EMS) sells a disposable testing device that primary care medical clinics (i.e., “family doctors”) use to test for a fictional disease called Frog Throat. There are a number of competitors to EMS selling similar products. EMS believes they have the best product in the market and that doctors will buy if they can get the clinic to hear their pitch. The big challenge, though, is getting past the first few moments of trying to pitch the product when they first visit a clinic. If they are successful, the sales people might be invited in right then to give a full pitch of the product to the doctors and nurse practitioners in the clinic. They might also be able to schedule a follow up visit to come back and give the pitch. Often, though, they are turned away when they first arrive and told the clinic already has a Frog Throat Testing supplier that they are happy with.  
  
EMS has just moved into a new region of the country and are trying to expand their business. Their sales force works out of offices in a few different cities. The sales people have been assigned clinics to visit and try to land sales.   
  
In their initial expansion regions, EMS has had sales people use a script for their opening pitch to the clinic that emphasizes the cost savings of their product over alternatives. Recently some of the sales force has suggested that it might be better to lead with a pitch other than the “cost angle”. They propose either a) leading first with the point that their product is much easier for the medical staff to use or b) their product leads to fewer contaminated samples and a lower error rate.   
  
The company has just hired a director of analytics and she proposed systematically testing whether different opening pitches have different effects on conversion of clinics by using a randomized controlled design. So in this new region the company took the clinics and randomized them into three groups: a) Control that received the original “cost-focused” pitch, b) Treatment 1 that received the “easier to use” pitch and c) Treatment 2 that received the “fewer errors” pitch. When the sales team goes out to visit a clinic they see the pitch that was randomly selected for that clinic on their work iPad.  
  
The file “clinicsales.csv” available on the course site has the results of the experiment. Here is a list of the variables:  
  
* clinicnumber: The id of the clinic. These were randomly assigned and have no underlying meaning.  
* numdoctors: The number of doctors working at the clinic  
* avgpanelsize: An estimate of the average number of patients each of the doctors at this clinic has in their panel. These are patients who list the doctor as their primary care physician.   
* distance: The distance (in miles) between the clinic and the sales office assigned to pitch that clinic.   
* treatment: Takes value 0 for control, 1 for Treatment 1, 2 for Treatment 2  
* purchase: Takes a value of 0 if the clinic declined to purchase test kits from EMS and 1 if they did purchase test kits from EMS. 
