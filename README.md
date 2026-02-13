# NASA CSDA - Planet
___________
This repository exists to provide users of the NASA Commercial Satellite Data Acquisition Program resources access to [Planet](https://www.planet.com/) satellite data.

To get more general training on using Planet's API's to access data, please visit our [notebooks repo](https://github.com/planetlabs/notebooks).

Documentation for Planet's API's can be found [here](https://docs.planet.com/)
___

### Clone or Update Repo

If you've never cloned the Planet NASA CSDA repo, run the following:

```bash
git clone https://github.com/planetlabs/nasa-csda.git
cd nasa-csda
```
___
### Dependencies

There are various python packages required to work with Planet's API's to query and download data. There is a `requirements.txt` file provided to get you started.

```bash
pip install -r requirements.txt
```
___

### Find a bug?

 Please [file an issue](https://github.com/planetlabs/nasa-csda/issues/new) and we'll get back to you as soon as possible.

___

## CSDA Data

Planet Data is available through the [CSDA Satellite Data explorer (SDX)](https://csdap.earthdata.nasa.gov/).

To request PlanetScope and RapidEye Archive data:

1. [Contact CSDA](https://csdap.earthdata.nasa.gov/signup/) and provide a name, email address, and other pertinent information (grant number, contract number, etc.) for data access approval

2. Search the [CSDA Satellite Data Explorer (SDX)](https://csdap.earthdata.nasa.gov/). An [Earthdata](https://www.earthdata.nasa.gov/data/earthdata-login) login is required for access.

3. If desired data is not found, utilize the (Data Request Form)[https://csdap.earthdata.nasa.gov/signup/vendor-data-request-form/] to initiate a request with the CSDA Data Management Team to acquire the data from Planet

4. Review discovered data and download direct from the SDX or using the Bulk Download Tool

___

### Table of Contents
This repository is split into a few sections:

- _tools_
    - Custom scripts to interact with CSDA data.
- _notebooks_
    - `.ipynb` notebooks designed to walk you through workflows or visualize planet data.
