Problems in the neighbourhood:

The salary information of the company's employees was stored in a special accounting software. The analytics department analyses the company's performance and the salary information on a monthly basis.

To reduce the risk of information leakage, the company has decided that data analysts are only provided with the information they need. As a result, an Excel file salary.xlsx was exported from the accounting software, where the client's name is encoded using an encoding algorithm developed by the company.

Due to a system error, the company lost access to the last month's salary data in the accounting system in one day.

The IT department has resolved the problem and found that the data is no longer available in the system, but the last salary.xlsx file produced for the analytics department is available, containing the employee's full name coding number and salary. Unfortunately, the employee's name saved in the file is encoded using an encoding algorithm that does not allow the name to be decoded back.

The company has 100 employees and there are 739 entries in the salary file. One of the employees is known to have performed several actions which may result in the employee appearing several times in the payroll file; the employee's salary information will not be present in the payroll file if the employee has been absent for a month.

To decode the information, it is possible to use the web encoding tool https://emn178.github.io/online-tools/crc32.html, which encodes the information using the CRC32 algorithm. (No information on whether the algorithm has been modified so that only the encoding result from the web platform can be used.)

Your task is to develop a program that:

    Opens a people.csv file for reading and reads the full employee name into a list data structure using the Python programming language.
    Using the Selenium library, you need to get the encoding result of each employee's full name using the https://emn178.github.io/online-tools/crc32.html web rick.
    Identify what is the total salary for each employee. The salary information is stored in the file salary.xslx, where the value of column A is the employee's full name in encoded format.
    After creating the program, it is necessary to answer the test questions by providing the required information about the salaries of the employees.

Once the program is executed, you need to submit the program file in <student ID number.py> format in the E-learning environment.
