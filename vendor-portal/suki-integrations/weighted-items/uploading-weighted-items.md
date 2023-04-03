---
description: This enables the vendor to upload weighted items as products
---

# Uploading Weighted Items

## To Prepare the Product CSV File

**(1)** Download the Sample Template CSV File [Here](https://docs.google.com/spreadsheets/d/1QNGs8E4O82r\_8KqVKg0CHX5-EnHN0WwOK8MyTVBM9GE/edit#gid=1008378241\&range=A1)

**(2)** Open the file in Google Sheets and Navigate to the **WEIGHTED ITEMS**

**(3)** You will see some sample entries

**(4)** Replace the examples with your products

* Barcode, Name, Price
* Approximate Weight
* Unit in Weight
* Price per Unit
* Variable

**(5)** Save the file in a CSV Format

**(6)** Click File > Download > Comma-separated values (.csv)

### Variable Price

* is the type of weighted item that change price depends on the weight of the item.
* It recalculates after entering the actual weight of the product.
* Having 1 the value of "variable" column indicates that the weighted item is variable price.

### Fixed Price

* unlike variable price, fixed price weighted item price will not recalculate. Fixed price weighted item value is 0 on "variable" column of CSV file.

| barcode | price | approx\_weight | unit\_in\_weight | price\_per\_unit | variable |
| ------- | ----- | -------------- | ---------------- | ---------------- | -------- |
| 77777   | 500   | 0.5            | KG               | 1000             | 1        |

## To Upload the Products

**(1)** On the Menu Bar, Navigate to Admin > Uploads > Upload Products

**(2)** The Product Upload Modal will be displayed

**(3)** Press the Choose File button

**(4)** Navigate to the location of your CSV file and click Proceed

**(5)** Click OK to Upload your File

**(6)** A Notification will appear indicating that you have successfully Uploaded your Products

**(7)** Click OK to close the notification

{% hint style="info" %}
Before Updating the Weighted Product, the Product record must already exist at the System's database
{% endhint %}

{% embed url="https://drive.google.com/file/d/1gwo1fXhv8OEkCMVqUfQ4-MGU4fvaTAk5/preview" %}
