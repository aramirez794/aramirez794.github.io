# Test Case 

## Test Details
    
* Test Case ID:
  * 3.3
* Test Case Name:
  * Save Game Requirement
* Component: 
  * Save in-gameplay data 
* Test Case Designer:
  * Andres Ramirez
* Creation Date:
  * 10/24/2017
* Modified By:
  * Andres Ramirez
* Modified Date:
  * 10/24/2017
* Requirements Covered:
  * 1. Only works in story mode.
  * 2. The file name for the game must be valid so it can be read back  in at a later time.
  * 3. If the file already exists, the file will be written over.
  * 4. If the file doesn’t exist it must be created.
  * 5. The  file  must  be  saved  in  a particular  format  and  include  all  the  game 
        data that needs to be read back in at a later time so the game can continue
* Test Description/Purpose:
  * Testing to see if saved game function works while in story mode.
* Pre-Test Conditions:
  * None
## Test Steps: 
| # | Description | Expected Result | Check (√) |
| --- | --- | --- | --- |
| 1 |Only works in story mode |Saving game must only work in the story mode | Games cannot be saved in build mode |			
| 2 |The file name for the game must be valid so it can be read back  in at a later time. | Whatever the user inputs as the name for the file must be valid| Strange  characters  in  the  file  name  make cause  problems  when opening the file for loading |			
| 3 |If the file already exists, the file will be written over. |If theres a file with a similar name, that file should be overwritten wth the new file |If the user is trying to save the game with the same file name then it is probably a continuation of that previously saved game. |			
| 4 |If the file doesn’t exist it must be created. |in case if theres no file, a new file should be created |The game can’t write to a file that’s not there |			
| 5 |The  file  must  be  saved  in  a particular  format  and  include  all  the  game data that needs to be read back in at a later time so the game can continue |The file that is saved must include all of the users game data that they played and it must be able to load back at a later time |If the file isn’t in a certain format then the game won’t be able to load all the information back in at a later date |			
		

## Overall Test Status:
 
Completed

## Run History:
| # |	Run Date |	Run By |	Results |
| --- | --- | --- | --- |
| 1 |10/18 |Bob |(√) |			
| 2 |10/19 |Bob |(√) |			
| 3 |10/23 |Bob |(√) |			

