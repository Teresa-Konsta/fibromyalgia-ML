## ML for Fibromyalgia diagnostics
I have been living with this hard syndrome my entire life.
First, I had to diagnose myself by myself, then I had to figure out the treatment.
I share my experience, treatment and hyposesis here https://muscle-spasms.vercel.app

My idea lies in creating a device with electrodes to check the patient's muscles in fibromyalgia spots for the next parameters: temperature in tissues, tension, sensitivity and pain level based on neuro impulses. For this project I have created a dataset based on my experience, that would serve for an ML model to estimate the fibromyalgia probability based on the pain level in certain body areas. Numbers in the dataset correspond to:

9 - maximum severe pain

8 - very severe pain

7 - severe pain

6 - medium to severe pain

5 - medium pain

4 - light to medium pain

3 - light pain

2 - very light pain

1 - no pain

I decided to set 1 as a starting point to avoid any null confusion by the machine. I use a random forest classification model as it gives the most precise results and I think its algorithm is the most suitable for this case. The model evaluates input with a 67% probability. It is a difficult syndrome, not learned to the fullest extent, and at the moment no diagnostic device exists in this world. So, I believe it is a good indicator for the start.
