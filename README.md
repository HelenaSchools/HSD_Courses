# HSD - Courses Customization

## Version 0.0
### Version 0.0.01  
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

### Version 0.0.02
#### Bug fix on edit.hsd_custom.content.footer.txt
    Mis-spelled documnet in script so it failed. 

### Verions 0.0.03
#### Bug fix on edit.hsd_custom.content.footer.txt
    Updated names in jquery tags to be the rendered names. PowerSchool didn't parse the names as expected. Changed some of the statements due to names too complex. 

## Version 0.1
### Version 0.1.00
#### Update edit.hsd_custom.content.footer.txt
    Added fields for 

### Version 0.1.01
#### Bug fix on edit.hsd_custom.content.footer.txt
    Updated jquery statement from InnerHtml() to html(). 

### Version 0.1.02
#### Update edit.hsd_custom.content.footer.txt
    Added statment to remove content to add after move.
    Added blank select option to CTE course field.

### Version 0.1.03
#### Update edit.hsd_cusom.content.footer.txt
    Updated CTE Area of Concentration Field to use the accurate name
        Previous name CTE Courses
        New name CTE Area of Conenctration
    Added ids to all custom rows
    Added script to hide/un-hide CTE Area of Concentration based upon value in CTE Course

### Version 0.1.04
#### Update edit.hsd_cusom.content.footer.txt
    Updated script to remove/add data to use the name of element "Like" instead of "equal"
    i.e.    [name=002030102] changed to [name^=002030]

### Version 0.1.06
#### Update edit.hsd_cusom.content.footer.txt
    Change script to work on update of CTE Course field