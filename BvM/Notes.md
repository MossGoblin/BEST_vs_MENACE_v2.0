grid values
-----------
 
 * 0 for empty
 * 1 for Beast
 * 2 for Menace

 history record structure
 ------------------------
 
 infopile:
 probability index - the value for seeding new cells in the choise pool for each board state
 history record:
 * game number
 * winner
 menace choise pool status
 * copy of "choisePool"
    * BSI : CPI
        * BSI - board state identity (space split int array)
        * CPI - choise pool identity (space split int array)

record formatting
-----------------

## board state line format
* nnnnnnnnn, where n is 0, 1 or 2

## turn format
* nnnnnnnnn, where n is either 0, M or B

## 
