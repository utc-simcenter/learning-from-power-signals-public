# learning-from-power-signals
OSG to Cyclic Histogram project

Developed by Joshua H. Tyler, Dr. Donald R. Reising, and Johnathan Boyd at the University of Tennessee at Chattanooga

In partnership with:

Tony Murphy and Nathan Hooker, Tennessee Valley Authority

Thomas Cooke, Electrical Power Research Institute

Christopher Lackner and Erika Wills, Grid Protection Alliance

#================================================================================================================

This project was developed to convert continuous, OScilloGraphy (OSG) data into small, actionable histograms saved as CSV files. The histogram types include: (i) cyclic, (ii) residual, (iii) frequency, and (iv) RMS. All code is written in phython and compiled into an executible using pythoninstaller. The .exe file will be found under "dist/[project type]/[project type].exe. To accellerate computation, each function is compiled and cached using the Numba library. Example data is included with the ideal visual output for reference.

#================================================================================================================
#DISCLAIMER: THIS IS A BETA RELEASE AND NOT INTENDED FOR DEPLOYMENT. DEPLOYMENT OF THIS VERSION IS STRONGLY DISCOURAGED AND THE AUTHORS CLAIM NO RESPONSIBILITY FOR ISSUES CAUSED BY USING THIS SOFTWARE.

#Copyright 2021 University of Tennessee/University of Tennessee Research Foundation

#Redistribution and use in source and binary forms, with or without modification, are permitted provided that the following conditions are met:
#1. Redistributions of source code must retain the above copyright notice, this list of conditions and the following disclaimer.
#2. Redistributions in binary form must reproduce the above copyright notice, this list of conditions and the following disclaimer in the documentation and/or other materials provided with the distribution.
#3. Neither the name of the copyright holder nor the names of its contributors may be used to endorse or promote products derived from this software without specific prior written permission.

#THIS SOFTWARE IS PROVIDED BY THE COPYRIGHT HOLDERS AND CONTRIBUTORS "AS IS" AND ANY EXPRESS OR IMPLIED WARRANTIES, INCLUDING, BUT NOT LIMITED TO, THE IMPLIED WARRANTIES OF MERCHANTABILITY AND FITNESS FOR A 
#PARTICULAR PURPOSE ARE DISCLAIMED. IN NO EVENT SHALL THE COPYRIGHT HOLDER OR CONTRIBUTORS BE LIABLE FOR ANY DIRECT, INDIRECT, INCIDENTAL, SPECIAL, EXEMPLARY, OR CONSEQUENTIAL DAMAGES (INCLUDING, BUT NOT 
#LIMITED TO, PROCUREMENT OF SUBSTITUTE GOODS OR SERVICES; LOSS OF USE, DATA, OR PROFITS; OR BUSINESS INTERRUPTION) HOWEVER CAUSED AND ON ANY THEORY OF LIABILITY, WHETHER IN CONTRACT, STRICT LIABILITY, OR 
#TORT (INCLUDING NEGLIGENCE OR OTHERWISE) ARISING IN ANY WAY OUT OF THE USE OF THIS SOFTWARE, EVEN IF ADVISED OF THE POSSIBILITY OF SUCH DAMAGE.

#================================================================================================================

#CONTRIBUTORS:

#Joshua H. Tylerm M.S.; joshua-tyler@mocs.utc.edu;

#Donald R. Reising, Ph.D.; donald-reising@utc.edu; 423-425-5843

#================================================================================================================
