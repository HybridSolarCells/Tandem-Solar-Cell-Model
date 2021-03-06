# Tandem-Solar-Cell-Model

This program models a silicon solar cell with an efficiency of 26.7% and a perovskite solar cell with an efficiency of 19.7%. These two subcells are then used to simulate the efficiency of a perovskite/Si tandem solar cell under standard test conditions. By using measured solar spectra and temperatures data this model can be extended to simulate the performance of realistic perovskite/silicon tandem solar cells under real world climate conditions. 

Measured solar spectra and temperatures can be downloaded for example from [NREL](https://midcdmz.nrel.gov/apps/go2url.pl?site=BMS&page=spectra.pl?BMS) and will soon be available from the [AMOLF Solar Field](http://www.lmpv.nl/solar-field/).

When citing this work, please refer to:
M. H. Futscher, B. Ehrler, [Modeling the Performance Limitations and Prospects of Perovskite/Si Tandem Solar Cells under Realistic Operating Conditions](http://pubs.acs.org/doi/abs/10.1021/acsenergylett.7b00596), ACS Energy Lett. 2017, 2, 2089–2095, DOI: 10.1021/acsenergylett.7b00596

This program is free software: you can redistribute it and/or modify it under the terms of the GNU General Public License as published by the Free Software Foundation, either version 3 of the License, or (at your option) any later version.

This program is distributed in the hope that it will be useful, but WITHOUT ANY WARRANTY; without even the implied warranty of MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE. See the GNU General Public License for more details.

You should have received a copy of the GNU General Public License along with this program. If not, see <http://www.gnu.org/licenses/>.

## Requirements

[Wolfram Mathematica](https://www.wolfram.com/mathematica/)

## Installation

Download RealisticTandem.nb, Input.zip, and the [ASTM G173-03 Reference Spectra (ASTMG173.xls)](http://rredc.nrel.gov/solar/spectra/am1.5/astmg173/astmg173.html) and include these files in the directory where you are performing the analysis. Unpack the file Input.zip and add the reference spectra into the folder Input. Open the file RealisticTandem.nb with Wolfram Mathematica and evaluate the notebook.
