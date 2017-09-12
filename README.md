# MUSHRAish-MaxMSP

A Max/MSP patcher for listening tests based on the MUSHRA interface.

This patcher is designed for conducting listening tests for which the MUSHRA interface is ideal, but the hidden reference and anchor are not (if you need these, please visit the original git which this was sourced from). The patcher allows the comparison of a number of stimuli (7 by default, although up to 10 is supported) and facilitates repeats. By default, the patcher can compare seven processes applied to three music tracks, with two repeats, making a total of six pages. However, the patcher can be easily adapted to accommodate a different number of stimuli and/or music tracks and/or repeats; the included documentation describes the procedure in detail.

This git includes the audio examples used in my MSc dissertation project testing. The "ED" examples were produced by myself (Declan Pearson), Stuart Parker, Carlos Esteves, and Andrew. They stem from the work completed on our Elephants Dream remake, which can be viewed here - https://www.youtube.com/watch?v=pzfGfjoROR8. The "Forest" examples were edited by myself using the S3A object-based audio dramas created by Woodcock et al, available here - http://cvssp.org/data/s3a/public/radiodrama_register.php. All rights belong to their respected owners. 

It should be noted that I am by no means an expert at Max, and simply tweaked the patcher that this was forked from. Maybe this will be of some use to somebody, but its place here is primarily to serve as a supplementary link to my data from my dissertation. 

## Requirements

Max/MSP 6 or higher.
