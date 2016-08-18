# PrognosticsModelLibrary

The Prognostics Model Library is a modeling framework focused on defining and building models for prognostics (computation of remaining useful life) of engineering systems, and provides a set of prognostics models for select components developed within this framework, suitable for use in prognostics applications for these components. The library currently includes models for valves, pumps, and batteries. The Prognostics Model Library is implemented in MATLAB. The implementation consists of a set of utilities for defining a model (specifying variables, parameters, and equations), simulating the model, and embedding it within common model-based prognostics algorithms. A user can use existing models within the library or construct new models with the provided framework.

## Installation

Installation can be done in one of two ways. Either (1) use the provided MATLAB toolbox installer provided in the install folder, which will install the toolbox in your local toolboxes folder and add the folder to your MATLAB path, or (2) copy the source from the MATLAB folder to any desired directory, and add that directory to your MATLAB path. Do not add the subdirectories (the package directories) to your MATLAB path. If the first option is used, then the MATLAB add-on manager can be used to uninstall the package; otherwise, the installation can be removed manually be removing the directory from your MATLAB path and deleting the source.

## User Manual

See https://github.com/nasa/PrognosticsModelLibrary/blob/master/docs/PrognosticsModelLibrary-UserManual.pdf.

## Compatibility

The PrognosticsModelLibrary has been tested with Matlab R2016a, but should work with older versions, down to at least R2012a.

## Contributions

All contributions are welcome. Issues may be opened using GitHub. To contribute directly, open a pull request against the "develop" branch. Pull requests will be evaluated and integrated into the next official release.

## Notices

Copyright © 2016 United States Government as represented by the Administrator of the National Aeronautics and Space Administration.  No copyright is claimed in the United States under Title 17, U.S. Code. All Other Rights Reserved.

### Disclaimers  

No Warranty: THE SUBJECT SOFTWARE IS PROVIDED "AS IS" WITHOUT ANY WARRANTY OF ANY KIND, EITHER EXPRESSED, IMPLIED, OR STATUTORY, INCLUDING, BUT NOT LIMITED TO, ANY WARRANTY THAT THE SUBJECT SOFTWARE WILL CONFORM TO SPECIFICATIONS, ANY IMPLIED WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE, OR FREEDOM FROM INFRINGEMENT, ANY WARRANTY THAT THE SUBJECT SOFTWARE WILL BE ERROR FREE, OR ANY WARRANTY THAT DOCUMENTATION, IF PROVIDED, WILL CONFORM TO THE SUBJECT SOFTWARE. THIS AGREEMENT DOES NOT, IN ANY MANNER, CONSTITUTE AN ENDORSEMENT BY GOVERNMENT AGENCY OR ANY PRIOR RECIPIENT OF ANY RESULTS, RESULTING DESIGNS, HARDWARE, SOFTWARE PRODUCTS OR ANY OTHER APPLICATIONS RESULTING FROM USE OF THE SUBJECT SOFTWARE.  FURTHER, GOVERNMENT AGENCY DISCLAIMS ALL WARRANTIES AND LIABILITIES REGARDING THIRD-PARTY SOFTWARE, IF PRESENT IN THE ORIGINAL SOFTWARE, AND DISTRIBUTES IT "AS IS."

Waiver and Indemnity:  RECIPIENT AGREES TO WAIVE ANY AND ALL CLAIMS AGAINST THE UNITED STATES GOVERNMENT, ITS CONTRACTORS AND SUBCONTRACTORS, AS WELL AS ANY PRIOR RECIPIENT.  IF RECIPIENT'S USE OF THE SUBJECT SOFTWARE RESULTS IN ANY LIABILITIES, DEMANDS, DAMAGES, EXPENSES OR LOSSES ARISING FROM SUCH USE, INCLUDING ANY DAMAGES FROM PRODUCTS BASED ON, OR RESULTING FROM, RECIPIENT'S USE OF THE SUBJECT SOFTWARE, RECIPIENT SHALL INDEMNIFY AND HOLD HARMLESS THE UNITED STATES GOVERNMENT, ITS CONTRACTORS AND SUBCONTRACTORS, AS WELL AS ANY PRIOR RECIPIENT, TO THE EXTENT PERMITTED BY LAW.  RECIPIENT'S SOLE REMEDY FOR ANY SUCH MATTER SHALL BE THE IMMEDIATE, UNILATERAL TERMINATION OF THIS AGREEMENT.
