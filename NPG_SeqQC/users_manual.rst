User's Manual for NPG SeqQC v58.1+
==================================

.. contents:: Table of Contents

Manual QC 
---------

Preliminary outcomes
~~~~~~~~~~~~~~~~~~~~

The current software version allows for lane outcomes to be marked as 
preliminary. Preliminary outcomes can only be changed by the same user which 
took the run for manual QC but are visible to other users of the application.

Preliminary outcomes are saved between sessions. Logging out or closing the
browser window will not delete the preliminary outcomes. Once a lane has been 
marked with a preliminary outcome, it will remain with that outcome until the
user changes to a different preliminary outcome or saves the current 
preliminary as final. 

Final outcomes
~~~~~~~~~~~~~~

Once a preliminary outcome is marked as final, it is considered as ready
to be reported. Currently there are is no way to modify a final outcome using
this web application. Once all lanes have a final outcome of manual QC, the 
run will move to the next status (archival pending).   