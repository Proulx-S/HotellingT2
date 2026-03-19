# HotellingT2 in matlab
Branch of Antonio Trujilo-Ortiz HotellingT2 matlab tools v1.0.0.0
originally shared on [MathWorks File Exchange](https://www.mathworks.com/matlabcentral/fileexchange/2844-hotellingt2?s_tid=ta_fx_results) (see citations below).  
Performs various Hotelling's T-squared multivariate tests.

## Work in progress

The original code relies on interactive prompts and only prints results to terminal.  
This repo adapts the code for a programatic use (results as an output struct variable and no promt).

### Status checklist

- [x] `HotellingT2/T2Hot1.m` (one-sample test): returns a `stats` struct for programmatic use
- [ ] `HotellingT2/HotellingT2.m` (dispatcher): still interactive / prints to terminal
- [ ] `HotellingT2/MBoxtest.m` (Box's M homogeneity of covariance): still pending conversion to return values
- [ ] `HotellingT2/T2Hot2d.m` (two-sample dependent): still pending conversion to return values
- [ ] `HotellingT2/T2Hot2ihe.m` (two-sample independent, heteroscedastic): still pending conversion to return values
- [ ] `HotellingT2/T2Hot2iho.m` (two-sample independent, homoscedastic): still pending conversion to return values


## License / citation

The original authors provide citation guidance in `HotellingT2/READMEhT2.txt`, and the license terms are provided in `license.txt` (BSD-style; redistribution in source/binary form is permitted with required notices/disclaimer). The original `READMEhT2.txt` also states the zip is free to redistribute and/or modify at your option.

Citation format (from the original `READMEhT2.txt`):

Trujillo-Ortiz, A. and R. Hernandez-Walls. (2002). HotellingT2: Hotelling T-Squared testing procedures for multivariate tests. A MATLAB file. [WWW document]. URL https://www.mathworks.com/matlabcentral/fileexchange/2844-hotellingt2?s_tid=ta_fx_results

License terms are in `license.txt`; if you redistribute or modify, retain the required copyright notice, conditions, and disclaimer.

