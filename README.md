<a id="readme-top"></a>

# customdataTableLWC
Custom data table using LWC

<details>
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#about-the-project">About The Project</a>
      <ul>
        <li><a href="#built-with">Built With</a></li>
      </ul>
    </li>
    <li>
      <a href="#getting-started">Getting Started</a>
      <ul>
        <li><a href="#prerequisites">Prerequisites</a></li>
        <li><a href="#installation">Installation</a></li>
      </ul>
    </li>
    <li><a href="#usage">Usage</a></li>
    <li><a href="#roadmap">Roadmap</a></li>
    <li><a href="#contact">Contact</a></li>
  </ol>
</details>


## About The Project

This project creates a custom data table using LWC. It is compatible with Lightning experience.

<p align="right">(<a href="#readme-top">back to top</a>)</p>


### Built With

* LWC
* Apex
* JS
* CSS
* Html

<p align="right">(<a href="#readme-top">back to top</a>)</p>


## Getting Started

The code for this project is available in this repo but it can be directly installed in any Salesforce org using below link for unmanaged package: 

* Unmanaged package
  ```sh
  https://login.salesforce.com/packaging/installPackage.apexp?p0=04tIU000000vN0M
  ```


  ### Assumptions
  1. The maximum records queried is limited to 2000 due to offset limitation in apex. This can be easily overcome using `createdDate/Id` as custom offset. Here, its for demonstration purpose.
  2. Editable field is assumend to be of number type which can be extended for all types of field.
  3. Fixed set of fields is considered for this implementation. Later, it can be fetched via a fieldset/custom metadata.
  4. Record level access is not considered. It can be added by multiple ways.



  ### Installation
1. Login to your Salesforce org
2. For sandbox environments, open a new tab and paste below link:
     ```sh
    https://test.salesforce.com/packaging/installPackage.apexp?p0=04tIU000000vN0M
    ```
3.For production / developer environments, replace `test` with `login` in above url.
4. Click install & package should get installed within few minutes.


## Usage
This component can be added to any record , home or app page.
<p align="right">(<a href="#readme-top">back to top</a>)</p>


## Roadmap
1. Make the component generic for supporting most of the objects.
2. Make the data table columns dynamic and configurable.
3. Add support for experience(community) pages.

<p align="right">(<a href="#readme-top">back to top</a>)</p>


## Contact
Rohit Chavan - scorpiorohit311@gmail.com

<p align="right">(<a href="#readme-top">back to top</a>)</p>

