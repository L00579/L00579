<b>&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;Source Code Review Form</b>
|Dev Code Environment||
| - | - |
|Application Name||
|User Story/Jira Card#||
|Pull Request#||
|No. of Components||
|Dev Code Environment||
|Summary of the Change||
|Language/Technology||
|Reviewer Role and Name||
|Date of Review||
|Overall Review Status||
Note: Source code is to be reviewed considering each of the standard as defined in this checklist given below. In case of “No” against any standard, please make sure that it is explained in the SCR’s Issue Description column.

Developer must ensure that all the review comments are closed and verified by reviewer. In case of any non-compliance, it must be explained in the SCR’s Issue Description column and concurrence of reviewer is sought. 

|**Functionality**|**Yes/ No/ NA**|**Issue Description**|
| - | :-: | - |
|**Annotation Standards**||
|CR number documented in code?|||
|Developer’s name in the code?|||
|Revision history completed, including date of change?|||
|Is there a brief description of module function? (If not in the code module, document where this is located.)|||
|Does the code adhere to the [naming standards](https://gso.my.salesforce.com/069b0000003Z327)?(On-premise)|||
|Has a uniform naming convention been adhered to?|||
|<p>Have the following guidelines been adhered to while declaring variables?</p><p>– One variable per line (by and large).</p><p>&emsp;– Variables of the same type declared together.</p><p>&emsp;– Variables declared in alphabetical order/logical order/order of data types.</p>|||
|**Understandability**||
|Were formatting standards properly applied (spacing, indentation, etc.)?|||
|Do variables have descriptive names?|||
|**Maintainability**||
|Is the code easy to understand and follow for maintenance?|||
|**Process Specifications**||
|Are common/standard subroutines or procedures used where applicable?|||
|Are all arguments to subprograms/subroutines passed correctly (argument definitions match between calling program and subroutine)?|||
|Is modularity used wherever feasible, in order to eliminate redundant or duplicate logic?|||
|Does the code logic satisfy all of the program specifications in the design documentation?|||
|<p>Is the programming defensive in nature, including checks for?</p><p>– Input errors</p><p>&emsp;– File handling errors</p><p>&emsp;– Arithmetic errors</p><p>&emsp;– Output errors</p>|||
|**Conditions / Decision Criteria**||
|Were all conditions (logical paths) reviewed|||
|Are required initializations done properly?|||
|Are all variables defined/declared?|||
|Are all error messages/information for the user meaningful?|||
|Have all the exception cases been trapped and handled?|||
|**Sequencing**||
|Was the code put in the proper sequence? (by paragraph or label sequence number, for coding languages that permit such)|||
|Is the use of nested “if” statements correct?|||
|Are all debugging statements bypassed or removed when the program has passed unit testing? |||
|Is there an exit condition for every loop?|||
|Is every unconditional branch statement (GOTO) used properly?|||
|**Formula(s)**||
|Were all formulas/algorithms/number or code assignment logic for the change/new implementation tested?|||
|**Calculations**||
|Were all calculations for the change/new implementation tested?|||
|Has the possibility of division by zero been eliminated?|||
|Are all array references properly limited by the size of the array?|||
|**Other Critical Parameters**||
|Does the code change satisfy the requirements or change request?|||
|Has all source code been placed into the correct place/folder|||
|Has performance optimization been maximized?|||
|**Dead Code**||
|Was all dead (non-executable) code removed?|||
