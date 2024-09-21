# JMeter
 JMeter Examples

# Core concepts demonstrated:
- Record route calls via Blazemeter Chrome extension
- Obtain JWT to address auth in subsequent api calls
- Define global values via User Defined Variables Config Element, this allows them to accesible to ALL thread groups.
- Use CSV DataSet Config element to read data from CSV file to be used in route calls
- Use Random Number config element.  This value is appended to form data to create unique instances of data
- Leverage functionality to upload a local file to be used for route call (requires Working directory configuration)
- Extract data from JSON response to be used in subsequent route calls
- Utilize JSR223 Postprocess to leveage custom Groovy code to create a NEW CSV file that will contain data to be used in subsequent route calls
        processor name in .jmx file is "Create file containing ids of creates locations"

- Utilize Beanshell Assertion config element to progmatically define and set new variables



 
 
