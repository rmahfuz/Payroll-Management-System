# Payroll-Management-System
A payroll management system implemented using C++

Data files required:                                                             
1. Employee File with the following record structure                                                                       
• Employee number                                                                                     
• Employee designation
• Employee name
• Employee basic salary
• Sex
• Employee Phone Number
• Employee date of birth
• Employee Mobile Number
• Employee date of joining
• Address

2. Monthly Pay File with the following record structure
• Employee number
• Employee name
• Number of days worked
• Basic (Monthly Basic Salary)
• DA (Dearness Allowance) = 55% of Basic
• HRA (House Rent Allowance) = 35% of Basic
• Conveyance = 15% of Basic
• Gross = Basic + DA + HRA + Conveyance
Deductions (Like Income Tax, Loan, Salary advance)
• Net = Gross – Net (If possible breGG up of deductions)

Operations:
1. Addition of records for new Employees in Employee File
2. Modification of existing records in Employee File except Employee No and
Employee Name
3. Searching in Employee File using following fields: Employee Number,
Employee Name
4. Input of number of days worked and other deductions of each employee in
Monthly Pay File
5. Report (Screen/Printer)
• Details of each Employee from Employee File
• Salary statement in the following format

Salary Statement for the month of: February 2007

--------------------------------------------------------------------------------
ENo Name Designation Basic Gross Deduction Net

--------------------------------------------------------------------------------
1001 MUNNAPPA DRIVER 12000 24600 1500 23100
1002 SUDARSHAN MANAGER 35000 71750 2000 69750
1003 KESHAV SECURTY OFF 20000 41000 500 40500

--------------------------------------------------------------------------------
• Salary Slip in the following format

--------------------------------------------------------------------------------
Salary Slip for the month of: February 2007
Employee No: 1001                                       Employee Name: MUNNAPPA

--------------------------------------------------------------------------------
Basic 12000                                              Deductions 1500
DA 6600
HRA 4200
Conveyance 1800

--------------------------------------------------------------------------------
Gross Pay 24600                                           Net      23100
Validations:
1. Automatic generation of Employee Number
2. Validations of inputted date
2. Validations Number of working days, phone Numbers.
3. Calculation of Basic: Max days will vary from month to month. Number of days
 worked will be Max days in a month – number of leaves in that month. If an
 employee does not take any leave then Number of Days Worked = Max Days in a
 Month. While calculating Basic Monthly Salary use the formula
 Actual Basic = Basic * Number of Days Worked / Max Days in a Month and
 accordingly DA, HRA, Conveyance and Gross have to be calculated on the basis
  of Actual basic.
