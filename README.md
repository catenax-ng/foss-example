# How to make your CatenaX product OSS ready

In this repository you find templates and examples that have to be added to a (new) CatenaX open source project, licensed under
the Apache 2.0 License.

The products / projects live in the [Catenax(ng) Github Organization](https://github.com/catenax-ng) 
and have to be "migrated" to the [Eclipse eclipse-tractusx Github Organization](https://github.com/eclipse-tractusx) in a second step.

This repository has the following directory structure:
* directory *general*: templates and examples for **both** catenax-ng and eclipse-tractusx repositories
* directory *catenax-ng-repositories*: templates and examples for **catenax-ng** repositories
* directory *eclipse-tractusx-repositories*: templates and examples for **eclipse-tractusx** repositories

Add the files at top level in your repositories, unless otherwise noted.
Files with the suffix *_template* have to be modified and renamed by deleting he suffix.

## Files from directory *general*

Templates and examples for **both** catenax-ng and eclipse-tractusx repositories

#### LICENSE file
The Apache-2.0 license file. Add this file to your repositories.

#### DEPENDENCIES
Contains a list of all 3rd party libraries used with your code.
Create the content for this file and rename it to 'DEPENDENCIES'.

[Example](https://github.com/eclipse-tractusx/sldt-semantic-hub/blob/main/DEPENDENCIES), created with [Eclipse Dash Tool](https://github.com/eclipse/dash-licenses#readme)

#### AUTHORS.md (optional)
If you want to mention the authors, create the content for this file and rename it to 'AUTHORS'.

[Example](https://github.com/eclipse-tractusx/sldt-semantic-hub/blob/main/AUTHORS.md)

## Files from directory *catenax-ng-repositories*
These files are for **catenax-ng** repositories only.

#### NOTICE.md
Add your repositories in the section *Source Code*.

#### SECURITY.md
Copy this file into your repository.

## Files from directory *eclipse-tractusx-repositories*
These files are for **eclipse-tractusx** repositories only.

#### NOTICE.md
Add your repositories in the section *Source Code*.

**Note:** The content is different from the one for the CatenaX repositories! 

#### SECURITY.md
Copy this file in your repository.

**Note:** The content is different from the one for the CatenaX repositories! 

#### CONTRIBUTING.md
Copy this file in your repository.

#### CODE_OF_CONDUCT.md
Copy this file in your repository.

## Copyright and License Header

Where possible, all source code, property files, and metadata files (including application, test, and generated source code as well as other types of files such as XML, HTML, etc.) must include a header with appropriate copyright and license notices.

If your Git history is maintained and complete, choose the CopyrightAndLicenseHeader_1.txt variant and add the text to all mentioned files in your repositories.

If your Git history is incomplete, e.g. because of squash commits, you have to choose variant 2 (CopyrightAndLicenseHeader_2.txt) and modify the line:

`Copyright (c) 2021,2022 {owner}[ and others]` 

for each file in an appropriate way, e.g.

`Copyright (c) 2021,2022 MyCompany GmbH and others`

**Note:** Choose the CopyrightAndLicenseHeader_* templates from the appropriate directory!

## Links
* [Legal Document Generator from the Eclipse Foundation](https://www.eclipse.org/projects/tools/documentation.php?id=automotive.tractusx)
* [Eclipse TractusX GitHub Organization](https://github.com/eclipse-tractusx)
