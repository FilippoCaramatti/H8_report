# H8 Report Analyzer
Here there are a few function that i have created to analyze the F8 report by the FED after the failure of SVB, SB and FRB. 

## Functions
- single_bank_type(file_name, bank_type, sa, last_x_days)
- def banks_bs_comp_change(reports, bank_type, sa, comp_criterias, last_x_days)
- def banks_bs_comp_change_div(reports, bank_type, sa, comp_criterias, last_x_days, divider)
- def banks_bs_comp_percent(reports, bank_type, sa, comp_criterias, last_x_days)
- def banks_bs_comp_percent(reports, bank_type, sa, comp_criterias, last_x_days)
- def banks_bs_comp_percent_div(reports, bank_type, sa, comp_criterias, last_x_days, divider)
### Inputs
- file_name name of the single file
- reports serie of reports to be used together
- bank_type what bank is going to be analyzed
- comp_criterias specify which criteria is going to be compared between different reports
- divider values by wich the comp_criterias are going to be divideed by
