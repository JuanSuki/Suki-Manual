# How to upload product description?

## List of Products description and CSV file that can be uploaded on Vendors portal

| Product Upload Description                                                                                                         | CSV file Headers                                                                                          |
| ---------------------------------------------------------------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------------------- |
| [Basic Product Details](how-to-upload-product-description.md#basic-product-detail)                                                 | barcode, name, price                                                                                      |
| [Product Names](how-to-upload-product-description.md#product-names)                                                                | barcode, name                                                                                             |
| [Product Tags & Keywords](how-to-upload-product-description.md#product-tags-and-keywords)                                          | barcode, name, tags, keywords                                                                             |
| [Product Categories](how-to-upload-product-description.md#product-categories)                                                      | barcode, name, category, subcategory                                                                      |
| [Products with Alternate Barcode](how-to-upload-product-description.md#products-with-alternate-barcodes)                           | barcode, alt\_barcodes, name, price                                                                       |
| [Uploading Products with Wholesale Items (Wholesale Purchase)](how-to-upload-product-description.md#products-with-wholesale-items) | barcode, name, price, wholesale\_barcode, wholesale\_price, wholesale\_content\_quantity, wholesale\_unit |
| [Set Products as Inactive](https://docs.suki.io/#!vendors/pu\_uploadproducts.md#Set\_Products\_as\_Inactive)                       | barcode, name, price, status                                                                              |
| [Special Tags for Product Limit](https://docs.suki.io/#!vendors/pu\_uploadproducts.md#Special\_Tags\_for\_Product\_Limit)          | barcode, name, special\_tags                                                                              |

{% hint style="info" %}
Click the **Product Upload Description** for further guide on how to prepare the CSV file
{% endhint %}

## How to Upload Product CSV file?

**(1)** On the Menu Bar, Navigate to Admin > Uploads > Upload Products

**(2)** The Product Upload Modal will be displayed

**(3)** Press the Choose File button

**(4)** Navigate to the location of your CSV file and click Proceed

**(5)** Click OK to Upload your File

**(6)** A Notification will appear indicating that you have successfully Uploaded your Products

**(7)** Click OK to close the notification

<div>

<figure><img src="../../.gitbook/assets/1 Upload Product.png" alt=""><figcaption></figcaption></figure>

 

<figure><img src="../../.gitbook/assets/2 Upload Product.png" alt=""><figcaption></figcaption></figure>

</div>

{% hint style="info" %}
Click the image for larger view
{% endhint %}

## Product Details upload Guide

### Basic Product Detail

Barcode, Name and Price these are the minimum header requirements for a new product upload

#### **To Prepare the Product CSV File**

**(1)** Download the Sample Template CSV File [Here](https://docs.google.com/spreadsheets/d/1QNGs8E4O82r\_8KqVKg0CHX5-EnHN0WwOK8MyTVBM9GE/edit#gid=0\&range=A1)

**(2)** Open the file in Google Sheets and Navigate to the **BASIC PRODUCT DETAILS TAB**

**(3)** You will see some sample entries

**(4)** Replace the examples with your products

* Barcode
* Name
* Price

**(5)** Save the file in a CSV Format

**(6)** Click File > Download > Comma-separated values (.csv)

| barcode       | name                                    | price |
| ------------- | --------------------------------------- | ----- |
| 4800361379397 | NESTLE BEAR BRAND MILK ADULT PLUS 180GM | 82.00 |

{% hint style="success" %}
If the Branch Price List feature is **Activated**, To apply the changes to the **Whole Account**, make sure to upload the CSV file to the **Standard Price** option or else select your **Preferred Price List** option to apply it to the **Branch Level**.
{% endhint %}

{% hint style="info" %}
Check on[ **how to upload products**](how-to-upload-product-description.md#how-to-upload-product-csv-file)****
{% endhint %}

### Product Names

Barcode, NameThis section contains instructions on how to Upload descriptive product names for your products so that customer can easily recognize your product

#### **To Prepare the Product CSV File**

**(1)** Download the Sample Template CSV File [Here](https://docs.google.com/spreadsheets/d/1QNGs8E4O82r\_8KqVKg0CHX5-EnHN0WwOK8MyTVBM9GE/edit#gid=2136203737\&range=A1)

**(2)** Open the file in Google Sheets and Navigate to the **PRODUCT NAMES TAB**

**(3)** You will see some sample entries

**(4)** Replace the examples with your products

* Barcode
* Name
* Override Name _(This is used to update the name of the product when the barcode already exists at the database)_
* Lock Name _(This field is used to Lock the name so that the POS cannot override the product name if there is an Integration)_ (_1 - is Locked, 0 - not Locked)_

**(5)** Save the file in a CSV Format

**(6)** Click File > Download > Comma-separated values (.csv)

| barcode       | name                                    | is\_locked\_name |
| ------------- | --------------------------------------- | ---------------- |
| 4800361379397 | NESTLE BEAR BRAND MILK ADULT PLUS 180GM | 1                |

| barcode       | override\_name                          |
| ------------- | --------------------------------------- |
| 4800361379397 | NESTLE BEAR BRAND MILK ADULT PLUS 180GM |

{% hint style="success" %}
If the Branch Price List feature is **Activated**, To apply the changes to the **Whole Account**, make sure to upload the CSV file to the **Standard Price** option or else select your **Preferred Price List** option to apply it to the **Branch Level**.
{% endhint %}

{% hint style="info" %}
Check on[ **how to upload products**](how-to-upload-product-description.md#how-to-upload-product-csv-file)****
{% endhint %}

### Product tags and keywords

Barcode, Tags, Keywords

#### **To Prepare the Product CSV File**

**(1)** Download the Sample Template CSV File [Here](https://docs.google.com/spreadsheets/d/1QNGs8E4O82r\_8KqVKg0CHX5-EnHN0WwOK8MyTVBM9GE/edit#gid=1035090969\&range=A1)

**(2)** Open the file in Google Sheets and Navigate to the **TAGS & KEYWORDS TAB**

**(3)** You will see some sample entries

**(4)** Replace the examples with your products

* Barcode
* Name
* Tags
* Keywords

**(5)** Save the file in a CSV Format

**(6)** Click File > Download > Comma-separated values (.csv)

| barcode       | name                                    | tags             | keywords           |
| ------------- | --------------------------------------- | ---------------- | ------------------ |
| 4800361379397 | NESTLE BEAR BRAND MILK ADULT PLUS 180GM | MILK, ADULT MILK | NESTLE, BEAR BRAND |

{% hint style="success" %}
If the Branch Price List feature is **Activated**, To apply the changes to the **Whole Account**, make sure to upload the CSV file to the **Standard Price** option or else select your **Preferred Price List** option to apply it to the **Branch Level**.
{% endhint %}

{% hint style="info" %}
Check on[ **how to upload products**](how-to-upload-product-description.md#how-to-upload-product-csv-file)****
{% endhint %}

### Product Categories

Barcode, Name, Category

#### **To Prepare the Product CSV File**

**(1)** Download the Sample Template CSV File [Here](https://docs.google.com/spreadsheets/d/1QNGs8E4O82r\_8KqVKg0CHX5-EnHN0WwOK8MyTVBM9GE/edit#gid=1261037389\&range=A1)

**(2)** Open the file in Google Sheets and Navigate to the **CATEGORIES TAB**

**(3)** You will see some sample entries

**(4)** Replace the examples with your products

* Barcode
* Name
* Alternate Category
* Alternate Sub Category

**(5)** Save the file in a CSV Format

**(6)** Click File > Download > Comma-separated values (.csv)

| barcode       | name                                    | category | subcategory |
| ------------- | --------------------------------------- | -------- | ----------- |
| 4800361379397 | NESTLE BEAR BRAND MILK ADULT PLUS 180GM | MILK     | ADULT MILK  |

{% hint style="success" %}
If the Branch Price List feature is activated, To apply the changes to the **Whole Account**, make sure to upload the CSV file to the **Standard Price** Option
{% endhint %}

{% hint style="info" %}
Check on[ **how to upload products**](how-to-upload-product-description.md#how-to-upload-product-csv-file)****
{% endhint %}

### Products with Alternate Barcodes

Barcode, Alternate Barcode, Name, Price

#### **To Prepare the Product CSV File**

**(1)** Download the Sample Template CSV File [Here](https://docs.google.com/spreadsheets/d/1QNGs8E4O82r\_8KqVKg0CHX5-EnHN0WwOK8MyTVBM9GE/edit#gid=1760553948\&range=A1)

**(2)** Open the file in Google Sheets and Navigate to the **ALTERNATE BARCODES TAB**

**(3)** You will see some sample entries

**(4)** Replace the examples with your products

* Barcode
* Alternate Barcode
* Name
* Price

**(5)** Save the file in a CSV Format

**(6)** Click File > Download > Comma-separated values (.csv)

| barcode       | alt\_barcodes  | is\_locked\_name                        | price |
| ------------- | -------------- | --------------------------------------- | ----- |
| 4800361379397 | 48003613793970 | NESTLE BEAR BRAND MILK ADULT PLUS 180GM | 82.00 |

{% hint style="success" %}
If the Branch Price List feature is **Activated**, To apply the changes to the **Whole Account**, make sure to upload the CSV file to the **Standard Price** option or else select your **Preferred Price List** option to apply it to the **Branch Level**.
{% endhint %}

{% hint style="info" %}
Check on[ **how to upload products**](how-to-upload-product-description.md#how-to-upload-product-csv-file)****
{% endhint %}

### Products with Wholesale Items

Barcode, Name, Price, Wholesale Details

#### **To Prepare the Product CSV File**

**(1)** Download the Sample Template CSV File [Here](https://docs.google.com/spreadsheets/d/1QNGs8E4O82r\_8KqVKg0CHX5-EnHN0WwOK8MyTVBM9GE/edit#gid=495158673\&range=A1)

**(2)** Open the file in Google Sheets and Navigate to the **WHOLESALE ITEMS TAB**

**(3)** You will see some sample entries

**(4)** Replace the examples with your products

* Barcode
* Name
* Price
* Wholesale Barcode _(The vendor can upload three sets of wholesale product property)_
* Wholesale Price
* Wholesale Content Quantity
* Wholesale Unit

**(5)** Save the file in a CSV Format

**(6)** Click File > Download > Comma-separated values (.csv)

| barcode       | name                                    | price | wholesale\_barcode | wholesale\_price | wholesale\_content\_quantity | wholesale\_unit |
| ------------- | --------------------------------------- | ----- | ------------------ | ---------------- | ---------------------------- | --------------- |
| 4800361379397 | NESTLE BEAR BRAND MILK ADULT PLUS 180GM | 82.00 | 4800361379403      | 980              | 12                           | box             |

{% hint style="success" %}
If the Branch Price List feature is **Activated**, To apply the changes to the **Whole Account**, make sure to upload the CSV file to the **Standard Price** option or else select your **Preferred Price List** option to apply it to the **Branch Level**.
{% endhint %}

{% hint style="info" %}
Check on[ **how to upload products**](how-to-upload-product-description.md#how-to-upload-product-csv-file)****
{% endhint %}

### Set Products as Inactive

Barcode, Name, Price, Status

#### **To Prepare the Product CSV File**

**(1)** Download the Sample Template CSV File [Here](https://docs.google.com/spreadsheets/d/1QNGs8E4O82r\_8KqVKg0CHX5-EnHN0WwOK8MyTVBM9GE/edit#gid=502756565\&range=A1)

**(2)** Open the file in Google Sheets and Navigate to the **STATUS TAB**

**(3)** You will see some sample entries

**(4)** Replace the examples with your products

* Barcode
* Name
* Price
* Status _(I - Inactive, A - Active)_

**(5)** Save the file in a CSV Format

**(6)** Click File > Download > Comma-separated values (.csv)

| barcode       | name                                    | price | status |
| ------------- | --------------------------------------- | ----- | ------ |
| 4800361379397 | NESTLE BEAR BRAND MILK ADULT PLUS 180GM | 82.00 | I      |

{% hint style="success" %}
If the Branch Price List feature is **Activated**, To apply the changes to the **Whole Account**, make sure to upload the CSV file to the **Standard Price** option or else select your **Preferred Price List** option to apply it to the **Branch Level**.
{% endhint %}

{% hint style="info" %}
Check on[ **how to upload products**](how-to-upload-product-description.md#how-to-upload-product-csv-file)****
{% endhint %}

### Special Tags for Product Limit

Barcode, Special Tags

#### **To Prepare the Product CSV File**

**(1)** Download the Sample Template CSV File [Here](https://docs.google.com/spreadsheets/d/1QNGs8E4O82r\_8KqVKg0CHX5-EnHN0WwOK8MyTVBM9GE/edit#gid=1499195269\&range=A1)

**(2)** Open the file in Google Sheets and Navigate to the **SPECIAL TAGS TAB**

**(3)** You will see some sample entries

**(4)** Replace the examples with your products

* Barcode
* Name
* Special Tags

**(5)** Save the file in a CSV Format

**(6)** Click File > Download > Comma-separated values (.csv)

| barcode      | name                                                                | special\_tags |
| ------------ | ------------------------------------------------------------------- | ------------- |
| 480004782024 | GREEN CROSS ALCOHOL ISOPROPYL WITH MOISTURE LOCK 70% SOLUTION 150ML | ALCOHOL       |

{% hint style="success" %}
If the Branch Price List feature is **Activated**, To apply the changes to the **Whole Account**, make sure to upload the CSV file to the **Standard Price** option or else select your **Preferred Price List** option to apply it to the **Branch Level**.
{% endhint %}

{% hint style="info" %}
Check on[ **how to upload products**](how-to-upload-product-description.md#how-to-upload-product-csv-file)****
{% endhint %}
