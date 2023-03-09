# PyTest Test Task

Test Automation for Data Quality Engineers - PyTest test task


# Steps fot setup
1. Clone repository
2. Install requirements.txt by pip ('pip install -r requirements.txt')
3. Download and install ODBC Driver 17 for SQL Server
3. Create new login in MS SQL SMS. Save username, password, servername and name of DB.
    ![DdCredintalsHint](./NoProjectFiles/DdCredintalsHint.gif)
4. Update values in project from previous step:
    ![change_values_hint](./NoProjectFiles/ChangeValuesHint.png)
5. Open command line or etc in ProjectFiles folder and run followerd command 'pytest main.py > result.txt'

# Report example
It's preview:
    ![reportexample](./NoProjectFiles/ReportExample.png)

You can look at whole report by open [this file](https://git.epam.com/yurii_hordiichuk/pytesttesttask/-/blob/main/ProjectFiles/result.txt).

# If not work and problem like from db side:
1. Check settings in  SQL Server Configuration Manager -> SQL Server Network Configuration -> Protocols for <SQLEXPRESS> -> TCP/IP Properties -> IP Addresses
2. At least one ip address may be active and enabled 

