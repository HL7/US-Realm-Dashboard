# Obtaining Spec Screenshots

1. Install Python (3) for your operating system
2. Obtain a [Google PageSpeed API key](https://developers.google.com/speed/docs/insights/v5/get-started)
3. Insert your API key into line 33 of `get-screenshot.py`

`key = "YOUR KEY HERE"`

3. Run the `get-screenshot.py` program as follows:

`python3 get-screenshot.py -s {INSERT URL FOR SPEC HERE}`

for example:

`python3 get-screenshot.py -s https://build.fhir.org/ig/HL7/home-lab-report/`

