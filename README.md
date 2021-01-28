
# Restaurant Passport

Deployed Site: 
https://restaurant-passport-ui.netlify.com/

**Project Initialization**

1. Obtain project files 

HTTPS: 
https://github.com/Restaurant-passport-2/UI.git
SSH: 
git@github.com:Restaurant-passport-2/UI.git

2. cd into the restaurant-passport-2 directory
3. install Node, Yarn, LESS, and less-watch-compiler 

    - Official Less Documentation: 
    http://lesscss.org/
    - Instruction ond Yarn Package Manager:
    https://yarnpkg.com/en/docs/install

4. implement variables, mixins, nesting, nested at-rules in LESS
5. Run complier using yarn global add less-watch-compiler
6. Test complier by changing background to red in home-page.less
7. Run compiler watcher using less-watch-compiler less css index.less
    - Complier will not work when there are syntax errors or undefined elements
    - Watcher will flag such errors
8. Open project by folder location with a support IDE

# UI
 **The Learning Annex of Developing UI**

    - Create a mock or wireframe outline 

    - Knowing how the layout is constructed makes it easier writing html because 
      it is built upon a grid system that forms the infrastructure of the site.  

    - It is then manipulated by external sources that help refines aspects of 
      each elements declare.

    - This includes but not limited to such things as positioning, color, size,
      visibility, and movement.

    - The typical sources used to achieve manipulation of the html element is 
      CSS and JavaScript.

    - CSS helps refine the visual aesthetic while JavaScript is more common 
      used to carry out tasks that return a value or outcome.

    - CSS can be implemented as a standalone, but it usually complied by an imported 
      system such as LESS and SASS

     - In order to use these resources, they must first be initiated through an 
       installation of external resources.

    - LESS gives the coder the ability to use multiple design files that have universal
      effects on all files of html. This is done without having to embed the specific
      location in each individual html head.

    - Instead all the files are imported by one specific file that then complies them
      export the data as CSS code.

    - The ability to know how each system is executed as well as which order and priority
      each element takes is vital when creating a UI that is efficient in usability and 
      universally responsive despite media queries.

**Code Structure**

1. The Html files are just framework of the UI final production


2. The index.less file is used to import all other less files 
    -  all other less files must be written on this page to be used as an import
    
    
3.  The reset LESS file creates a standard format despite the use of different browsers


4. Global values are a the standardization of the starting format associated with the sites specific needs


5. Pages are formatted generally by 3 different files
    -navigation
    -site index
    -footer 
6. Variables are a single value used repeatedly throughout the application

7. Mixins are a collection of values that create a more dynamic output and can include a combination of different variables

8. The last file is specific effects used throughout the program.

**The LESS file will now be imported by the index.less file and then compiled automatically to the index.css file.**







