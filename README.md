# HSD - Courses Customization

## Version 0.0 - Future Release
### Version 0.0.01 - Future Release  
#### Added edit.hsd_custom.content.footer.txt
    Added basic custom file. Contains the javascript to remove the following fields:
<table>
    <thead>
        <tr>
            <th>Field</th>
            <th>Reason removed</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td>
                Course Description
            </td>
            <td>
                Removed prior to documentation; unused
            </td>
        </tr>
        <tr>
            <td>
                Alternate Course Number
            </td>
            <td>
                Removed prior to documentation; unused
            </td>
        </tr>
        <tr>
            <td>
                CIP Code
            </td>
            <td>
                Unused
            </td>
        </tr>
        <tr>
            <td>
                Maximum Credit Hours
            </td>
            <td>
                Unused
            </td>
        </tr>
        <tr>
            <td>
                Special Program
            </td>
            <td>
                Unused
            </td>
        </tr>
        <tr>
            <td>
                Course Notes
            </td>
            <td>
                Unused
            </td>
        </tr>
        <tr>
            <td>
                Department
            </td>
            <td>
                Unused
            </td>
        </tr>
    </tbody>
</table>

### Version 0.0.02 - Future Release
#### Bug fix on edit.hsd_custom.content.footer.txt
    Mis-spelled documnet in script so it failed. 

### Verions 0.0.03 - Future Release
#### Bug fix on edit.hsd_custom.content.footer.txt
    Updated names in jquery tags to be the rendered names. PowerSchool didn't parse the names as expected. Changed some of the statements due to names too complex. 

## Version 0.1 - Future Release
### Version 0.1.00 - Future Release
#### Update edit.hsd_custom.content.footer.txt
    Added fields for 

### Version 0.1.01 - Future Release
#### Bug fix on edit.hsd_custom.content.footer.txt
    Updated jquery statement from InnerHtml() to html(). 

### Version 0.1.02 - Future Release
#### Update edit.hsd_custom.content.footer.txt
    Added statment to remove content to add after move.
    Added blank select option to CTE course field.

### Version 0.1.03 - Future Release
#### Update edit.hsd_custom.content.footer.txt
    Updated CTE Area of Concentration Field to use the accurate name
        Previous name CTE Courses
        New name CTE Area of Conenctration
    Added ids to all custom rows
    Added script to hide/un-hide CTE Area of Concentration based upon value in CTE Course

### Version 0.1.04 - Future Release
#### Update edit.hsd_custom.content.footer.txt
    Updated script to remove/add data to use the name of element "Like" instead of "equal"
    i.e.    [name=002030102] changed to [name^=002030]

### Version 0.1.05 - Future Release
### Version 0.1.06 - Future Release
### Version 0.1.07 - Future Release
#### Update edit.hsd_custom.content.footer.txt
    Change script to work on update of CTE Course field

### Version 0.1.08 - Future Release
#### Update edit.hsd_custom.footer.txt
    Add field clear to CTE Area of Concentration if the CTE Course Indicator field is set to blank (no)

## Version 0.2
### Version 0.2.00 - Future Release
#### Adding the NCES and course list functionality
    Started new version to add the NCES codes and functionality for the codes. 

### Version 0.2.01 - Future Release
#### Adding district settings to admin/district/
    Added page home.AddDeleteStateCourses.content.footer.txt

### Version 0.2.02 - Future Release
#### Update home.AddDeleteStateCourses.content.footer.txt
    Changed where the state courses delete page link exists, added to courses group inside the district home page
#### Update deleteStateCourses.html
    Chanaged the custom page to have the proper breadcrumbs back to District Setup. 

### Version 0.2.03 - Future Release
#### Update deleteStateCourses.html
    Changed breadcrum string due to typo

### Version 1.0.01
#### Put Department back on the Courses page
    Returned Departments so it can be associated. 