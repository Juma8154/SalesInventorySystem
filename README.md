# SalesInventorySystem
# FACULTY OF INFORMATION COMMUNICATION aAND TECHNOLOGY
# TEST PLAN FOR: ZETECH UNIVERSITY CANTEEN POINT OF SALE SYSTEM
# BY
# NAME: JUMA W CLARENCE
# REG NUMBER: DIT-02-8154/2020

# SUBMITTED TO:
 # FELIX WERU

# Table of Contents

# 1.0INTRODUCTION
# 1.1Goals and Objectives
This test plan describes the testing approach and overall framework that will drive the testing of the ZETECH UNIVERSITY CANTEEN POS SYSTEM. The objective of the test is to verify that the functionality of ZETECHU CANTEEN POS works according to the specifications. The test will execute and verify the test scripts, identify, fix and retest all high and medium severity defects per the entrance criteria, prioritize lower severity defects for future fixing.
# 1.2Statement Of Scope

The scope of this project is to test the functionality of the ZETECH_U Canteen POS system. 
The following items will be tested.
1.Terminal. Terminal is the main screen which is used to enter the details of the transaction. Terminal Testing requires validation to ensure that the devices are connected to the network and that the latest OS is running on it to support the POS app.
2.Display pole. Display Pole is the device which displays the item price once the product is scanned using the bar-code scanner. 
3.Cash register. Cash Register is used to storing Cash. For any cash transaction, the cash register opens immediately for cashiers to accept the cash from the customer and also return the balance amount if any. Testing can be done by selecting payment mode as Cash, and doing cash transaction with a refund amount.
4.Receipt printer. Printers are connected to each of the terminals and are called as register printers, these are used to generate the receipt after each transaction.
5.User interfaces. Are graphical interfaces visible by users while interacting with the system. Testing them helps to verify they are clear and eye catching to attract users or get their attention.
6.Uninterrupted power supply. It provides power to the system in case of a sudden power surge. Testing helps to verify f its working effectively according to its purpose.




# 1.3Major constraints

Skill set to plan and conduct performance testing is not adequately available.It is a late activity, and duration available for testing is not adequate.
Production environment cannot be simulated as it requires investments. A subdued environment may not produce the relevant results.
Testing is a complex and time consuming activity.
The testing process should start from the requirements collection phase itself.
Performance testing requires simulating several concurrent users. This requires automated tools which are expensive.


# 2.0Test Plan
# 2.1Software (SCIis) to be tested
ZETECH UNIVERSITY CANTEEN POINT OF SALE SYSTEM IS THE SOFTWARE TO BE TESTED IN THIS CASE.
# 2.2Testing strategy
# 2.2.1Unit testing.
Report testing
Security and regulatory compliance
Tracking customer data
Performance
Sales
Cashier activity
# 2.2.2Integration testing
Testing on windows 7 environment
Testing on windows 8 environment
Testing on windows 10 environment.
# 2.2.3Validation testing
User manual
User friendliness
Report/inventory testing.
Backup testing
# 2.2.4High-order testing
This is performed to
 evaluate the compliance of the system with the corresponding requirements.
# 2.3Testing resources and staffing
# 2.4Test work products


# 2.5Test record keeping
The test recorder in POS helps significantly reduce the time and cost of UAT. UAT is typically required before a Microsoft application update is applied, or before custom code and configurations are applied to your POS production environments. The test recorder can record user actions in the client, and it provides exact fidelity for all controls and for all elements in the Document Object Model (DOM)
# 2.6Test metrics
# 2.7Testing tools and environment
# 2.8Test schedule
# 3.0Test Procedure
# 3.1Software (SCIis) to be tested
# 3.2Testing procedure
# 3.2.1Unit test cases
Test scenario 1: Cashier activity
Test the entry of items purchased by a customer is correct
Test discounts are applied correctly
Verify store value cards can be used
Check petty cash management works as expected
Check totals and closings match
Check cash drawer loans are handled properly
Test the POS system is compatible with peripherals like RFID Reader, Bar Code Scanner etc.
Test scenario 2: Sales activity
Check for a regular sale process
Check sales can be processed with debit/credit cards
Check for loyalty membership purchase
Check for correct prices are displayed for merchandise purchased
Test for "0" or null transaction
Tie UPC or bar-codes to vendors
Test for billing details or shipping details in payment manager
Test for reference transaction
Test the print format of the receipt generated
Verify that the correct code is generated for approved, hold or declined transactions
Test scenario 3: Return & exchange
Verify system display both the current amount as well as the discount amount on an exchange of item if applicable
Check system process the sale with receipt or without a receipt
Verify that system should allow entering bar-code manually in case scanner don't work

Test scenario 4: Performance
Check for speed or time taken to receive a response or send a request
Check the transaction based rules are applicable (discounts/tax/ rebates etc.)
Verify that the correct code is generated for approved, hold or declined transactions
Test scenario 5: Negative scenarios

Check the inventory by entering a wrong code for the item
Check how a system responds while entering a wrong invoice number
Test for a negative transaction
Test the response of system while entering an invalid date for promotional offers online items
	Test scenario 6: Tracking customer data
Test for system response with incorrect customer data input
Test system for allowing authorized access to customer's confidential data
Test the database for recording customer's buying history like (what they buy, how frequent they buy, etc.)
Test scenario 7: Security & regulatory Compliance
Verifying POS system as per regulatory compliance
Test alert system that notifies security defenders
Make sure you can void a payment before posting
Test user profiles and access levels on the POS Software
Test database consistency
Verify specific information about each tender cash, coupon identifier, check number and so on
Test scenario 8: Report testing
Testing of a trend analysis report
Test information related to credit card transaction should be reflected in reports
Test for the individual as well as consolidated reports of customers buying history
Test for online report generation








# 3.2.1.2 Stubs and / or drivers for component i
# 3.2.1.3 Test cases component i
# 3.2.1.4 Purpose of tests for component 1
# 3.2.1.5 Expected results for component i

# 3.2.2Integration testing
# 3.2.2.1 Testing procedure for integration 
# 3.2.2.2 Stubs and drivers required 
# 3.2.2.3 Test cases and their purpose 
# 3.2.2.4 Expected results 
# 3.2.3 Validation testing

# 3.2.3.1 Testing procedure for validation 
# 3.2.3.3 Expected results 
# 3.2.3.4 Pass/fail criterion for all validation tests
# 3.2.4 High order testing (a.k.a System testing)
# 3.2.4.1 Recovery testing 
Make sure back up plans are working effectively to avoid data loss.
# 3.2.4.2 Security testing 
Verifying POS system as per regulatory compliance
Test alert system that notifies security defenders
Make sure you can void a payment before posting
Test user profiles and access levels on the POS Software
Test database consistency
Verify specific information about each tender cash, coupon identifier, check number and so on

# 3.2.4.3 Stress testing
Verify the flexibility and stability of the program allows it to handle overloads by running the program many times by clicking on its application shortcut.
 # 3.2.4.4 Performance testing 
Check for speed or time taken to receive a response or send a request
Check the transaction based rules are applicable (discounts/tax/ rebates etc.)
Verify that the correct code is generated for approved, hold or declined transactions

# 3.2.4.5 Alpha/beta testing 
# 3.2.4.6 Pass/fail criterion for all validation tests
# 3.3 Testing resources and staffing
# 3.4 Test work products 
# 3.5 Test record keeping and test log 
