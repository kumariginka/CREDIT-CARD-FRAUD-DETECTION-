# CREDIT-CARD-FRAUD-DETECTION
## TABLE OF CONTENTS
* introduction
* problem satement
* data set for credit card fraud detection
* fraud detection
* technologies used
* modules
* system requirements
* fraud prevention tips
* conclusion and future scope
### INTRODUCTION
![image](https://user-images.githubusercontent.com/81427273/115814603-04651780-a413-11eb-9b5c-11840c0fc94b.png)

One of the major concerns for financial institutions is a fraud. As the number of transactions is increasing, it is also increasing the chances of fraud. But now, financial institutions can keep track of scams and frauds in a better way by using the analytical tools to analyze the big data.

Credit card fraud will remain at the top of the list of financial scams. There has been an improvement in the detection of these types of fraud because of the development of algorithms. Anomaly detection is much easier now with higher accuracy. The losses from the scams are promptly minimized by the detection alert received at real-time by the companies about the anomalies in financial purchases.

Unusual patterns in trading data are identified using various machine learning tools. Financial institutions are alerted, and the anomalies are taken for further investigation. There are many other types of fraud also which are detected by understanding the pattern of the data which seems to be suspicious and many insurance companies are using several clustering algorithms to segregate the data and understand the cluster pattern of information

### PROBLEM STATEMENT
The Credit Card Frayd Detection problem includes modeling Past Credit Card Transactions with the knowledge of the ones that turned out to be fraud. This model is then used to identify wheather a new transaction if fraudlent or not.

 #### CONTEXT
Due to card less transaction every people use ATM card and credit card for transaction, so fraud can also be increases.

Billions of dollars of loss are caused every year by fraudulent credit card transactions.the design of efficient fraud detection algorithms is key for reducing these losses.

#### DATA COLLECTION:
This dataset is collected from kaggle https://www.kaggle.com/kartik2112/fraud-detection

#### ABOUT DATASET
This is a simulated credit card transaction dataset containing legitimate and fraud transactions from the duration 1st Jan 2019 - 31st Dec 2020 in USA . It covers credit cards of 1000 customers (USA) doing transactions with a pool of 800 merchants.

#### Source of Simulation:
This was generated using Sparkov Data Generation | Github tool created by Brandon Harris. This simulation was run for the duration - 1 Jan 2019 to 31 Dec 2020. The files were combined and converted into a standard format.

#### EXPLANATION OF EACH FEATURE:
*    trans_date_trans_time : the transaction date and time of that customer
*    cc_num : the credit card number of each customer
*    merchant : A commercial entity or person authorized to accept cards and receive payments from its customers pursuant to agreement with the card brands.
*    category : type of category
*    amt : amount to be transfered in every transaction
*    first : first name of customer
*    last : last name of customer
*    gender : gender of card holder
*    street : address of card holder
*    city : city of card holder
*    state : state of card holder
*    job : designation of card holder
*    dob : date of birth of card holder
*    trans_num : transaction number
*    is_fraud : tells that transaction was fraud or not?
#### FRAUD DETECTION
fraud detection is the topic which is applicable to many industries including banking and financial sectors,insurances,government agencies, and more... through the use of sophisticated use of data mining tools, millions of transactions can be searched to spot patterns and detect fraudlent transaction fraud detection is the process of identifing fraudlent transactions

#### FRAUD DETECTION PROCESS:
![image](https://user-images.githubusercontent.com/81427273/115814930-a127b500-a413-11eb-8f53-aba3d18b5e12.png)

#### TECHNOLOGIES USED
####  MACHINE LEARNING
machine learning is set of techniques to make computers better at doing things that human can do better then machines
![image](https://user-images.githubusercontent.com/81427273/115815016-d0d6bd00-a413-11eb-806a-6cba66fdd379.png)
 #### SUPER VISED MACHINE LEARNING
![image](https://user-images.githubusercontent.com/81427273/115815799-41caa480-a415-11eb-8502-c3fab94f7706.png)
supervised machine learning the name tells that machiens works under the supervisor as a teacher in supervised machine learning ,the machine can treats as baby we train the machine by giving labelled data and makes the prediction according to the test data some of the super vised machine learning algorithems are: linear regression logistic regression and classifier support vectro machines decission trees k nearest neighbours naive bayes ensemble techniques: random forest ( bagging) xg boost (boosting)

UNSUPER VISED MACHINE LEARNING
![image](https://user-images.githubusercontent.com/81427273/115815525-b9e49a80-a414-11eb-8adb-55268a7aa397.png)
unsupervised machine learning acts as young child means, machine can learn things by its own so we can give unlabelled data to the machine ,the machine can able to predict the results eg: k clustering hirerarchical clustering dbscan

REINFORCEMENT MACHINE LEARNING
![image](https://user-images.githubusercontent.com/81427273/115815550-ca951080-a414-11eb-9212-051ca9b7a7b0.png)
reinforcement learning is an area of machine learning.it is about taking suitable action to maximize reward in a particular situation it is employed by various software and machines to find the best possible behaviour or path it should take in a specific situation

eg: if you put a person in space ,he just do trial and error for to sustain there environment and life style .... similarly machines are also same here for one particular allocated work they do trail and error methods to attains best results

MODULES
 MODULE1 :
  frame the problem
 MODULE 2:
 collect the raw data 
 eg:
 from kaggle
 from google dataset downloader
 MODULE3 :
 IMPORT LIBRARIES:
   PANDAS
   NUMPY
   SKLEARN
   MATPLOTLIB
   SEABORN
   ETC....
  MODULE4:
  process the data for analysis
  MODULE 5:
  train the model and make predictions
SYSTEM REQUIREMENTS
HARDWARE EQURIMENTS:
   RAM:4GB OR HIGHER
   PROCESSOR: INTEL I3 OR ABOVE
   HARD DISK: 500GB MIN
SOFTWARE REQUIREMENTS:
  OS: WINDOWS OR LINUX
  PYTHON IDE=PYTHON 2.7 OR ABOVE( LATEST VERSION OF  PYTHON 3.8)
  JUPYTER NOTEBOOK
  LANGUAGE:PYTHON
in windows 10 install ANACONDA and launch jupyter spyder etc.

the Code is written in Python 3.8. If you don't have Python installed you can find it here. If you are using a lower version of Python you can upgrade using the pip package, ensuring you have the latest version of pip. To install the required packages and libraries, run this command in the project directory after cloning the repository:

pip install -r requirements.txt

#### FRAUD PREVENTION TIPS
#### 1.Keep Your Credit Cards Safe
One of the simplest ways to avoid credit card fraud is by keeping your credit cards safe from thieves. Place your credit cards in a purse or wallet close to your body where it can't easily be snatched away.

If you're shopping in a high traffic area, carry a smaller purse because it's harder to steal or sneak into. For both men and women, carry only the one or two credit and debit cards you'll be using that day. Leave all your other credit cards at home.

Thieves can take pictures of your credit card with a camera or cell phone, so don't leave your credit card exposed any longer than necessary.

After you make a purchase put your credit card away immediately. Confirm you have your credit card back in your possession before you leave the store or restaurant.

#### 2.Shred Anything with Your Credit Card Number on It
Don't toss your credit card billing statements directly into the trash; they typically have your full credit card number printed on them. Shred them to keep dumpster divers from getting their hands on your credit card number. The same thing applies to old credit cards that have expired or been canceled.

You can go a step further and put the shredded pieces in different trash bags for the extra eager thieves who might put shredded pages back together.

#### 3.Avoid Giving out Your Credit Card Information
Only give your credit card number or other sensitive information on calls you initiate. Not only that, when you call your credit card issuer's customer service, use the number on the back of your credit card. Don't return calls to a phone number left on your answering machine or sent to you in an email or text message. It's hard to be sure a scammer hasn't left a fake number for you to call.

Don't give your credit card number to anyone who calls you requesting the number. Credit card thieves have been known to pose as credit card issuers and other businesses to trick you into giving out your credit card number.

#### 4.Be Safe with Your Credit Card Online
Don't click on email links from anyone that looks like your bank, credit card company, or other business who uses your personal information, even if the email looks legitimate. These links are often phishing scams and the scammers want to trick you into entering your login information on their fake website. Instead, go directly to that business's website to login to your account.

Make sure you're cautious when you're using your credit card online. Only enter your credit card number on secure websites that you can be 100% sure are legitimate. To be sure a website is secure, look for https:// in the address field and a padlock icon in the status or address bar of your internet browser. Taking these extra steps will help you avoid credit card fraud.

#### 5. Report Lost or Stolen Credit Cards Immediately
The sooner you report a missing credit card the sooner your credit card issuer can cancel your credit card and prevent fraudulent charges. Reporting your lost or stolen credit card as soon as possible lowers the likelihood that you'll have to pay for any fraudulent charges made on your credit card. Write down your credit card companies' customer service number now so you'll have them if your credit cards are ever missing.

#### 6.Review Your Billing Statements Each Month
Unauthorized charges on your credit card are the first sign of credit card fraud. If you notice a charge you didn't make, no matter how small, report the charge to your credit card issuer immediately. Your credit card issuer will tell you whether you should close your account and get a new account number to avoid credit card fraud.

#### 7.Make Strong Passwords and Keep Them Safe
Your credit card number may be stored in a number of places online. For example, you may save your credit card on Amazon so you can make one-click purchases. Make sure you use strong passwords with a combination of upper- and lower-case characters, numbers, and even characters, and avoid writing or sharing your password.

#### CONCLUSION AND FUTURE SCOPE
fraud detection system have become essential for banks and financial institutions ,to minimize their losses however, there are lack of published literature on credit card fraud detection techniques,due to the unavaliable credit card transaction dataset for researches we designed a system to detect fraud in credit card transactioin. this system is capable of providing most of the essential features required to detect fraudlent and legitimate transactions the dataset available on day to day prcessing may become outdated, it is necessary to have updated data for effective fraud behaviour identification
