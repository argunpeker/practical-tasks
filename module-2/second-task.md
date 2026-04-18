ID_2.1 My Scheduled Reports: Export

Icon Button:

Is the button clickable? → Functional Testing
Is the export icon visible and easily discoverable for authorized users? → Functional Testing (UI) + Usability Testing
Can authorized users successfully interact with (click) the icon? → Functional Testing
Does the export module open within an acceptable response time after clicking the icon? → Performance Testing
Does the feature work consistently across different browsers and operating systems? → Compatibility Testing
Is the icon hidden or disabled for unauthorized users? → Functional Testing + Security (Authorization Testing)
Do unauthorized users receive an appropriate error message when accessing the page? → Functional Testing + Security Testing
Is the error message clear and understandable? → Usability Testing
What happens if the error message is not displayed? → Negative Testing (Functional)
Does clicking the icon successfully open the pop-up? → Functional Testing 

Pop-up:

Does the pop-up open within an acceptable response time? → Performance Testing
Are all required 3 export options displayed? → Functional Testing
Do all available options function correctly? → Functional Testing
Are the options clear and understandable for users? → Usability Testing
Are the option labels correctly displayed and mapped? → Functional Testing (UI Validation)
Do all document formats behave correctly when selected? → Functional Testing
Is behavior consistent across different browsers? → Compatibility Testing
Does the Unicode option work correctly and render properly? → Functional Testing


ID_2.2 Report Export: File Format Availability

File Format Availability:

Is the report size calculated correctly? → Functional Testing
Is the report size calculation completed within acceptable time limits? → Performance Testing
Is report size pre-calculated before the user opens the Export module? → Functional Testing
What happens if the report size is not yet calculated when the Export module is opened? → Negative Testing (Functional)
Are unsupported file formats clearly communicated to the user? → Functional Testing + Usability Testing
Is a loading spinner displayed while the system evaluates available formats? → Functional Testing (UI)
Are available file formats correctly filtered based on report size? → Functional Testing (Boundary Value Analysis & Equivalence Partitioning)
Does exporting large files with unlimited formats cause performance issues? → Performance Testing (Stress Testing)
Does the enhanced PDF format (PST payroll register) work correctly outside its restricted use case? → Functional Testing + Security Testing 
Are exported files generated correctly and usable? → Functional Testing
Does the system handle high load conditions while calculating format availability within acceptable time? → Performance Testing
