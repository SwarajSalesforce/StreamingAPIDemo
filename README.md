# Subscribe to and Replay Events Using a Java Client

## Step 1: Create an Object
The first step is to create an InvoiceStatement object.

After you create a PushTopic and subscribe to it, you’ll get notifications when an InvoiceStatement record is created, updated, deleted, or undeleted. You’ll create the object with the user interface.

1. From your management settings for custom objects, if you’re using Salesforce Classic, click New Custom Object, or if you’re using   Lightning Experience, select Create | Custom Object. 
Define the custom object.
In the Label field, type Invoice Statement.
In the Plural Label field, type Invoice Statements.
Select Starts with vowel sound.
In the Record Name field , type Invoice Number.
In the Data Type field , select Auto Number. 
In the Display Format field, type INV-{0000}.
In the Starting Number field, type 1.
Click Save.

Add a Status field.
Scroll down to the Custom Fields & Relationships related list and click New.
For Data Type, select Picklist and click Next.
In the Field Label field, type Status.
Type the following picklist values in the box provided, with each entry on its own line.
1
Open
2
Closed
3
Negotiating
4
Pending
Select the checkbox for Use first value as default value.
Click Next.
For field-level security, select Read Only and then click Next.
Click Save & New to save this field and create a new one.
Now create an optional Description field.
In the Data Type field, select Text Area and click Next.
In the Field Label and Field Name fields, enter Description.
Click Next, accept the defaults, and click Next again.
Click Save to go the detail page for the Invoice Statement object.
Your InvoiceStatement object should now have two custom fields.
