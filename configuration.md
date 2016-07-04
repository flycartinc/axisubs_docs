# Configuration

The configuration page has 2 tabs. Each one is explained below in detail. They are:
* **Configurations**
* **Currency and Tax**

<a name="Configurations"></a>
## Configurations


* ***Address, City***

    The address and city of the store is not mandatory. You can enter an address or simply leave the fields empty.
    
* ***ZIP/Postal code***

    Enter a valid postal code. This field can not be empty.
    

Check the image below to understand how to enter address, city, zip/ postal code and date time format.

![Store Configuration](./assets/images/configurations.png)
    
* ***Country Name***

    Name of the country should be selected from the given list. This field can not be empty.

* ***Zone Name***

    Name of the zone in the country. To be selected from the given list.
    
* ***Date time format***

    Here one can choose the display format of date from several [available options](http://php.net/manual/en/datetime.formats.date.php).

    
<a name="Currency and Tax"></a>
## Currency and Tax

An important area. Please think twice before you configure. Read the description carefully while configuring the following options.

* ***Default Currency***

    The currency that has been a legal tender in the country. To be selected from the given list.

* ***Auto Update Currency***

    Setting this option to *Yes* will automatically update the latest exchange values for the currency that is being dealt with. For e.g., the daily exchange values of INR against US $ will be updated automatically.
    

 * ***Enable Tax***
 
     Set this to **YES** will include the taxes for the or it will exclude tax for the plan.


* ***Prices Entered with tax***

    This is a very important option which deserves careful attention when entering the price of a product. The two options are:
    1. ***Yes***, I will enter prices inclusive of tax
    2. ***No***, I will enter prices exclusive of tax

* ***Price Display Options***

    Price of a product can be displayed in three formats.
     1. Only the price of the plan.
     2. Price inclusive of relevant tax, as a single figure.
     3. Price and Tax separately.

* ***Display tax information below the prices***

     Set this to **YES** will display (Incl.19% tax) or (excl.19% tax) to plan.
     
Check the image below to understand how to enable tax and currency .
     
![](./assets/images/currency and tax.png)