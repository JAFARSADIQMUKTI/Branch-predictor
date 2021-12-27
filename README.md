# Branch-predictor
Comparing different dynamic branch prediction methods for a pipelined processor.

Currently only shows branch direction predictions (taken or not taken), not branch target address predictions or branch instruction predictions (determining whether instruction is branch), since these can generally be done efficiently for direct branches with a branch target buffer (BTB) and return address stack (RAS) for function returns.

Note that this tool is simply to be used for visualizing and better understanding branch prediction accuracy of different branch prediction methods under different branch patterns, not for rigorous testing for comparison between the methods.
# References
cynthia wang-Branch-prediction-visualization
