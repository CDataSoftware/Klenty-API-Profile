# Table of Contents

 <details>
 <summary>Klenty Profile</summary>
	 <br>
	 <ul>
	<li><a href="https://github.com/CDataSoftware/Klenty-API-Profile/blob/main/README.md#connecting-to-klenty">Connecting to Klenty</a>
	<li><a href="https://github.com/CDataSoftware/Klenty-API-Profile/blob/main/README.md#using-the-profile-1">Using the Profile</a>
		<ul>
			<li><a href="https://github.com/CDataSoftware/Klenty-API-Profile/blob/main/README.md#using-the-profile-in-adonet">ADO.NET</a>
			<li><a href="https://github.com/CDataSoftware/Klenty-API-Profile/blob/main/README.md#using-the-profile-in-jdbc">JDBC</a>
			<li><a href="https://github.com/CDataSoftware/Klenty-API-Profile/blob/main/README.md#using-the-profile-in-odbc">ODBC</a>
			<li><a href="https://github.com/CDataSoftware/Klenty-API-Profile/blob/main/README.md#using-the-profile-in-powerbi">PowerBI</a>
			<li><a href="https://github.com/CDataSoftware/Klenty-API-Profile/blob/main/README.md#using-the-profile-in-ssis">SSIS</a>
			<li><a href="https://github.com/CDataSoftware/Klenty-API-Profile/blob/main/README.md#using-the-profile-in-excel">Excel</a>
		</ul>
	<li><a href="https://github.com/CDataSoftware/Klenty-API-Profile/blob/main/README.md#sql-compliance-1">SQL Compliance</a>
		<ul>
			<li><a href="https://github.com/CDataSoftware/Klenty-API-Profile/blob/main/README.md#sql-compliance-2">SELECT STATEMENTS</a>
			<li><a href="https://github.com/CDataSoftware/Klenty-API-Profile/blob/main/README.md#sql-compliance-3">SQL FUNCTIONS</a>
				<ul>
					<li><a href="https://github.com/CDataSoftware/Klenty-API-Profile/blob/main/README.md#sql-compliance-3">String FUNCTIONS</a>
					<li><a href="https://github.com/CDataSoftware/Klenty-API-Profile/blob/main/README.md#sql-compliance-5">Date FUNCTIONS</a>
					<li><a href="https://github.com/CDataSoftware/Klenty-API-Profile/blob/main/README.md#sql-compliance-6">Math FUNCTIONS</a>
				</ul>
			<li><a href="https://github.com/CDataSoftware/Klenty-API-Profile/blob/main/README.md#sql-compliance-7">EXECUTE STATEMENTS</a>
		</ul>
  	<li><a href="https://github.com/CDataSoftware/Klenty-API-Profile/blob/main/README.md#schema-discovery-1">Schema Discovery</a>
		<ul>
			<li><a href="https://github.com/CDataSoftware/Klenty-API-Profile/blob/main/README.md#schema-discovery-1">ADO.NET</a>
			<li><a href="https://github.com/CDataSoftware/Klenty-API-Profile/blob/main/README.md#schema-discovery-3">JDBC</a>
			<li><a href="https://github.com/CDataSoftware/Klenty-API-Profile/blob/main/README.md#schema-discovery-4">System Tables</a>
				<ul>
					<li><a href="https://github.com/CDataSoftware/Klenty-API-Profile/blob/main/README.md#schema-discovery-5">sys_tables</a>
					<li><a href="https://github.com/CDataSoftware/Klenty-API-Profile/blob/main/README.md#schema-discovery-6">sys_tablecolumns</a>
					<li><a href="https://github.com/CDataSoftware/Klenty-API-Profile/blob/main/README.md#schema-discovery-7">sys_procedures</a>
				</ul>
		</ul>
  	<li><a href="https://github.com/CDataSoftware/Klenty-API-Profile/blob/main/README.md#klenty-tables">Tables</a>
		<ul>
			<li><a href="https://github.com/CDataSoftware/Klenty-API-Profile/blob/main/README.md#companycadences">CompanyCadences</a>
			<li><a href="https://github.com/CDataSoftware/Klenty-API-Profile/blob/main/README.md#lists">Lists</a>
			<li><a href="https://github.com/CDataSoftware/Klenty-API-Profile/blob/main/README.md#usercadences">UserCadences</a>
			<li><a href="https://github.com/CDataSoftware/Klenty-API-Profile/blob/main/README.md#prospectbylist">ProspectByList</a>
			<li><a href="https://github.com/CDataSoftware/Klenty-API-Profile/blob/main/README.md#prospectdetailsbyemail">ProspectDetailsByEmail</a>
			<li><a href="https://github.com/CDataSoftware/Klenty-API-Profile/blob/main/README.md#prospectstatusbyemail">ProspectStatusByEmail</a>
			<li><a href="https://github.com/CDataSoftware/Klenty-API-Profile/blob/main/README.md#prospectdetailswithcustomfields">ProspectDetailsWithCustomFields</a>
			<li><a href="https://github.com/CDataSoftware/Klenty-API-Profile/blob/main/README.md#prospectstatusbyid">ProspectStatusByID</a>
			<li><a href="https://github.com/CDataSoftware/Klenty-API-Profile/blob/main/README.md#prospectbycreationdate">ProspectByCreationDate</a>
			<li><a href="https://github.com/CDataSoftware/Klenty-API-Profile/blob/main/README.md#prospectbylastupdateddate">ProspectByLastUpdatedDate</a>
		</ul>
	</ul>
 </details>

 <br>

## Klenty Profile for API Driver
The CData API Profile for Klenty allows you to query data from Klenty. The Klenty profile is a single file (i.e. Klenty.apip) which can be used along with the [CData API Driver](https://www.cdata.com/apidriver/). The profile contains the table definitions and other metadata that the CData API Driver uses to connect to Klenty.
To use the Klenty Profile, set the Profile property of CData API Driver to the path of the Klenty profile. In addition, other connection properties will be required to authenticate to the service. You can find instructions specific to the Klenty Profile in [Connecting to Klenty](https://github.com/CDataSoftware/Klenty-API-Profile/blob/main/README.md#connecting-to-klenty). Once the connction to the profile has been established, you may access the data exposed by the profile from code or from various applications.

### Using the Profile
The API Profile can be used to connect to data exposed by a service in various applications. See [Using the API Profile](https://github.com/CDataSoftware/Klenty-API-Profile/blob/main/README.md#using-the-profile-1) for a list of guides on using the drivers in different frameworks, such as ADO.NET, JDBC or using different applications by connecting to the ODBC, Excel Add-in, or SSIS provider.

### SQL Compliance
The API Profile are fully compatible with SQL-92 syntax for selecting and executing procedures. In [SQL Compliance](https://github.com/CDataSoftware/Klenty-API-Profile/blob/main/README.md#sql-compliance-1), you can find a syntax reference and code examples outlining the supported SQL of each profile.

### Schema Discovery
The API Profiles support standard schema collections to retrieve the metadata exposed. See [Schema Discovery](https://github.com/CDataSoftware/Klenty-API-Profile/blob/main/README.md#schema-discovery-1) to find more about the standard schema classes in ADO.NET and JDBC exposing this data. Additionally, you may query the [System Tables](https://github.com/CDataSoftware/Klenty-API-Profile/blob/main/README.md#schema-discovery-4) to access additional metadata, such as data source capabilities.

### Tables
The provider models the data in APIs into a list of tables that can be queried using standard SQL statements. In the [Tables](https://github.com/CDataSoftware/Klenty-API-Profile/blob/main/README.md#klenty-tables) section you can find descriptions of the available table in the profile, including column names and datatypes.

[Jump to top](https://github.com/CDataSoftware/Klenty-API-Profile/blob/main/README.md#table-of-contents)
</br>
<br>

## Connecting to Klenty
To authenticate to Klenty, you can either use Token Authentication.

### Generating Klenty APIKey
The Klenty API follows the REST paradigm and requires you to have a unique API Key. To access the Klenty REST APIs, you need to authenticate your requests using the Klenty API Key.

 - Login to your Klenty account. Go to Settings → Integrations → Klenty API Key
 - Click on the key icon to generate an API Key 

### Using Token Authentication
To authenticate using the token, set the APIKey to your AuthToken obtained and the User connection property to your Klenty username/email. Additionally, set AuthScheme property to None in the ProfileSettings connection property.

##### Example connection string
`Profile=C:\profiles\Klenty.apip;ProfileSettings='APIKey=my_authtoken;AuthScheme=None;User=my_user;'`

### Connection Properties
The connection string properties are the various options that can be used to establish a connection. This section provides a complete list of the options you can configure in the connection string for this provider.

|**Property**  |**Description**                                                                                 |
|:-------------|:-----------------------------------------------------------------------------------------------|
| _APIKey_     | Your Personal Auth Token                                                                       |
| _AuthScheme_ | The scheme used for authentication. Accepted and Allowed entries are: **NONE**  |
| _User_       | The Klenty API user account used to authenticate.                                                     |

[Jump to top](https://github.com/CDataSoftware/Klenty-API-Profile/blob/main/README.md#table-of-contents)
</br>
<br>

## Using the Profile
The API Profile can be used in the CData API driver to enable access to data exposed by the service from a wide range of applications and frameworks. This chapter provides some examples using the different editions of the CData API Driver, such as the ADO.NET provider, JDBC driver or ODBC driver, which can be downloaded from the CData website.

### API Profile integrations
#### In ADO.NET
Using the ADO.NET provider for API with this profile will enable access to the profile in any .NET framework. See [ADO.NET](https://github.com/CDataSoftware/Klenty-API-Profile/blob/main/README.md#using-the-profile-in-adonet) for a walk-through of writing data access code this profile in ADO.NET by creating data connection objects, DataReader or DataAdapter classes.

#### In JDBC
The JDBC driver for API will allow access to the profile from a wide range of Java application, including custom code. See [JDBC](https://github.com/CDataSoftware/Klenty-API-Profile/blob/main/README.md#using-the-profile-in-jdbc) for a walk-through of writing data access code to this profile using the JDBC driver, including establishing a connection and executing basice statements.

#### In ODBC
With the ODBC driver for API, you can access data exposed by this profile from any ODBC compatible application. For information on how to get started with the ODBC and creating a DSN connecting to this profile, see [ODBC](https://github.com/CDataSoftware/Klenty-API-Profile/blob/main/README.md#using-the-profile-in-odbc).

#### Power BI
The CData Power BI Connector for API offers self-service integration with Microsoft Power BI. The connector facilitates live access to data from API profiles in Power BI from the Get Data window. The connector also provides direct querying to visualize and analyze API data. See [Power BI](https://github.com/CDataSoftware/Klenty-API-Profile/blob/main/README.md#using-the-profile-in-powerbi) for more information on how to connect to API profiles in the API PowerBI connector.

#### In SSIS
The CData SSIS Components for API enable you to connect SQL Server with data from API profiles through SSIS workflows. The components wrap the complexity of accessing API data in standard SSIS data flow components. See [SSIS](https://github.com/CDataSoftware/Klenty-API-Profile/blob/main/README.md#using-the-profile-in-ssis) for more information on how to connect to APIs in SSIS.

#### In Excel
The CData Excel Add-in for API provides the easiest way to connect to API profiles from Excel. From the CData ribbon, you can select API profile data as tables and columns into the spreadsheet. The spreadsheet is then linked with the remote data. To update the data, edit the spreadsheet. See [Excel](https://github.com/CDataSoftware/Klenty-API-Profile/blob/main/README.md#using-the-profile-in-excel) for more information.  
<br>The API Driver is available in other editions as well. For information on how to connect using the other available editions, please refer to the edition specific API help.</br>

[Jump to top](https://github.com/CDataSoftware/Klenty-API-Profile/blob/main/README.md#table-of-contents)
</br>
<br>

## Using the Profile in ADO.NET
This section provides a walk-through of writing data access code to this profile in ADO.NET. See Tables for more information on the available data source entities and how to query them with SQL. See SQL Compliance for the SQL syntax.

### Creating Connection Objects
See Establishing a Connection for guides to defining the connection string and authenticating. Below is a typical invocation to create APIConnection objects.

#### **C#**
```c#
using (APIConnection connection = 
  new APIConnection("Profile=Klenty.apip;ProfileSettings='APIKey=my_authtoken;AuthScheme=None;User=my_user;'"))
{
  connection.Open();
}
```

### Using the APIDataReader
The APIDataReader retrieves data faster than the APIDataAdapter because it can retrieve data in pages. As you read data from the APIDataReader, it periodically requests the next page of results from the data source, if required. This causes results to be returned at a faster rate. The following example selects all the columns from the CompanyCadences table:

#### **C#**

```c#
string connectionString = "Profile=Klenty.apip;ProfileSettings='APIKey=my_authtoken;AuthScheme=None;User=my_user;'";
using (APIConnection connection = new APIConnection(connectionString)) {
  APICommand cmd = new APICommand("SELECT * FROM CompanyCadences", connection);

  APIDataReader rdr = cmd.ExecuteReader();

  while (rdr.Read()) {
    Console.WriteLine(String.Format("\t{0} --> \t\t{1}", rdr["name"], rdr["owner"]));
  }
}
```

### Using the APIDataAdapter
Use the adapter's Fill method to retrieve data from the data source. An empty DataTable instance is passed as an argument to the Fill method. When the method returns, the DataTable instance is populated with the queried data. Note that the APIDataAdapter is slower than the APIDataReader because the Fill method needs to retrieve all data from the data source before returning.  
<br>
The following example selects the name and owner columns of the CompanyCadences table:
</br>

#### C#
```c#
string connectionString = "Profile=Klenty.apip;ProfileSettings='APIKey=my_authtoken;AuthScheme=None;User=my_user;'";
using (APIConnection connection = new APIConnection(connectionString)) {
  APIDataAdapter dataAdapter = new APIDataAdapter(
  "SELECT name, owner FROM CompanyCadences", connection);
   
  DataTable table = new DataTable();
  dataAdapter.Fill(table);
   
  Console.WriteLine("Contents of CompanyCadences.");
   
  foreach (DataRow row in table.Rows) {
    Console.WriteLine("{0}: {1}", row["name"], row["owner"]);
  }
}
```

[Jump to top](https://github.com/CDataSoftware/Klenty-API-Profile/blob/main/README.md#table-of-contents)
</br>
<br>

## Using the Profile in JDBC
This section provides a walk-through of writing data access code to this profile in JDBC using the CData JDBC driver for API.

### Connecting from Code
When connecting with the DriverManager class, the CData JDBC Driver for API 2019 follows the JDBC convention: First, load the API driver class. Then, make a connection.

#### Load the Driver
The following step is optional per the JDBC 4.0 specification.
```java
Class.forName("cdata.jdbc.api.APIDriver");
```
#### Establish a Connection
Provide the connection string with the getConnection method of the static DriverManager class. Start the connection string with "jdbc:api:". A typical connection string is the following:
```java
Connection conn = DriverManager.getConnection("jdbc:api:Profile=C:\profiles\Klenty.apip;ProfileSettings='APIKey=my_authtoken;AuthScheme=None;User=my_user;'");
```
Alternatively, you can prepare the connection options using a Properties object. Pass the Properties object to the DriverManager.
```java
Properties prop = new Properties();
prop.setProperty("Profile", "Klenty.apip");
prop.setProperty("ProfileSettings", "'APIKey=my_authtoken;AuthScheme=None;User=my_user;'");
Connection conn = DriverManager.getConnection("jdbc:api:,");
```
### Executing Select Statements
To execute SQL statements that return data, use the Statement class' generic execute method or the executeQuery method. To return the results of a query, call the getResultSet method of the Statement.  
<br>
The following example calls the execute method and iterates over the results returned:
</br>
```java
Statement stat = conn.createStatement();
boolean ret = stat.execute("SELECT name, owner FROM CompanyCadences");
if (ret) {
  ResultSet rs=stat.getResultSet();
  while(rs.next()) {
    for(int i=1;i<=rs.getMetaData().getColumnCount();i++) {
      System.out.println(rs.getMetaData().getColumnName(i) +"="+rs.getString(i));
    }
  }
}
```

[Jump to top](https://github.com/CDataSoftware/Klenty-API-Profile/blob/main/README.md#table-of-contents)
</br>
<br>

## Using the Profile in ODBC
This section provides a walk-through for accessing data from the profile in ODBC-compatible applications using the CData ODBC driver for API.
### Windows DSN Configuration
You can use the Microsoft ODBC Data Source Administrator to edit the DSN configuration. Note that the DSN is created during the installation process. Complete the following steps to edit the DSN configuration:
1. Select Start > Search, and enter **ODBC Data Sources** in the Search box.
2. Choose the version of the ODBC Administrator that corresponds to the bitness of your application (32-bit or 64-bit).
3. Click the **System DSN** tab.
4. Select the system data source and click **Configure**.
5. Specify the required configuration setting to connect to your profile
    - Profile
    - ProfileSettings
6. Edit any additional configuration settings on the Connection tab and click **OK**.

### Connecting from Applications
Once you've created your DSN, you can connect to the data exposed by the profile in any ODBC compatible application. Some of the most common ODBC application used with CData ODBC drivers are listed below:
  - From **Excel**
  - From **PowerPivot**
  - From **Access**
  - From **Filemaker Pro**
  - From **OBIEE**
  - From **Informatica**
  - From **SAS**  

In your application, you can now select this DSN to connect to your data. For more information, please refer the documentation specific to your client application.

[Jump to top](https://github.com/CDataSoftware/Klenty-API-Profile/blob/main/README.md#table-of-contents)
</br>
<br>

## Using the Profile in PowerBI
This section provides a walk-through for accessing data from the profile in PowerBI.

### Editing the DSN Configuration
You can use the Microsoft ODBC Data Source Administrator to edit the DSN configuration. Note that the DSN is created during the installation process. Complete the following steps to edit the DSN configuration:
1.	Select Start > Search, and enter **ODBC Data Sources** in the Search box.
2.	Choose the version of the ODBC Administrator that corresponds to the bitness of your application (32-bit or 64-bit).
3.	Click the **System DSN** tab.
4.	Select the system data source and click **Configure**.
5.	Specify the required configuration setting to connect to your profile
     -	Profile
     -	ProfileSettings
6.	Edit any additional configuration settings on the Connection tab and click **OK**.

### Getting Data
After Installing the Connector and Creating the Data Source Name, you can connect to the data that you want to work with. Complete the following steps to connect to the data:

1.	Click **Get Data**.
2.	Accept the warning to connect to a third-party service.
3.	Select **All > CDataAPI** in the Data Source Name menu.
4.	Select **Connect**.
5.	Enter the **Data Source Name, Advanced Connection Properties (optional)**, and **Advanced Options (optional)**.
6.	Select a data connectivity mode and click **OK**.
     -	Select **Import** to import a copy of the data into your project. You can refresh this data on demand.
     -	Select **DirectQuery** to work with the remote data.
7.	In the Navigator window, expand the CData Power BI API folder, then expand the associated schema folder to see a list of available data (tables, stored procedures, or views).
8.	Select the box next to the data that you want to work with.
9.	Select **Load** or **Edit**. See the next section for more information on these options.  

After getting the data, you can create visuals and reports.

[Jump to top](https://github.com/CDataSoftware/Klenty-API-Profile/blob/main/README.md#table-of-contents)
</br>
<br>

## Using the Profile in SSIS
The CData SSIS Components for API provide data flow components that allow for straightforward integration with API Profiles from SSIS data flow tasks. SQL Server 2008 R2, 2012, 2014, 2016, 2017, and 2019 are supported including their corresponding version of SQL Server Data Tools.

### Connecting with the API Connection Manager
Adding a new API Profile connection to the SSIS package is straightforward. Right-click within the Connection Manager window and select **New Connection** from the menu. Then, choose the API Connection Manager from the Add SSIS Connection Manager window.  
<br>
In order to connect to the profile, set the connection property Profile to the path of the profile, and ProfileSettings to the required profile properties defined in the Profile Connection page.
</br>

### Querying API Profile Data with the Source Component
Follow the procedure below to connect to API Profiles, retrieve data, and provide data to other components in the workflow.
1.	In the SSIS Toolbox, drag the CData API source component into the Data Flow task.
2.	Double-click the CData API source component. The CData API Source Editor will display.
3.	In the Connection Managers menu, select an available CData API connection manager, or create a new instance if one is not already available.
4.	Choose your Access Mode: "Table or View" or "SQL Statement". Select "Table or View" to use the GUI to select a table or view. Select "SQL Statement" to configure a statement of your choice.
5.	Select the Columns tab and rename any output columns as desired.
6.	When you execute the data flow, rows from your selected table or statement will be made available to the components in the data flow.
7.	See SELECT Statements for the supported SQL syntax and examples. See Calling Stored Procedures for how to call stored procedures.

When you execute the data flow, rows from your selected table or statement will be made available to the components in the data flow.

[Jump to top](https://github.com/CDataSoftware/Klenty-API-Profile/blob/main/README.md#table-of-contents)
</br>
<br>

## Using the Profile in Excel
The add-in adds controls to the Excel ribbon, standard Excel formulas, and VBA classes for writing macros.

### Configure a Connection Profile
Click From API to launch the connection dialog. Here, you can set the connection settings, including the Profile and ProfileSetting connection properties, test the connection, and save the connection profile. The profile enables you to control the following for a connection:
 -	**Workbook Sharing**  
    <br>
    Select the Store in Workbook option to create easy-to-share spreadsheets. By default, the provider saves the connection to an .rdc file in the CData subfolder in the %APPDATA% folder.
    </br>


### Building an SQL SELECT Query
After Establishing a Connection, select tables, columns, and filters -- as you make changes, the add-in generates the underlying SELECT query. Edit the query directly to execute joins, aggregations, or more complex SELECT Statements.
1.	Click "From API" from the CData ribbon to open the Data Selection wizard.
2.	In the Connection menu, select a connection or select the option to create a new connection.
3.	Select a table to start building the query. You can define filters, column aliases, and a limit on the records to return.

[Jump to top](https://github.com/CDataSoftware/Klenty-API-Profile/blob/main/README.md#table-of-contents)
</br>
<br>

## SQL Compliance
The API Profile supports several operations on profile data, including selecting and executing procedures.

### SELECT Statements
The API Profile supports SQL-92 Syntax. [SELECT Statements](https://github.com/CDataSoftware/Klenty-API-Profile/blob/main/README.md#sql-compliance-2) includes a comprehensive list of the supported keywords and clauses, as well as syntax reference and examples.

### SQL Functions
In addition to standard SELECT statement clauses, the API Profile supports additional functionaliy. See [SQL Functions](https://github.com/CDataSoftware/Klenty-API-Profile/blob/main/README.md#sql-compliance-3) for documentation and examples of SQL functions that are supported in SELECT queries, including [STRING Functions](https://github.com/CDataSoftware/Klenty-API-Profile/blob/main/README.md#sql-compliance-4), [DATE Functions](https://github.com/CDataSoftware/Klenty-API-Profile/blob/main/README.md#sql-compliance-5) and [MATH Functions](https://github.com/CDataSoftware/Klenty-API-Profile/blob/main/README.md#sql-compliance-6).

### EXECUTE Statements
Use EXECUTE or EXEC statements to execute stored procedures, when functionality cannot be represented diretly as a SELECT, INSERT, UPDATE or DELETE statement. See [EXECUTE Statements](https://github.com/CDataSoftware/Klenty-API-Profile/blob/main/README.md#sql-compliance-7) for a syntax reference and procedure examples.

[Jump to top](https://github.com/CDataSoftware/Klenty-API-Profile/blob/main/README.md#table-of-contents)
</br>
<br>

## SQL Compliance
A SELECT statement can consist of the following basic clauses.
-	SELECT
-	INTO
-	FROM
-	JOIN
-	WHERE
-	GROUP BY
-	HAVING
-	UNION
-	ORDER BY
-	LIMIT
### SELECT Syntax
The following syntax diagram outlines the syntax supported by the SQL engine of the provider:
```sql
SELECT {
  [ TOP <numeric_literal> | DISTINCT ]
  {
    *
    | {
        <expression> [ [ AS ] <column_reference> ]
        | { <table_name> | <correlation_name> } .*
      } [ , ... ]
  }
  [ INTO csv:// [ filename= ] <file_path> [ ;delimiter=tab ] ]
  {
    FROM <table_reference> [ [ AS ] <identifier> ]
  } [ , ... ]
  [ [ 
      INNER | { { LEFT | RIGHT | FULL } [ OUTER ] }
    ] JOIN <table_reference> [ ON <search_condition> ] [ [ AS ] <identifier> ]
  ] [ ... ]
  [ WHERE <search_condition> ]
  [ GROUP BY <column_reference> [ , ... ]
  [ HAVING <search_condition> ]
  [ UNION [ ALL ] <select_statement> ]
  [
    ORDER BY
    <column_reference> [ ASC | DESC ] [ NULLS FIRST | NULLS LAST ]
  ]
  [
    LIMIT <expression>
    [
      { OFFSET | , }
      <expression>
    ]
  ]
} | SCOPE_IDENTITY()
 
<expression> ::=
  | <column_reference>
  | @ <parameter>
  | ?
  | COUNT( * | { [ DISTINCT ] <expression> } )
  | { AVG | MAX | MIN | SUM | COUNT } ( <expression> )
  | NULLIF ( <expression> , <expression> )
  | COALESCE ( <expression> , ... )
  | CASE <expression>
      WHEN { <expression> | <search_condition> } THEN { <expression> | NULL } [ ... ]
    [ ELSE { <expression> | NULL } ]
    END
  | <literal>
  | <sql_function>
 
<search_condition> ::=
  {
    <expression> { = | > | < | >= | <= | <> | != | LIKE | NOT LIKE | IN | NOT IN | IS NULL | IS NOT NULL | AND | OR | CONTAINS | BETWEEN } [ <expression> ]
  } [ { AND | OR } ... ]
```
### Examples
1.	Return all columns:
   
    `SELECT * FROM CompanyCadences`

2.	Rename a column:
   
    `SELECT [name] AS Project_Name FROM CompanyCadences`

3.	Cast a column's data as a different data type:
   
    `SELECT CAST(createdDate AS VARCHAR) AS Str_createdDate FROM CompanyCadences`

4.	Search data:

    `SELECT * FROM CompanyCadences WHERE owner = 'test@cdata.com'`

5.	Return the number of items matching the query criteria:
   
    `SELECT COUNT(*) AS MyCount FROM CompanyCadences`

6.	Return the number of unique items matching the query criteria:

    `SELECT COUNT(DISTINCT owner) FROM CompanyCadences`
  	
7.	Return the unique items matching the query criteria:

    `SELECT DISTINCT owner FROM CompanyCadences`

8.	Summarize data:

    `SELECT owner, UPPER(name) FROM CompanyCadences GROUP BY owner`

	See [Aggregate Functions](https://github.com/CDataSoftware/Klenty-API-Profile/blob/main/README.md#sql-compliance-2) for details.

9.	Retrieve data from multiple tables.

    `SELECT CompanyCadences.Id, Lists.Id FROM CompanyCadences, Lists WHERE CompanyCadences.Id=Lists.Id`

	See [JOIN Queries](https://github.com/CDataSoftware/Klenty-API-Profile/blob/main/README.md#sql-compliance-2) for details.

10.	Sort a result set in ascending order:

    `SELECT owner, name FROM CompanyCadences ORDER BY owner ASC`
   	
11.	Restrict a result set to the specified number of rows:

    `SELECT owner, name FROM CompanyCadences LIMIT 10`

12.	Parameterize a query to pass in inputs at execution time. This enables you to create prepared statements and mitigate SQL injection attacks.

    `SELECT * FROM ProspectDetailsByEmail WHERE Email = 'test@cdata.com'`

See [Explicitly Caching Data](https://github.com/CDataSoftware/Klenty-API-Profile/blob/main/README.md#sql-compliance-2) for information on using the SELECT statement in offline mode.

[Jump to top](https://github.com/CDataSoftware/Klenty-API-Profile/blob/main/README.md#table-of-contents)
</br>
<br>

## SQL Compliance
The provider provides functions that are similar to those that are available with most standard databases. These functions are implemented in the CData provider engine and thus are available across all data sources with the same consistent API. Three categories of functions are available: string, date, and math.

The provider interprets all SQL function inputs as either strings or column identifiers, so you need to escape all literals as strings, with single quotes. For example, contrast the SQL Server syntax and provider syntax for the **DATENAME** function:

-	**SQL Server**:  

    `SELECT DATENAME(yy,GETDATE())`

-	**provider**:  

    `SELECT DATENAME('yy',GETDATE())`

### String Functions
These functions perform string manipulations and return a string value. See [STRING Functions](https://github.com/CDataSoftware/Klenty-API-Profile/blob/main/README.md#sql-compliance-4) for more details.  

```sql
SELECT CONCAT(FirstName, space(1), LastName) FROM ProspectDetailsByEmail WHERE Email = 'test@cdata.com'
```

### Date Functions
These functions perform date and date time manipulations. See [DATE Functions](https://github.com/CDataSoftware/Klenty-API-Profile/blob/main/README.md#sql-compliance-5) for more details.  

```sql
SELECT CURRENT_TIMESTAMP() FROM CompanyCadences
```

### Math Functions
These functions provide mathematical operations. See [MATH Functions](https://github.com/CDataSoftware/Klenty-API-Profile/blob/main/README.md#sql-compliance-6) for more details.  

```sql
SELECT RAND() FROM CompanyCadences
```

### Function Parameters and Nesting SQL Functions
The provider supports column names, constants, and results of other functions as parameters to functions. The following are all valid uses of SQL functions:  

```sql
SELECT CONCAT('Mr./Ms.', SPACE(1), FirstName, SPACE(1), LastName) FROM ProspectDetailsByEmail WHERE Email = 'test@cdata.com'
```

[Jump to top](https://github.com/CDataSoftware/Klenty-API-Profile/blob/main/README.md#table-of-contents)
</br>
<br>

## SQL Compliance

### ASCII(character_expression)
Returns the ASCII code value of the left-most character of the character expression.
-	**character_expression**: The character expression.
```sql
SELECT ASCII('0');
--  Result: 48
```
### CHAR(integer_expression)
Converts the integer ASCII code to the corresponding character.
-	**integer_expression**: The integer from 0 through 255.
```sql
SELECT CHAR(48);
-- Result: '0'
```
### CHARINDEX(expressionToFind ,expressionToSearch [,start_location ])
Returns the starting position of the specified expression in the character string.
-	**expressionToFind**: The character expression to find.
-	**expressionToSearch**: The character expression, typically a column, to search.
-	**start_location**: The optional character position to start searching for expressionToFind in expressionToSearch.
```sql
SELECT CHARINDEX('456', '0123456');
-- Result: 4

 SELECT CHARINDEX('456', '0123456', 5);
-- Result: -1
```
### CHAR_LENGTH(character_expression),
Returns the number of UTF-8 characters present in the expression.
-	**character_expression**: The set of characters to be be evaluated for length.
```sql
SELECT CHAR_LENGTH('sample text') FROM Account LIMIT 1
-- Result: 11
```         
### CONCAT(string_value1, string_value2 [, string_valueN])
Returns the string that is the concatenation of two or more string values.
-	**string_value1**: The first string to be concatenated.
-	**string_value2**: The second string to be concatenated.
-	*: The optional additional strings to be concatenated.
```sql
SELECT CONCAT('Hello, ', 'world!');
-- Result: 'Hello, world!'
```
### CONTAINS(expressionToSearch, expressionToFind)
Returns 1 if expressionToFind is found within expressionToSearch; otherwise, 0.
-	**expressionToSearch**: The character expression, typically a column, to search.
-	**expressionToFind**: The character expression to find.
```sql
SELECT CONTAINS('0123456', '456');
-- Result: 1

SELECT CONTAINS('0123456', 'Not a number');
-- Result: 0
```
### ENDSWITH(character_expression, character_suffix)
Returns 1 if character_expression ends with character_suffix; otherwise, 0.
-	**character_expression**: The character expression.
-	**character_suffix**: The character suffix to search for.
```sql
SELECT ENDSWITH('0123456', '456');
-- Result: 1

SELECT ENDSWITH('0123456', '012');
-- Result: 0
```
### FILESIZE(uri)
Returns the number of bytes present in the file at the specified file path.
-	**uri**: The path of the file to read the size from.
```sql
SELECT FILESIZE('C:/Users/User1/Desktop/myfile.txt');
-- Result: 23684
```
### FORMAT(value [, parseFormat], format )
Returns the value formatted with the specified format.
-	**value**: The string to format.
-	**Format**: The string specifying the output syntax of the date or numeric format.
-	**parseFormat**: The string specifying the input syntax of the date value. Not applicable to numeric types.
```sql
SELECT FORMAT(12.34, '#');
-- Result: 12

 SELECT FORMAT(12.34, '#.###');
-- Result: 12.34

SELECT FORMAT(1234, '0.000E0');
-- Result: 1.234E3

SELECT FORMAT('2019/01/01', 'yyyy-MM-dd');
-- Result: 2019-01-01

 SELECT FORMAT('20190101', 'yyyyMMdd', 'yyyy-MM-dd');
-- Result: '2019-01-01'
```
### FROM_UNIXTIME(time, issecond)
Returns a representation of the unix_timestamp argument as a value in YYYY-MM-DD HH:MM:SS expressed in the current time zone.
-	**time**: The time stamp value from epoch time. Milliseconds are accepted.
-	**issecond**: Indicates the time stamp value is milliseconds to epoch time.
```sql
SELECT FROM_UNIXTIME(1540495231, 1);
-- Result: 2018-10-25 19:20:31

 SELECT FROM_UNIXTIME(1540495357385, 0);
-- Result: 2018-10-25 19:22:37
```
### HASHBYTES(algorithm, value)
Returns the hash of the input value as a byte array using the given algorithm. The supported algorithms are MD5, SHA1, SHA2_256, SHA2_512, SHA3_224, SHA3_256, SHA3_384, and SHA3_512.
-	**algorithm**: The algorithm to use for hashing. Must be one of MD5, SHA1, SHA2_256, SHA2_512, SHA3_224, SHA3_256, SHA3_384, or SHA3_512.
-	**value**: The value to hash. Must be either a string or byte array.
```sql
SELECT HASHBYTES('MD5', 'Test');
-- Result (byte array): 0x0CBC6611F5540BD0809A388DC95A615B
```
### INDEXOF(expressionToSearch, expressionToFind [,start_location ])
Returns the starting position of the specified expression in the character string.

-	**expressionToSearch**: The character expression, typically a column, to search.
-	**expressionToFind**: The character expression to find.
-	**start_location**: The optional character position to start searching for expressionToFind in expressionToSearch.
```sql
SELECT INDEXOF('0123456', '456');
-- Result: 4

 SELECT INDEXOF('0123456', '456', 5);
-- Result: -1
```
### ISNULL ( check_expression , replacement_value )
Replaces null with the specified replacement value.

- **check_expression**: The expression to be checked for null.
-	**replacement_value**: The expression to be returned if check_expression is null.
```sql
SELECT ISNULL(42, 'Was NULL');
-- Result: 42
 	
 SELECT ISNULL(NULL, 'Was NULL');
-- Result: 'Was NULL'
```
### JSON_AVG(json, jsonpath)
Computes the average value of a JSON array within a JSON object. The path to the array is specified in the jsonpath argument. Return value is numeric or null.
-	**json**: The JSON document to compute.
-	**jsonpath**: The JSONPath used to select the nodes. [x], [2..], [..8], or [1..12] are accepted. [x] selects all nodes.
```sql
SELECT JSON_AVG('[1,2,3,4,5]', '$[x]');
-- Result: 3

SELECT JSON_AVG('{"test": {"data": [1,2,3,4,5]}}', '$.test.data[x]');
-- Result: 3

SELECT JSON_AVG('{"test": {"data": [1,2,3,4,5]}}', '$.test.data[3..]');
-- Result: 4.5
```
### JSON_COUNT(json, jsonpath)
Returns the number of elements in a JSON array within a JSON object. The path to the array is specified in the jsonpath argument. Return value is numeric or null.

-	**json**: The JSON document to compute.
-	*jsonpath**: The JSONPath used to select the nodes. [x], [2..], [..8], or [1..12] are accepted. [x] selects all nodes.
```sql
SELECT JSON_COUNT('[1,2,3,4,5]', '$[x]');
-- Result: 5

SELECT JSON_COUNT('{"test": {"data": [1,2,3,4,5]}}', '$.test.data[x]');
-- Result: 5

SELECT JSON_COUNT('{"test": {"data": [1,2,3,4,5]}}', '$.test.data[3..]');
-- Result: 2
```
### JSON_EXTRACT(json, jsonpath)
Selects any value in a JSON array or object. The path to the array is specified in the jsonpath argument. Return value is numeric or null.
-	**json**: The JSON document to extract.
-	**jsonpath**: The XPath used to select the nodes. The JSONPath must be a string constant. The values of the nodes selected will be returned in a token-separated list.
```sql
SELECT JSON_EXTRACT('{"test": {"data": 1}}', '$.test');
-- Result: '{"data":1}'

SELECT JSON_EXTRACT('{"test": {"data": 1}}', '$.test.data');
-- Result: 1

SELECT JSON_EXTRACT('{"test": {"data": [1, 2, 3]}}', '$.test.data[1]');
-- Result: 2
```
### JSON_MAX(json, jsonpath)
Gets the maximum value in a JSON array within a JSON object. The path to the array is specified in the jsonpath argument. Return value is numeric or null.
-	**json**: The JSON document to compute.
-	**jsonpath**: The JSONPath used to select the nodes. [x], [2..], [..8], or [1..12] are accepted. [x] selects all nodes.
```sql
SELECT JSON_MAX('[1,2,3,4,5]', '$[x]');
-- Result: 5

SELECT JSON_MAX('{"test": {"data": [1,2,3,4,5]}}', '$.test.data[x]');
-- Result: 5

SELECT JSON_MAX('{"test": {"data": [1,2,3,4,5]}}', '$.test.data[..3]');
-- Result: 4
```
### JSON_MIN(json, jsonpath)
Gets the minimum value in a JSON array within a JSON object. The path to the array is specified in the jsonpath argument. Return value is numeric or null.
-	**json**: The JSON document to compute.
-	**jsonpath**: The JSONPath used to select the nodes. [x], [2..], [..8], or [1..12] are accepted. [x] selects all nodes.
```sql
SELECT JSON_MIN('[1,2,3,4,5]', '$[x]');
-- Result: 1

SELECT JSON_MIN('{"test": {"data": [1,2,3,4,5]}}', '$.test.data[x]');
-- Result: 1

 SELECT JSON_MIN('{"test": {"data": [1,2,3,4,5]}}', '$.test.data[3..]');
-- Result: 4
```
### JSON_SUM(json, jsonpath)
Computes the summary value in JSON according to the JSONPath expression. Return value is numeric or null.
-	**json**: The JSON document to compute.
-	**jsonpath**: The JSONPath used to select the nodes. [x], [2..], [..8], or [1..12] are accepted. [x] selects all nodes.
```sql
SELECT JSON_SUM('[1,2,3,4,5]', '$[x]');
-- Result: 15

SELECT JSON_SUM('{"test": {"data": [1,2,3,4,5]}}', '$.test.data[x]');
-- Result: 15

SELECT JSON_SUM('{"test": {"data": [1,2,3,4,5]}}', '$.test.data[3..]');
-- Result: 9
```
### LEFT ( character_expression , integer_expression )
Returns the specified number of characters counting from the left of the specified string.
-	**character_expression**: The character expression.
-	**integer_expression**: The positive integer that specifies how many characters will be returned counting from the left of character_expression.
```sql
SELECT LEFT('1234567890', 3);
-- Result: '123'
```
### LEN(string_expression)
Returns the number of characters of the specified string expression.
-	**string_expression**: The string expression.
```sql
SELECT LEN('12345');
-- Result: 5
```
### LOCATE(substring,string)
Returns an integer representing how many characters into the string the substring appears.
-	**substring**: The substring to find inside larger string.
-	**string**: The larger string that will be searched for the substring.
```sql
SELECT LOCATE('sample','XXXXXsampleXXXXX');
-- Result: 6
```
### LOWER ( character_expression )
Returns the character expression with the uppercase character data converted to lowercase.
-	**character_expression**: The character expression.
```sql
SELECT LOWER('MIXED case');
-- Result: 'mixed case'
```
### LTRIM(character_expression)
Returns the character expression with leading blanks removed.
-	**character_expression**: The character expression.
```sql
SELECT LTRIM('     trimmed');
-- Result: 'trimmed'
```
### MASK(string_expression, mask_character [, start_index [, end_index ]])
Replaces the characters between start_index and end_index with the mask_character within the string.
-	**string_expression**: The string expression to be searched.
-	**mask_character**: The character to mask with.
-	**start_index**: The optional number of characters to leave unmasked at beginning of string. Defaults to 0.
-	**end_index**: The optional number of characters to leave unmasked at end of string. Defaults to 0.
```sql
SELECT MASK('1234567890','*',);
-- Result: '**********'

SELECT MASK('1234567890','*', 4);
-- Result: '1234******'

SELECT MASK('1234567890','*', 4, 2);
-- Result: '1234****90' 
```
### NCHAR(integer_expression)
Returns the Unicode character with the specified integer code as defined by the Unicode standard.
-	**integer_expression**: The integer from 0 through 255.

### OCTET_LENGTH(character_expression),
Returns the number of bytes present in the expression.
-	**character_expression**: The set of characters to be be evaluated.
```sql
SELECT OCTET_LENGTH('text') FROM Account LIMIT 1
-- Result: 4
```
### PATINDEX(pattern, expression)
Returns the starting position of the first occurrence of the pattern in the expression. Returns 0 if the pattern is not found.
-	**pattern**: The character expression that contains the sequence to be found. The wild-card character % can be used only at the start or end of the expression.
-	**expression**: The expression, typically a column, to search for the pattern.
```sql
SELECT PATINDEX('123%', '1234567890');
-- Result: 1
 	
SELECT PATINDEX('%890', '1234567890');
-- Result: 8
 	
SELECT PATINDEX('%456%', '1234567890');
-- Result: 4
```
### POSITION(expressionToFind IN expressionToSearch)
Returns the starting position of the specified expression in the character string.
-	**expressionToFind**: The character expression to find.
-	**expressionToSearch**: The character expression, typically a column, to search.
```sql
SELECT POSITION('456' IN '123456');
-- Result: 4

SELECT POSITION('x' IN '123456');
-- Result: 0
```
### QUOTENAME(character_string [, quote_character])
Returns a valid SQL Server-delimited identifier by adding the necessary delimiters to the specified Unicode string.
-	**character_string**: The string of Unicode character data. The string is limited to 128 characters. Inputs greater than 128 characters return null.
-	**quote_character**: The optional single character to be used as the delimiter. Can be a single quotation mark, a left or right bracket, or a double quotation mark. If quote_character is not specified brackets are used.
```sql
SELECT QUOTENAME('table_name');
-- Result: '[table_name]'

SELECT QUOTENAME('table_name', '"');
-- Result: '"table_name"'

SELECT QUOTENAME('table_name', '[');
-- Result: '[table_name]'
```
### REPLACE(string_expression, string_pattern, string_replacement)
Replaces all occurrences of a string with another string.
-	**string_expression**: The string expression to be searched. Can be a character or binary data type.
-	**string_pattern**: The substring to be found. Cannot be an empty string.
-	**string_replacement**: The replacement string.
```sql
SELECT REPLACE('1234567890', '456', '|');
-- Result: '123|7890'

SELECT REPLACE('123123123', '123', '.');
-- Result: '...'

SELECT REPLACE('1234567890', 'a', 'b');
-- Result: '1234567890'
```
### REPLICATE ( string_expression ,integer_expression )
Repeats the string value the specified number of times.
-	**string_expression**: The string to replicate.
-	**integer_expression**: The repeat count.
```sql
SELECT REPLACE('x', 5);
-- Result: 'xxxxx'
```
### REVERSE ( string_expression )
Returns the reverse order of the string expression.
-	**string_expression**: The string.
```sql
SELECT REVERSE('1234567890');
-- Result: '0987654321'
```
### RIGHT ( character_expression , integer_expression )
Returns the right part of the string with the specified number of characters.
-	**character_expression**: The character expression.
-	**integer_expression**: The positive integer that specifies how many characters of the character expression will be returned.
```sql
SELECT RIGHT('1234567890', 3);
-- Result: '890'
```
## RTRIM(character_expression)
Returns the character expression after it removes trailing blanks.
-	**character_expression**: The character expression.
```sql
SELECT RTRIM('trimmed     ');
-- Result: 'trimmed'
```
### SOUNDEX(character_expression)
Returns the four-character Soundex code, based on how the string sounds when spoken.
-	**character_expression**: The alphanumeric expression of character data.
```sql
SELECT SOUNDEX('smith');
-- Result: 'S530'
```
### SPACE(repeatcount)
Returns the string that consists of repeated spaces.
-	**repeatcount**: The number of spaces.
```sql
SELECT SPACE(5);
-- Result: '     '
```
### SPLIT(string, delimiter, offset)
Returns a section of the string between to delimiters.
-	**string**: The string to split.
-	**delimiter**: The character to split the string with.
-	**offset**: The number of the split to return. Positive numbers are treated as offsets from the left, and negative numbers are treated as offsets from the right.
```sql
SELECT SPLIT('a/b/c/d', '/', 1);
-- Result: 'a'

SELECT SPLIT('a/b/c/d', '/', -2);
-- Result: 'c'
```
### STARTSWITH(character_expression, character_prefix)
Returns 1 if character_expression starts with character_prefix; otherwise, 0.
-	**character_expression**: The character expression.
-	**character_prefix**: The character prefix to search for.
```sql
SELECT STARTSWITH('0123456', '012');
-- Result: 1

SELECT STARTSWITH('0123456', '456');
-- Result: 0
```
### STR ( float_expression [ , integer_length [ , integer_decimal ] ] )
Returns the character data converted from the numeric data. For example, STR(123.45, 6, 1) returns 123.5.
-	**float_expression**: The float expression.
-	**length**: The optional total length to return. This includes decimal point, sign, digits, and spaces. The default is 10.
-	**decimal**: The optional number of places to the right of the decimal point. The decimal must be less than or equal to 16.
```sql
SELECT STR('123.456');
-- Result: '123'

 SELECT STR('123.456', 2);
-- Result: '**'

SELECT STR('123.456', 10, 2);
-- Result: '123.46'
```
### STUFF(character_expression , integer_start , integer_length , replaceWith_expression)
Inserts a string into another string. It deletes the specified length of characters in the first string at the start position and then inserts the second string into the first string at the start position.
-	**character_expression**: The string expression.
-	**start**: The integer value that specifies the location to start deletion and insertion. If start or length is negative, null is returned. If start is longer than the string to be modified, character_expression, null is returned.
-	**length**: The integer that specifies the number of characters to delete. If length is longer than character_expression, deletion occurs up to the last character in replaceWith_expression.
-	**replaceWith_expression**: The expression of character data that will replace length characters of character_expression beginning at the start value.
```sql
SELECT STUFF('1234567890', 3, 2, 'xx');
-- Result: '12xx567890'
```
### SUBSTRING(string_value FROM start FOR length)
Returns the part of the string with the specified length; starts at the specified index.
-	**string_value**: The character string.
-	**start**: The positive integer that specifies the start index of characters to return.
-	**length**: Optional. The positive integer that specifies how many characters will be returned.
```sql
SELECT SUBSTRING('1234567890' FROM 3 FOR 2);
-- Result: '34'

SELECT SUBSTRING('1234567890' FROM 3);
-- Result: '34567890'
```
### TOSTRING(string_value1)
Converts the value of this instance to its equivalent string representation.
-	**string_value1**: The string to be converted.
```sql
SELECT TOSTRING(123);
-- Result: '123'

SELECT TOSTRING(123.456);
-- Result: '123.456'

SELECT TOSTRING(null);
-- Result: ''
```
### TRIM(trimspec trimchar FROM string_value)
Returns the character expression with leading and/or trailing blanks removed.
-	**trimspec**: Optional. If included must be one of the keywords BOTH, LEADING or TRAILING.
-	**trimchar**: Optional. If included should be a one-character string value.
-	**string_value**: The string value to trim.
```sql
SELECT TRIM('     trimmed     ');
-- Result: 'trimmed'

SELECT TRIM(LEADING FROM '     trimmed     ');
-- Result: 'trimmed     '

SELECT TRIM('-' FROM '-----trimmed-----');
-- Result: 'trimmed'

SELECT TRIM(BOTH '-' FROM '-----trimmed-----');
-- Result: 'trimmed'

SELECT TRIM(TRAILING '-' FROM '-----trimmed-----');
-- Result: '-----trimmed'
```
### UNICODE(ncharacter_expression)
Returns the integer value defined by the Unicode standard of the first character of the input expression.
-	**ncharacter_expression**: The Unicode character expression.
### UPPER ( character_expression )
Returns the character expression with lowercase character data converted to uppercase.
-	**character_expression**: The character expression.
```sql
SELECT UPPER('MIXED case');
-- Result: 'MIXED CASE'
```
### XML_EXTRACT(xml, xpath [, separator])
Extracts an XML document using the specified XPath to flatten the XML. A comma is used to separate the outputs by default, but this can be changed by specifying the third parameter.
-	**xml**: The XML document to extract.
-	**xpath**: The XPath used to select the nodes. The nodes selected will be returned in a token-separated list.
-	**separator**: The optional token used to separate the items in the flattened response. If this is not specified, the separator will be a comma.
```sql
SELECT XML_EXTRACT('<vowels><ch>a</ch><ch>e</ch><ch>i</ch><ch>o</ch><ch>u</ch></vowels>', '/vowels/ch');
-- Result: 'a,e,i,o,u'

SELECT XML_EXTRACT('<vowels><ch>a</ch><ch>e</ch><ch>i</ch><ch>o</ch><ch>u</ch></vowels>', '/vowels/ch', ';');
-- Result: 'a;e;i;o;u'
```

[Jump to top](https://github.com/CDataSoftware/Klenty-API-Profile/blob/main/README.md#table-of-contents)
</br>
<br>

## SQL Compliance

### CURRENT_DATE()
Returns the current date value.
```sql
SELECT CURRENT_DATE();
-- Result: 2018-02-01
```
### CURRENT_TIMESTAMP()
Returns the current time stamp of the database system as a datetime value. This value is equal to GETDATE and SYSDATETIME, and is always in the local timezone.
```sql
SELECT CURRENT_TIMESTAMP();
-- Result: 2018-02-01 03:04:05
```
### DATEADD (datepart , integer_number , date [, dateformat])
Returns the datetime value that results from adding the specified number (a signed integer) to the specified date part of the date.
-	**datepart**: The part of the date to add the specified number to. The valid values and abbreviations are year (yy, yyyy), quarter (qq, q), month (mm, m), dayofyear (dy, y), day (dd, d), week (wk, ww), weekday (dw), hour (hh), minute (mi, n), second (ss, s), and millisecond (ms).
-	**number**: The number to be added.
-	**date**: The expression of the datetime data type.
-	**dateformat**: The optional output date format.
```sql
SELECT DATEADD('d', 5, '2018-02-01');
-- Result: 2018-02-06 

SELECT DATEADD('hh', 5, '2018-02-01 00:00:00');
-- Result: 2018-02-01 05:00:00
```
### DATEDIFF ( datepart , startdate , enddate )
Returns the difference (a signed integer) of the specified time interval between the specified start date and end date.
-	**datepart**: The part of the date that is the time interval of the difference between the start date and end date. The valid values and abbreviations are day (dd, d), hour (hh), minute (mi, n), second (ss, s), and millisecond (ms).
-	**startdate**: The datetime expression of the start date.
-	**enddate**: The datetime expression of the end date.
```sql
SELECT DATEDIFF('d', '2018-02-01', '2018-02-10');
-- Result: 9 

SELECT DATEDIFF('hh', '2018-02-01 00:00:00', '2018-02-01 12:00:00');
-- Result: 12
```
### DATEFROMPARTS(integer_year, integer_month, integer_day)
Returns the datetime value for the specified year, month, and day.
-	**year**: The integer expression specifying the year.
-	**month**: The integer expression specifying the month.
-	**day**: The integer expression specifying the day.
```sql
SELECT DATEFROMPARTS(2018, 2, 1);
-- Result: 2018-02-01
```
### DATENAME(datepart , date)
Returns the character string that represents the specified date part of the specified date.
-	**datepart**: The part of the date to return. The valid values and abbreviations are year (yy, yyyy), quarter (qq, q), month (mm, m), dayofyear (dy, y), day (dd, d), week (wk, ww), weekday (dw), hour (hh), minute (mi, n), second (ss, s), millisecond (ms), microsecond (mcs), nanosecond (ns), and TZoffset (tz).
-	**date**: The datetime expression.
```sql
SELECT DATENAME('yy', '2018-02-01');
-- Result: '2018' 

SELECT DATENAME('dw', '2018-02-01');
-- Result: 'Thursday'
```
### DATEPART(datepart, date [,integer_datefirst])
Returns a character string that represents the specified date part of the specified date.
-	**datepart**: The part of the date to return. The valid values and abbreviations are year (yy, yyyy), quarter (qq, q), month (mm, m), dayofyear (dy, y), day (dd, d), week (wk, ww), weekday (dw), hour (hh), minute (mi, n), second (ss, s), millisecond (ms), microsecond (mcs), nanosecond (ns), TZoffset (tz), ISODOW, ISO_WEEK (isoweek, isowk,isoww), and ISOYEAR.
-	**date**: The datetime string.
-	**datefirst**: The optional integer representing the first day of the week. The default is 7, Sunday.
```sql
SELECT DATEPART('yy', '2018-02-01');
-- Result: 2018 

SELECT DATEPART('dw', '2018-02-01');
-- Result: 5
```
### DATETIME2FROMPARTS(integer_year, integer_month, integer_day, integer_hour, integer_minute, integer_seconds, integer_fractions, integer_precision)
Returns the datetime value for the specified date parts.
-	**year**: The integer expression specifying the year.
-	**month**: The integer expression specifying the month.
-	**day**: The integer expression specifying the day.
-	**hour**: The integer expression specifying the hour.
-	**minute**: The integer expression specifying the minute.
-	**seconds**: The integer expression specifying the seconds.
-	**fractions**: The integer expression specifying the fractions of the second.
-	**precision**: The integer expression specifying the precision of the fraction.
```sql
SELECT DATETIME2FROMPARTS(2018, 2, 1, 1, 2, 3, 456, 3);
-- Result: 2018-02-01 01:02:03.456
```
### DATETIMEFROMPARTS(integer_year, integer_month, integer_day, integer_hour, integer_minute, integer_seconds, integer_milliseconds)
Returns the datetime value for the specified date parts.
-	**year**: The integer expression specifying the year.
-	**month**: The integer expression specifying the month.
-	**day**: The integer expression specifying the day.
-	**hour**: The integer expression specifying the hour.
-	**minute**: The integer expression specifying the minute.
-	**seconds**: The integer expression specifying the seconds.
-	**milliseconds**: The integer expression specifying the milliseconds.
```sql
SELECT DATETIMEFROMPARTS(2018, 2, 1, 1, 2, 3, 456);
-- Result: 2018-02-01 01:02:03.456
```
### DATE_TRUNC(date, datepart)
Truncates the date to the precision of the given date part. Modelled after the Oracle TRUNC function.

-	**date**: The datetime string that specifies the date.
-	**datepart**: Refer to the Oracle documentation for valid datepart syntax.
```sql
SELECT DATE_TRUNC('05-04-2005', 'YY');
-- Result: '1/1/2005'
 
SELECT DATE_TRUNC('05-04-2005', 'MM');
-- Result: '5/1/2005'
```                   
### DATE_TRUNC2(datepart, date, [weekday])
Truncates the date to the precision of the given date part. Modeled after the PostgreSQL date_trunc function.
-	**datepart**: One of 'millennium', 'century', 'decade', 'year', 'quarter', 'month', 'week', 'day', 'hour', 'minute' or 'second'.
-	**date**: The datetime string that specifies the date.
-	**weekday**: The optional day of the week to use as the first day for 'week'. One of 'sunday', 'monday', etc.
```sql
SELECT DATE_TRUNC2('year', '2020-02-04');
-- Result: '2020-01-01'
 
SELECT DATE_TRUNC2('week', '2020-02-04', 'monday');
-- Result: '2020-02-02', which is the previous Monday
```
### DAY(date)
Returns the integer that specifies the day component of the specified date.
-	**date**: The datetime string that specifies the date.
```sql
SELECT DAY('2018-02-01');
-- Result: 1
```
### DAYOFMONTH(date)
Returns the day of the month of the given date part.
-	**date**: The datetime string that specifies the date.
```sql
SELECT DAYOFMONTH('04/15/2000');
-- Result: 15
```
### DAYOFWEEK(date)
Returns the day of the week of the given date part.
-	**date**: The datetime string that specifies the date.
```sql
SELECT DAYOFWEEK('04/15/2000');
-- Result: 7
```
### DAYOFYEAR(date)
Returns the day of the year of the given date part.
-	**date**: The datetime string that specifies the date.
```sql
SELECT DAYOFYEAR('04/15/2000');
-- Result: 106
```
### EOMONTH(date [, integer_month_to_add ]) or LAST_DAY(date)
Returns the last day of the month that contains the specified date with an optional offset.
-	**date**: The datetime expression specifying the date for which to return the last day of the month.
-	**integer_month_to_add**: The optional integer expression specifying the number of months to add to the date before calculating the end of the month.
```sql
SELECT EOMONTH('2018-02-01');
-- Result: 2018-02-28
 
SELECT LAST_DAY('2018-02-01');
-- Result: 2018-02-28
 
SELECT EOMONTH('2018-02-01', 2);
-- Result: 2018-04-30
```
### FDWEEK(date)
Returns the first day of the week of the given date part.
-	**date**: The datetime string that specifies the date.
```sql
SELECT FDWEEK('02-08-2018');
-- Result: 2/4/2018
```
### FDMONTH(date)
Returns the first day of the month of the given date part.
-	**date**: The datetime string that specifies the date.
```sql
SELECT FDMONTH('02-08-2018');
-- Result: 2/1/2018
```
### FDQUARTER(date)
Returns the first day of the quarter of the given date part.
-	**date**: The datetime string that specifies the date.
```sql
SELECT FDQUARTER('05-08-2018');
-- Result: 4/1/2018
```
### FILEMODIFIEDTIME(uri)
Returns the time stamp associated with the Date Modified of the relevant file.
-	**uri**: An absolute path pointing to a file on the local file system.
```sql
SELECT FILEMODIFIEDTIME('C:/Documents/myfile.txt');
-- Result: 6/25/2019 10:06:58 AM
```
### FROM_DAYS(datevalue)
Returns a date derived from the number of days after 1582-10-15 (based upon the Gregorian calendar). This will be equivalent to the MYSQL FROM_DAYS function.
-	**datevalue**: A integer value representing the number of days since 1582-10-15.
```sql
SELECT FROM_DAYS(736000);
-- Result: 2/6/2015
```
### GETDATE()
Returns the current time stamp of the database system as a datetime value. This value is equal to CURRENT_TIMESTAMP and SYSDATETIME, and is always in the local timezone.
```sql
SELECT GETDATE();
-- Result: 2018-02-01 03:04:05
```
### GETUTCDATE()
Returns the current time stamp of the database system formatted as a UTC datetime value. This value is equal to SYSUTCDATETIME.
```sql
SELECT GETUTCDATE();
-- For example, if the local timezone is Eastern European Time (GMT+2)
-- Result: 2018-02-01 05:04:05
```
### HOUR(date)
Returns the hour component from the provided datetime.
-	**date**: The datetime string that specifies the date.
```sql
SELECT HOUR('02-02-2020 11:30:00');
-- Result: 11
```
### ISDATE(date, [date_format])
Returns 1 if the value is a valid date, time, or datetime value; otherwise, 0.
-	**date**: The datetime string.
-	**date_format**: The optional datetime format.
```sql
SELECT ISDATE('2018-02-01', 'yyyy-MM-dd');
-- Result: 1
 
SELECT ISDATE('Not a date');
-- Result: 0
```
### LAST_WEEK()
Returns a time stamp equivalent to exactly one week before the current date.
```sql
SELECT LAST_WEEK(); //Assume the date is 3/17/2020 
-- Result: 3/10/2020
```
### LAST_MONTH()
Returns a time stamp equivalent to exactly one month before the current date.
```sql
SELECT LAST_MONTH(); //Assume the date is 3/17/2020
-- Result: 2/17/2020
```
### LAST_YEAR()
Returns a time stamp equivalent to exactly one year before the current date.
```sql
SELECT LAST_YEAR(); //Assume the date is 3/17/2020 
-- Result: 3/10/2019
```
### LDWEEK(date)
Returns the last day of the provided week.
-	**date**: The datetime string.
```sql
SELECT LDWEEK('02-02-2020');
-- Result: 2/8/2020
```
### LDMONTH(date)
Returns the last day of the provided month.
-	**date**: The datetime string.
```sql
SELECT LDMONTH('02-02-2020');
-- Result: 2/29/2020
```
### LDQUARTER(date)
Returns the last day of the provided quarter.
-	**date**: The datetime string.
```sql
SELECT LDQUARTER('02-02-2020');
-- Result: 3/31/2020
```
### MAKEDATE(year, days)
Returns a date value from a year and a number of days.
-	**year**: The year
-	**days**: The number of days into the year. Value must be greater than 0.
```sql
SELECT MAKEDATE(2020, 1);
-- Result: 2020-01-01
```
### MINUTE(date)
Returns the minute component from the provided datetime.
-	**date**: The datetime string that specifies the date.
```sql
SELECT MINUTE('02-02-2020 11:15:00');
-- Result: 15
```
### MONTH(date)
Returns the month component from the provided datetime.
-	**date**: The datetime string that specifies the date.
```sql
SELECT MONTH('02-02-2020');
-- Result: 2
```
### QUARTER(date)
Returns the quarter associated with the provided datetime.
-	**date**: The datetime string that specifies the date.
```sql
SELECT QUARTER('02-02-2020');
-- Result: 1
```
### SECOND(date)
Returns the second component from the provided datetime.
-	**date**: The datetime string that specifies the date.
```sql
SELECT SECOND('02-02-2020 11:15:23');
-- Result: 23
```
### SMALLDATETIMEFROMPARTS(integer_year, integer_month, integer_day, integer_hour, integer_minute)
Returns the datetime value for the specified date and time.
-	**year**: The integer expression specifying the year.
-	**month**: The integer expression specifying the month.
-	**day**: The integer expression specifying the day.
-	**hour**: The integer expression specifying the hour.
-	**minute**: The integer expression specifying the minute.
```sql
SELECT SMALLDATETIMEFROMPARTS(2018, 2, 1, 1, 2);
-- Result: 2018-02-01 01:02:00
```
### STRTODATE(string,format)
Parses the provided string value and returns the corresponding datetime.
-	**string**: The string value to be converted to datetime format.
-	**format**: A format string which describes how to interpret the first string input. A few special formats are available as well, including UNIX, UNIXMILIS, TICKS, and FILETICKS.
```sql
SELECT STRTODATE('03*04*2020','dd*MM*yyyy');
-- Result: 4/3/2020
```
### SYSDATETIME()
Returns the current time stamp as a datetime value of the database system. It is equal to GETDATE and CURRENT_TIMESTAMP, and is always in the local timezone.
```sql
SELECT SYSDATETIME();
-- Result: 2018-02-01 03:04:05
```
### SYSUTCDATETIME()
Returns the current system date and time as a UTC datetime value. It is equal to GETUTCDATE.
```sql
SELECT SYSUTCDATETIME();
-- For example, if the local timezone is Eastern European Time (GMT+2)
-- Result: 2018-02-01 05:04:05
```
### TIMEFROMPARTS(integer_hour, integer_minute, integer_seconds, integer_fractions, integer_precision)
Returns the time value for the specified time and with the specified precision.
-	**hour**: The integer expression specifying the hour.
-	**minute**: The integer expression specifying the minute.
-	**seconds**: The integer expression specifying the seconds.
-	**fractions**: The integer expression specifying the fractions of the second.
-	**precision**: The integer expression specifying the precision of the fraction.
```sql
SELECT TIMEFROMPARTS(1, 2, 3, 456, 3);
-- Result: 01:02:03.456
```
### TO_DAYS(date)
Returns the number of days since 0000-00-01. This will only return a value for dates on or after 1582-10-15 (based upon the Gregorian calendar). This will be equivalent to the MYSQL TO_DAYS function.
-	**date**: The datetime string that specifies the date.
```sql
SELECT TO_DAYS('02-06-2015');
-- Result: 736000
```
### WEEK(date)
Returns the week (of the year) associated with the provided datetime.
-	**date**: The datetime string that specifies the date.
```sql
SELECT WEEK('02-17-2020 11:15:23');
-- Result: 8
```
### YEAR(date)
Returns the integer that specifies the year of the specified date.
-	**date**: The datetime string.
```sql
SELECT YEAR('2018-02-01');
-- Result: 2018
```

[Jump to top](https://github.com/CDataSoftware/Klenty-API-Profile/blob/main/README.md#table-of-contents)
</br>
<br>

## SQL Compliance
### ABS ( numeric_expression )
Returns the absolute (positive) value of the specified numeric expression.
-	**numeric_expression**: The expression of an indeterminate numeric data type except for the bit data type.
```sql
SELECT ABS(15);
-- Result: 15
 
SELECT ABS(-15);
-- Result: 15
```
### ACOS ( float_expression )
Returns the arc cosine, the angle in radians whose cosine is the specified float expression.
-	**float_expression**: The float expression that specifies the cosine of the angle to be returned. Values outside the range from -1 to 1 return null.
```sql
SELECT ACOS(0.5);
-- Result: 1.0471975511966
```
### ASIN ( float_expression )
Returns the arc sine, the angle in radians whose sine is the specified float expression.
-	**float_expression**: The float expression that specifies the sine of the angle to be returned. Values outside the range from -1 to 1 return null.
```sql
SELECT ASIN(0.5);
-- Result: 0.523598775598299
```
### ATAN ( float_expression )
Returns the arc tangent, the angle in radians whose tangent is the specified float expression.
-	**float_expression**: The float expression that specifies the tangent of the angle to be returned.
```sql
SELECT ATAN(10);
-- Result: 1.47112767430373
```
### ATN2 ( float_expression1 , float_expression2 )
Returns the angle in radians between the positive x-axis and the ray from the origin to the point (y, x) where x and y are the values of the two specified float expressions.
-	**float_expression1**: The float expression that is the y-coordinate.
-	**float_expression2**: The float expression that is the x-coordinate.
```sql
SELECT ATN2(1, 1);
-- Result: 0.785398163397448
```
### CEILING ( numeric_expression ) or CEIL( numeric_expression )
Returns the smallest integer greater than or equal to the specified numeric expression.
-	**numeric_expression**: The expression of an indeterminate numeric data type except for the bit data type.
```sql
SELECT CEILING(1.3);
-- Result: 2
 
SELECT CEILING(1.5);
-- Result: 2
 
SELECT CEILING(1.7);
-- Result: 2
```
### COS ( float_expression )
Returns the trigonometric cosine of the specified angle in radians in the specified expression.
-	**float_expression**: The float expression of the specified angle in radians.
```sql
SELECT COS(1);
-- Result: 0.54030230586814
```
### COT ( float_expression )
Returns the trigonometric cotangent of the angle in radians specified by float_expression.
-	**float_expression**: The float expression of the angle in radians.
```sql
SELECT COT(1);
-- Result: 0.642092615934331
```
### DEGREES ( numeric_expression )
Returns the angle in degrees for the angle specified in radians.
-	**numeric_expression**: The angle in radians, an expression of an indeterminate numeric data type except for the bit data type.
```sql
SELECT DEGREES(3.1415926);
-- Result: 179.999996929531
```
### EXP ( float_expression )
Returns the exponential value of the specified float expression. For example, EXP(LOG(20)) is 20.
-	**float_expression**: The float expression.
```sql
SELECT EXP(2);
-- Result: 7.38905609893065
```
### EXPR ( expression )
Evaluates the expression.
-	**expression**: The expression. Operators allowed are +, -, *, /, ==, !=, >, <, >=, and <=.
```sql
SELECT EXPR('1 + 2 * 3');
-- Result: 7
 
SELECT EXPR('1 + 2 * 3 == 7');
-- Result: true
```
### FLOOR ( numeric_expression )
Returns the largest integer less than or equal to the numeric expression.
-	**numeric_expression**: The expression of an indeterminate numeric data type except for the bit data type.
```sql
SELECT FLOOR(1.3);
-- Result: 1
 
SELECT FLOOR(1.5);
-- Result: 1
 
SELECT FLOOR(1.7);
-- Result: 1
```
### GREATEST(int1,int2,....)
Returns the greatest of the supplied integers.
```sql
SELECT GREATEST(3,5,8,10,1)
-- Result: 10
```          
### HEX(value)
Returns a the equivalent hex for the input value.
-	**value**: A string or numerical value to be converted into hex.
```sql
SELECT HEX(866849198);
-- Result: 33AB11AE
 
SELECT HEX('Sample Text');
-- Result: 53616D706C652054657874
```
### LEAST(int1,int2,....)
Returns the least of the supplied integers.
```sql
SELECT LEAST(3,5,8,10,1)
-- Result: 1
```           
### LOG ( float_expression [, base ] )
Returns the natural logarithm of the specified float expression.
-	**float_expression**: The float expression.
-	**base**: The optional integer argument that sets the base for the logarithm.
```sql
SELECT LOG(7.3890560);
-- Result: 1.99999998661119
```
### LOG10 ( float_expression )
Returns the base-10 logarithm of the specified float expression.
-	**float_expression**: The expression of type float.
```sql
SELECT LOG10(10000);
-- Result: 4
```
### MOD(dividend,divisor)
Returns the integer value associated with the remainder when dividing the dividend by the divisor.
-	**dividend**: The number to take the modulus of.
-	**divisor**: The number to divide the dividend by when determining the modulus.
```sql
SELECT MOD(10,3);
-- Result: 1
```
### NEGATE(real_number)
Returns the opposite to the real number input.
-	**real_number**: The real number to find the opposite of.
```sql
SELECT NEGATE(10);
-- Result: -10
 
SELECT NEGATE(-12.4)
--Result: 12.4
```
### PI ( )
Returns the constant value of pi.
```sql
SELECT PI()
-- Result: 3.14159265358979
```
### POWER ( float_expression , y )
Returns the value of the specified expression raised to the specified power.
-	**float_expression**: The float expression.
-	**y**: The power to raise float_expression to.
```sql
SELECT POWER(2, 10);
-- Result: 1024
 
SELECT POWER(2, -2);
-- Result: 0.25
```
### RADIANS ( float_expression )
Returns the angle in radians of the angle in degrees.
-	**float_expression**: The degrees of the angle as a float expression.
```sql
SELECT RADIANS(180);
-- Result: 3.14159265358979
```
### RAND ( [ integer_seed ] )
Returns a pseudorandom float value from 0 through 1, exclusive.
-	**seed**: The optional integer expression that specifies the seed value. If seed is not specified, a seed value at random will be assigned.
```sql
SELECT RAND();
-- This result may be different, since the seed is randomized
-- Result: 0.873159630165044
 
SELECT RAND(1);
-- This result will always be the same, since the seed is constant
-- Result: 0.248668584157093
```
### ROUND ( numeric_expression [ ,integer_length] [ ,function ] )
Returns the numeric value rounded to the specified length or precision.
-	**numeric_expression**: The expression of a numeric data type.
-	**length**: The optional precision to round the numeric expression to. When this is ommitted, the default behavior will be to round to the nearest whole number.
-	**function**: The optional type of operation to perform. When the function parameter is omitted or has a value of 0 (default), numeric_expression is rounded. When a value other than 0 is specified, numeric_expression is truncated.
```sql
SELECT ROUND(1.3, 0);
-- Result: 1
 
SELECT ROUND(1.55, 1);
-- Result: 1.6
 
SELECT ROUND(1.7, 0, 0);
-- Result: 2
 
SELECT ROUND(1.7, 0, 1);
-- Result: 1
 
SELECT ROUND (1.24);
-- Result: 1.0
```
### SIGN ( numeric_expression )
Returns the positive sign (1), 0, or negative sign (-1) of the specified expression.
-	**numeric_expression**: The expression of an indeterminate data type except for the bit data type.
```sql
SELECT SIGN(0);
-- Result: 0
 
SELECT SIGN(10);
-- Result: 1
 
SELECT SIGN(-10);
-- Result: -1
```
### SIN ( float_expression )
Returns the trigonometric sine of the angle in radians.
-	**float_expression**: The float expression specifying the angle in radians.
```sql
SELECT SIN(1);
-- Result: 0.841470984807897
```
### SQRT ( float_expression )
Returns the square root of the specified float value.
-	**float_expression**: The expression of type float.
```sql
SELECT SQRT(100);
-- Result: 10
```
### SQUARE ( float_expression )
Returns the square of the specified float value.
-	**float_expression**: The expression of type float.
```sql
SELECT SQUARE(10);
-- Result: 100
 
SELECT SQUARE(-10);
-- Result: 100
```
### TAN ( float_expression )
Returns the tangent of the input expression.
-	**float_expression**: The expression of type float.
```sql
SELECT TAN(1);
-- Result: 1.5574077246549
```
### TRUNC(decimal_number,precision)
Returns the supplied decimal number truncated to have the supplied decimal precision.
-	**decimal_number**: The decimal value to truncate.
-	**precision**: The number of decimal places to truncate the decimal number to.
```sql
SELECT TRUNC(10.3423,2);
-- Result: 10.34
```

[Jump to top](https://github.com/CDataSoftware/Klenty-API-Profile/blob/main/README.md#table-of-contents)
</br>
<br>

## SQL Compliance
To execute stored procedures, you can use EXECUTE or EXEC statements.  

EXEC and EXECUTE assign stored procedure inputs, referenced by name, to values or parameter names.

### Stored Procedure Syntax
To execute a stored procedure as an SQL statement, use the following syntax:
```sql
{ EXECUTE | EXEC } <stored_proc_name>
{
  [ @ ] <input_name> = <expression>
} [ , ... ]
 
<expression> ::=
  | @ <parameter>
  | ?
  | <literal>
```

### Example Statements
Reference stored procedure inputs by name:

`EXECUTE my_proc @second = 2, @first = 1, @third = 3;`

Execute a parameterized stored procedure statement:

`EXECUTE my_proc second = @p1, first = @p2, third = @p3;`

[Jump to top](https://github.com/CDataSoftware/Klenty-API-Profile/blob/main/README.md#table-of-contents)
</br>
<br>

## Schema Discovery
The API Profile supports schema discovery using common classes or using SQL queries to the available system tables. The common classes enable access to schema information, connection property information, and information on the columns returned.

### Using ADO.NET
See [ADO.NET](https://github.com/CDataSoftware/Klenty-API-Profile/blob/main/README.md#schema-discovery-2) for information on how you can use ADO.NET schema collections to retrieve schema and connection property information, including table and column listings. Invoke the GetSchema method of the APIConnection class to access the metadata.

### Using JDBC
See [JDBC](https://github.com/CDataSoftware/Klenty-API-Profile/blob/main/README.md#schema-discovery-3) for information on how you can use JDBC interfaces to access schema information, connection property metadata, and result set metadata. The driver implements the standard interfaces as defined in the JDBC 4.0 specification.

### Using SQL
Query the [System Tables](https://github.com/CDataSoftware/Klenty-API-Profile/blob/main/README.md#schema-discovery-4) to access additional metadata, such as data source capabilities. These system tables can be used in any edition of the API driver.

### Automatic Schema Discovery
Schema discovery is obtained dynamically for the API Profile when used in the CData ODBC Driver, PowerBI Connector, SSIS Component or the Excel Add-in. To load the available tables, columns and procedures, simply load the connection in any application compatible with the connector.

[Jump to top](https://github.com/CDataSoftware/Klenty-API-Profile/blob/main/README.md#table-of-contents)
</br>
<br>

## Schema Discovery
The API Profile supports standard ADO.NET schemas to access profile metadata.

### Retrieving the Table Listing
The Tables schema collection lists all tables in the database. To retrieve the Tables schema collection, call the GetSchema method of the APIConnection class.
#### **C#**
```c#
String connectionString = "Profile=C:\profiles\Klenty.apip;ProfileSettings='APIKey=my_authtoken;AuthScheme=None;User=my_user;'";
 
using (APIConnection conn = new APIConnection(connectionString)) {
  conn.Open();
  DataTable databaseSchema = conn.GetSchema("Tables");
  foreach (DataRow row in databaseSchema.Rows) {
    Console.WriteLine(row["TABLE_NAME"]);
  }
}
```
#### Columns Returned
The Tables schema collection returns the following columns.

| **Column Name**   | **Data Type**     | **Description**                           |
|:--------------|:--------------|:--------------------------------------|
| TABLE_CATALOG | System.String | The database that contains the table. |
| TABLE_SCHEMA  | System.String | The schema that contains the table.   |
| TABLE_NAME    | System.String | The table name.                       |
| TABLE_TYPE    | System.String | The table type.                       |

### Retrieving Column Metadata
Call the GetSchema method of the APIConnection class to retrieve the Columns or ViewColumns schema collections. You can restrict results by table name, as shown in the example below.
#### **C#**
```c#
string connectionString = "Profile=C:\profiles\Klenty.apip;ProfileSettings='APIKey=my_authtoken;AuthScheme=None;User=my_user;'";
 
using (APIConnection conn = new APIConnection(connectionString)) {
  conn.Open();
  DataTable databaseSchema = conn.GetSchema("Columns", new string[] {"CompanyCadences"});
  foreach (DataRow column in databaseSchema.Rows) {
    Console.WriteLine(column["COLUMN_NAME"]);
    Console.WriteLine(column["IS_KEY"]);
    Console.WriteLine(column["DATA_TYPE"]);
  }
}
```
#### Columns Returned
The Columns and ViewColumns schema collections and DataTables returned from the query contain the following columns.

| **Column Name**          | **Data Type**  | **Description**                                                                                                          |
|:--------------------------|:----------------|:--------------------------------------------------------------------------------------------------------------------------|
| TABLE_CATALOG            | System.String  | The database containing the table.                                                                                       |
| TABLE_SCHEMA             | System.String  | The schema containing the table.                                                                                         |
| TABLE_NAME               | System.String  | The table containing the column.                                                                                         |
| COLUMN_NAME              | System.String  | The column name.                                                                                                         |
| ORDINAL_POSITION         | System.Int32   | The sequence number of the column.                                                                                       |
| COLUMN_DEFAULT           | System.String  | The default value of the column.                                                                                         |
| IS_NULLABLE              | System.String  | Whether the column allows null values. The value is YES or NO.                                                           |
| DATA_TYPE                | System.String  | The column data type.                                                                                                    |
| CHARACTER_MAXIMUM_LENGTH | System.Int32   | The maximum length in characters of a column with character data.                                                        |
| NUMERIC_PRECISION        | System.Int32   | The maximum number of digits allowed for numeric data.                                                                   |
| NUMERIC_SCALE            | System.Int32   | The maximum column scale or the number of digits to the right of the decimal point in numeric data.                      |
| DATETIME_PRECISION       | System.Int32   | Returns the precision in fractional seconds if the parameter type is datetime or smalldatetime. Otherwise, returns NULL. |
| CHARACTER_SET_NAME       | System.String  | The name of the character set for a column with character data.                                                          |
| COLUMN_COMMENT           | System.String  | A brief description of the column.                                                                                       |
| IS_KEY                   | System.Boolean | Whether the column is the primary key of the table referenced by TABLE_NAME                                              |
| IS_READONLY              | System.Boolean | Whether the column is read-only                                                                                          |
| PROVIDER_TYPE            | System.Type    | Indicates the appropriate data type dependent on the language you are executing it                                       |

[Jump to top](https://github.com/CDataSoftware/Klenty-API-Profile/blob/main/README.md#table-of-contents)
</br>
<br>

## Schema Discovery
The API Profile supports standard JDBC schemas to access profile metadata.

### Retrieving the Table Listing
You can use the getTables method of the DatabaseMetaData interface to retrieve a list of tables:
```java
String connectionString = "jdbc:api:Profile=C:\profiles\Klenty.apip;ProfileSettings='APIKey=my_authtoken;AuthScheme=None;User=my_user;'";
 
Connection conn = DriverManager.getConnection(connectionString);
DatabaseMetaData table_meta = conn.getMetaData();
ResultSet rs=table_meta.getTables(null, null, "%", null); 
while(rs.next()){
  System.out.println(rs.getString("TABLE_NAME"));
}
```
The getTables method returns the following columns:

| **Column Name** | **Data Type** | **Description**        |
|:----------------|:--------------|:-----------------------|
| TABLE_CAT       | String        | The table catalog.     |
| TABLE_SCHEM    | String        | The table schema.      |
| TABLE_NAME      | String        | The table name.        |
| TABLE_TYPE      | String        | The table type.        |
| REMARKS         | String        | The table description. |

### Retrieving Column Metadata
You can use the getColumns method of the DatabaseMetaData interface to retrieve column information. You can restrict the results by the table name. The code example below retrieves the column names for the CompanyCadences table:
```java
String connectionString = "jdbc:api:Profile=C:\profiles\Klenty.apip;ProfileSettings='APIKey=my_authtoken;AuthScheme=None;User=my_user;'";
 
Connection conn = DriverManager.getConnection(connectionString);
DatabaseMetaData table_meta = conn.getMetaData();
ResultSet rs = table_meta.getColumns(null,null,"CompanyCadences", null);
while(rs.next()){
  System.out.println(rs.getString("COLUMN_NAME"));
}
```
The getColumns method returns the following columns:

| **Column Name**    | **Data Type**   | **Description**         |                                                                                                                                        
|:--------------------|:---------------|:----------------------------------------------------------------------------------------------------------------------------------------------------|
| TABLE_CAT          | String        | The database name.                                                                                                                                              |
| TABLE_SCHEM        | String        | The table schema.                                                                                                                                               |
| TABLE_NAME         | String        | The table name.                                                                                                                                                 |
| COLUMN_NAME        | String        | The column name.                                                                                                                                                |
| DATA_TYPE          | int           | The data type identified by the value of a constant defined in java.sql.Types.                                                                                  |
| TYPE_NAME          | String        | The data type name used by the provider.                                                                                                                        |
| COLUMN_SIZE        | int           | The length in characters of the column or the numeric precision.                                                                                                |
| BUFFER_LENGTH      | int           | The buffer length.                                                                                                                                              |
| DECIMAL_DIGITS     | int           | The column scale or number of digits to the right of the decimal point.                                                                                         |
| NUM_PREC_RADIX     | int           | The radix, or base.                                                                                                                                             |
| NULLABLE           | int           | Whether the column can contain null as defined by the following JDBC DatabaseMetaData constraints: columnNoNulls (0) or commonNullable (1)                      |
| REMARKS            | String        | The column description                                                                                                                                          |
| COLUMN_DEF         | String        | The default value of the column.                                                                                                                                |
| SQL_DATA_TYPE      | int           | Reserved by the specification.                                                                                                                                  |
| SQL_DATETIME_SUB   | int           | Reserved by the specification.                                                                                                                                  |
| CHAR_OCTET_LENGTH  | int           | The maximum length of binary and character-based columns.                                                                                                       |
| ORDINAL_POSITION   | int           | The column index, starting at 1.                                                                                                                                |
| IS_NULLABLE        | String        | Whether a null value is allowed: YES or NO.                                                                                                                     |
| SCOPE_CATALOG      | String        | The table catalog that is the scope of a reference attribute.                                                                                                   |
| SCOPE_SCHEMA       | String        | The table schema that is the scope of a reference attribute.                                                                                                    |
| SCOPE_TABLE        | String        | The table name that is the scope of a reference attribute.                                                                                                      |
| SOURCE_DATA_TYPE   | int           | The source type of a distinct type. Or a user generated Ref type. If DATA_TYPE is not distinct, the value is null. If a user generated-Ref, this value is null. |
| IS_AUTOINCREMENT   | String        | Whether the common value is assigned by API in fixed increments.                                                                                                |
| IS_GENERATEDCOLUMN | String        | Whether the column is generated: YES or NO.                                                                                                                     |
| ISREADONLY         | boolean       | Whether the column is read-only.                                                                                                                                |
| ISKEY              | boolean       | Whether the column is a key.                                                                                                                                    |

[Jump to top](https://github.com/CDataSoftware/Klenty-API-Profile/blob/main/README.md#table-of-contents)
</br>
<br>

## Schema Discovery
Schema information is available in the form of system tables which can be queried to display schema information and available data source functionality. The included system tables are listed here.

### Schema Tables
The following tables return database metadata for API:
-	[sys_tables](https://github.com/CDataSoftware/Klenty-API-Profile/blob/main/README.md#schema-discovery-5): Lists the available tables.
-	[sys_tablecolumns](https://github.com/CDataSoftware/Klenty-API-Profile/blob/main/README.md#schema-discovery-6): Describes the columns of the available tables.
-	[sys_procedures](https://github.com/CDataSoftware/Klenty-API-Profile/blob/main/README.md#schema-discovery-7): Describes the available stored procedures.

[Jump to top](https://github.com/CDataSoftware/Klenty-API-Profile/blob/main/README.md#table-of-contents)
</br>
<br>

## Schema Discovery
Lists the available tables.

The following query retrieves the available tables:
```sql
SELECT * FROM sys_tables
```
### Columns

| **Name**    | **Type** | **Description**                    |
|:-------------|:----------|:------------------------------------|
| CalalogName | String   | The database containing the table. |
| SchemaName  | String   | The schema containing the table.   |
| TableName   | String   | The name of the table.             |
| TableType   | String   | The table type.                    |
| Description | String   | The description of the table.      |
| IsUpdateable| String   | Shows if the data can be updated.  |

[Jump to top](https://github.com/CDataSoftware/Klenty-API-Profile/blob/main/README.md#table-of-contents)
</br>
<br>


## Schema Discovery
Describes the columns of the available tables.

The following query returns the columns and data types for the CompanyCadences table:
```sql
SELECT ColumnName, DataTypeName FROM sys_tablecolumns WHERE TableName='CompanyCadences'
```
### Columns
| **Name**          | **Type** | **Description**                                                                                                 |
|:-------------------|:----------|:-----------------------------------------------------------------------------------------------------------------|
| CatalogName       | String   | The name of the database containing the table.                                                                  |
| SchemaName        | String   | The schema containing the table.                                                                                |
| TableName         | String   | The name of the table containing the column.                                                                    |
| ColumnName        | String   | The column name.                                                                                                |
| DataTypeName      | String   | The data type name.                                                                                             |
| DataType          | Int32    | An integer indicating the data type. The value is determined at run time based on the environment.              |
| Length            | Int32    | The length in character of the column or the numeric precision.                                                 |
| NumericPrecision  | Int32    | The maximum number of digits in numeric data. The column length in characters for character and date-time data. |
| NumericScale      | Int32    | The column scale or number of digits to the right of the decimal point.                                         |
| IsNullable        | Boolean  | Whether the column can contain null.                                                                            |
| Description       | String   | A brief description of the column.                                                                              |
| Ordinal           | Int32    | The sequence number of the column.                                                                              |
| IsAutoIncrement   | String   | Whether the column value is offered in fixed increments.                                                        |
| IsGeneratedColumn | String   | Whether the column is generated.                                                                                |
| IsReadOnly        | Boolean  | Whether the column is read-only.                                                                                |
| IsKey             | Boolean  | Whether the column is a primary key.                                                                            |
| IsHidden          | Boolean  | Whether the column is hidden.                                                                                   |

[Jump to top](https://github.com/CDataSoftware/Klenty-API-Profile/blob/main/README.md#table-of-contents)
</br>
<br>

## Schema Discovery
Lists the available stored procedures.

The following query retrieves the available stored procedures:
```sql
SELECT * FROM sys_procedures
```
### Columns
| **Name**      | **Type** | **Description**                               |
|---------------|----------|-----------------------------------------------|
| CatalogName   | String   | The database containing the stored procedure. |
| SchemaName    | String   | The schema containing the stored procedure.   |
| ProcedureName | String   | The name of the stored procedure.             |
| Description   | String   | A description of the stored procedure.        |

[Jump to top](https://github.com/CDataSoftware/Klenty-API-Profile/blob/main/README.md#table-of-contents)
</br>
<br>

## Klenty Tables
The provider models the data in API into a list of tables that can be queried using standard SQL statements.

Generally, querying API tables is the same as querying a table in a relational database. Sometimes there are special cases, for example, including a certain column in the WHERE clause might be required to get data for certain columns in the table. This is typically needed for situations where a separate request must be made for each row to get certain columns. These types of situations are clearly documented at the top of the table page linked below.

### Klenty Tables
| **Name**        | **Description**                    |
|:-----------------|:------------------------------------|
| [CompanyCadences](https://github.com/CDataSoftware/Klenty-API-Profile/blob/main/README.md#companycadences) | Returns a table containing all cadences in that team. |
| [Lists](https://github.com/CDataSoftware/Klenty-API-Profile/blob/main/README.md#lists)           | Returns a table containing the Prospect Lists created by the team.            |
| [UserCadences](https://github.com/CDataSoftware/Klenty-API-Profile/blob/main/README.md#usercadences)    | It expects the email address of the user as an input and will return an object containing cadences that belong to that user. |
| [ProspectByList](https://github.com/CDataSoftware/Klenty-API-Profile/blob/main/README.md#prospectbylist)  | It expects a Prospect List name and will return an object containing all the prospects in the list. You can also provide start & limit values to filter the response.            |
| [ProspectDetailsByEmail](https://github.com/CDataSoftware/Klenty-API-Profile/blob/main/README.md#prospectdetailsbyemail) | It expects an email address and will return an object containing details of the Prospect who matches that email address. |
| [ProspectStatusByEmail](https://github.com/CDataSoftware/Klenty-API-Profile/blob/main/README.md#prospectstatusbyemail)           | It expects the email address of the Prospect, and will return an object containing the status of the Prospect who matches the email address.            |
| [ProspectDetailsWithCustomFields](https://github.com/CDataSoftware/Klenty-API-Profile/blob/main/README.md#prospectdetailswithcustomfields) | Returns the value of custom fields for the specified Prospect along with other fields. |
| [ProspectStatusByID](https://github.com/CDataSoftware/Klenty-API-Profile/blob/main/README.md#prospectstatusbyid)           | It expects an ID of a Prospect and will return a table containing the status of that Prospect.            |
| [ProspectByCreationDate](https://github.com/CDataSoftware/Klenty-API-Profile/blob/main/README.md#prospectbycreationdate) | It expects the start date & end date and returns the prospects created between those dates. If the end date is not given, the endpoint considers the present date as the end date. The end date should be ahead of the start date. |
| [ProspectByLastUpdatedDate](https://github.com/CDataSoftware/Klenty-API-Profile/blob/main/README.md#prospectbylastupdateddate)           | Returns prospects based on the last date of update (last interaction with the prospect).            |

[Jump to top](https://github.com/CDataSoftware/Klenty-API-Profile/blob/main/README.md#table-of-contents)
</br>
<br>

## CompanyCadences
Returns a table containing all cadences in that team.

The following query retrieves all the candence data from Klenty:
```sql
SELECT * FROM CompanyCadences
```

### Columns
| **Name**    | **Type** | **References** |
|-------------|----------|----------------|
| id[KEY]     | string   |                |
| name        | string   |                |
| owner       | string   |                |
| isActive    | string   |                |
| createdDate | datetime |                |

[Jump to top](https://github.com/CDataSoftware/Klenty-API-Profile/blob/main/README.md#table-of-contents)
</br>
<br>

## Lists
Returns a table containing the Prospect Lists created by the team.

The following query retrieves all the prospect lists from Klenty:
```sql
SELECT * FROM Lists
```

### Columns
| **Name**    | **Type** | **References** |
|-------------|----------|----------------|
| id[KEY]     | string   |                |
| name        | string   |                |

[Jump to top](https://github.com/CDataSoftware/Klenty-API-Profile/blob/main/README.md#table-of-contents)
</br>
<br>

## UserCadences
It expects the email address of the user as an input and will return an object containing cadences that belong to that user.

The following query retrieves all the user related cadences from Klenty:
```sql
SELECT * FROM UserCadences WHERE owner = 'test@cdata.com'
```

### Columns
| **Name**    | **Type** | **References** |
|-------------|----------|----------------|
| id[KEY]     | string   |                |
| name        | string   |                |
| owner       | string   |                |
| isActive    | string   |                |
| createdDate | datetime |                |

[Jump to top](https://github.com/CDataSoftware/Klenty-API-Profile/blob/main/README.md#table-of-contents)
</br>
<br>

## ProspectByList
It expects a Prospect List name and will return an object containing all the prospects in the list. You can also provide start & limit values to filter the response.

The following query retrieves all the prospects in a list from Klenty:
```sql
SELECT * FROM ProspectByList WHERE List = 'List_Name'
```

### Columns
| **Name**    | **Type** | **References** |
|-------------|----------|----------------|
| id[KEY]     | string   |                |
| FullName    | string   |                |
| FirstName   | string   |                |
| LastName    | string   |                |
| Email       | string   |                |
| listName    | string   |                |
| Tags        | string   |                |
| assignTo    | string   |                |
| Company     | string   |                |

[Jump to top](https://github.com/CDataSoftware/Klenty-API-Profile/blob/main/README.md#table-of-contents)
</br>
<br>

## ProspectDetailsByEmail
It expects an email address and will return an object containing details of the Prospect who matches that email address. 

The following query retrieves all the prospect details based on an email address from Klenty:
```sql
SELECT * FROM ProspectDetailsByEmail where Email = 'test@cdata.com'
```

### Columns
| **Name**    | **Type** | **References** |
|-------------|----------|----------------|
| id[KEY]     | string   |                |
| Email    | string   |                |
| FirstName   | string   |                |
| Company    | string   |                |
| Phone       | string   |                |
| FullName    | string   |                |
| LastName        | string   |                |
| MiddleName    | string   |                |
| Account     | string   |                |
| Department        | string   |                |
| CompanyDomain     | string   |                |
| Title    | string   |                |
| TwitterId   | string   |                |
| CompanyPhone    | string   |                |
| CompanyEmail       | string   |                |
| LinkedinURL    | string   |                |
| City        | string   |                |
| Country    | string   |                |
| Location     | string   |                |
| List        | string   |                |
| Tags    | string   |                |
| assignTo     | string   |                |

[Jump to top](https://github.com/CDataSoftware/Klenty-API-Profile/blob/main/README.md#table-of-contents)
</br>
<br>

## ProspectStatusByEmail
It expects the email address of the Prospect, and will return an object containing the status of the Prospect who matches the email address.

The following query retrieves all the prospect status based on an email address from Klenty:
```sql
SELECT * FROM ProspectStatusByEmail WHERE Email = 'test@cdata.com'
```

### Columns
| **Name**    | **Type** | **References** |
|-------------|----------|----------------|
| cadenceStatus     | string   |                |
| prospectStatus    | string   |                |

[Jump to top](https://github.com/CDataSoftware/Klenty-API-Profile/blob/main/README.md#table-of-contents)
</br>
<br>

## ProspectDetailsWithCustomFields
Returns the value of custom fields for the specified Prospect along with other fields. 

The following query retrieves the value of custom fields for a prospect based on an email address from Klenty:
```sql
SELECT * FROM ProspectDetailswithCustomFields WHERE Email = 'test@cdata.com'
```

### Columns
| **Name**    | **Type** | **References** |
|-------------|----------|----------------|
| id[KEY]     | string   |                |
| Email    | string   |                |
| FirstName   | string   |                |
| Company    | string   |                |
| Phone       | string   |                |
| FullName    | string   |                |
| LastName        | string   |                |
| MiddleName    | string   |                |
| Account     | string   |                |
| Department        | string   |                |
| CompanyDomain     | string   |                |
| Title    | string   |                |
| TwitterId   | string   |                |
| CompanyPhone    | string   |                |
| CompanyEmail       | string   |                |
| LinkedinURL    | string   |                |
| City        | string   |                |
| Country    | string   |                |
| Location     | string   |                |
| List        | string   |                |
| Tags    | string   |                |
| CustomFields    | string   |                |
| assignTo     | string   |                |

[Jump to top](https://github.com/CDataSoftware/Klenty-API-Profile/blob/main/README.md#table-of-contents)
</br>
<br>

## ProspectStatusByID
It expects an ID of a Prospect and will return an table containing the status of that Prospect.  

The following query retrieves prospect status based on their ID from Klenty:
```sql
SELECT * FROM ProspectStatusByID WHERE id = 'test@cdata.com'
```

### Columns
| **Name**    | **Type** | **References** |
|-------------|----------|----------------|
| cadenceStatus     | string   |                |
| prospectStatus    | string   |                |

[Jump to top](https://github.com/CDataSoftware/Klenty-API-Profile/blob/main/README.md#table-of-contents)
</br>
<br>

## ProspectByCreationDate
It expects the start date & end date and returns the prospects created between those dates. If the end date is not given, the endpoint considers the present date as the end date. The end date should be ahead of the start date.  

The following query retrieves prospects created between specified dates from Klenty:
```sql
SELECT * FROM ProspectByCreationDate WHERE startDate='yyyy/mm/dd' AND endDate = 'yyyy/mm/dd'
```

### Columns
| **Name**    | **Type** | **References** |
|-------------|----------|----------------|
| id[KEY]     | string   |                |
| Email    | string   |                |
| FirstName   | string   |                |
| Company    | string   |                |
| Phone       | string   |                |
| FullName    | string   |                |
| LastName        | string   |                |
| MiddleName    | string   |                |
| Account     | string   |                |
| Department        | string   |                |
| CompanyDomain     | string   |                |
| Title    | string   |                |
| TwitterId   | string   |                |
| CompanyPhone    | string   |                |
| CompanyEmail       | string   |                |
| LinkedinURL    | string   |                |
| City        | string   |                |
| Country    | string   |                |
| Location     | string   |                |
| List        | string   |                |
| Tags    | string   |                |
| assignTo     | string   |                |

[Jump to top](https://github.com/CDataSoftware/Klenty-API-Profile/blob/main/README.md#table-of-contents)
</br>
<br>

## ProspectByLastUpdatedDate
Returns prospects based on the last date of update (last interaction with the prospect).  

The following query retrieves prospect details based on its last date of update from Klenty:
```sql
SELECT * FROM ProspectByLastUpdatedDate WHERE startdate ='yyyy/mm/dd' AND enddate = 'yyyy/mm/dd'
```

### Columns
| **Name**    | **Type** | **References** |
|-------------|----------|----------------|
| id[KEY]     | string   |                |
| Email    | string   |                |
| FirstName   | string   |                |
| Company    | string   |                |
| Phone       | string   |                |
| FullName    | string   |                |
| LastName        | string   |                |
| MiddleName    | string   |                |
| Account     | string   |                |
| Department        | string   |                |
| CompanyDomain     | string   |                |
| Title    | string   |                |
| TwitterId   | string   |                |
| CompanyPhone    | string   |                |
| CompanyEmail       | string   |                |
| LinkedinURL    | string   |                |
| City        | string   |                |
| Country    | string   |                |
| Location     | string   |                |
| List        | string   |                |
| Tags    | string   |                |
| assignTo     | string   |                |

[Jump to top](https://github.com/CDataSoftware/Klenty-API-Profile/blob/main/README.md#table-of-contents)
</br>
