# Market_Analysis_Project
### Problem Statement
The objective of this project is to assess the market trends associated with enlisted companies by providing stakeholders with a comprehensive understanding of how the market evaluates a company, including insights into its business performance, profitability, and growth prospects. Key financial metrics considered in this analysis encompass Market Capitalization, Revenue, Earnings, P/E Ratio, and the number of employees within the companies. The data utilized for this evaluation has been sourced from the Global Ranking [Website](https://companiesmarketcap.com) Approximately 5000 data have been extracted from the aforementioned source.

Later tha data has been pre-processed,manipulated and molded (removing $/ B /M signs) as per project's needs. The pertinent data then populated in Tableau to create visulaization. For that files from [final_data](https://github.com/TabassumTanzim/Market_Analysis_Project/tree/main/final_data) are joined on 'company name'. Three dashboards have been made which depicts the followings:
1. Demonstrating world wide P/E ratios of the pharmaceutical catagory - map
2. Maximum revenue generated country wise - symbol map
3. Revenue Vs earning of automakers and e-commerce category - scatter plot
4. Market cap Vs P/E ratio of automakers and e-commerce category- scatter plot
5. Manipultion ratio of China and Japan and their earnings
6. #Employees impact on revenue - scatter plot
7. Canada Vs Israel Market Cap - bar plot

## You can visit the dashboard [here](https://public.tableau.com/views/Market_Analysis_2/MarketCapitalVSPERatio?:language=en-GB&publish=yes&:display_count=n&:origin=viz_share_link)

### Intersting findings from the dashboards: 
1. Indian companies have the highest P/E ratio on Pharmaceutical catagory.<img width="1008" alt="image" src="https://github.com/TabassumTanzim/Market_Analysis_Project/assets/75922668/d23e7bdf-99d0-412d-b511-fb67b7d1ea9d">

2. Amazon produces maximum revenue based on all catagories.<img width="1318" alt="image" src="https://github.com/TabassumTanzim/Market_Analysis_Project/assets/75922668/3579fb71-4097-4e13-8d0c-0fc4b447b162">

3. Revenue to Earning proportion of 'Amazon' doesn't justify even after generating the highest revenue.<img width="820" alt="image" src="https://github.com/TabassumTanzim/Market_Analysis_Project/assets/75922668/d6982fd8-7569-410e-a8a5-7d65c92692a0">

4. Even though Amazon has the highest market capitalization, Tata Motor has more P/E ratio than Amazon having so much less market cap.<img width="1142" alt="image" src="https://github.com/TabassumTanzim/Market_Analysis_Project/assets/75922668/5bcbeee8-d58a-4f7d-8024-ebb970ae557c">

5. Japanese automaking companies have huge manipulation ratio. This parameter is indicating employees exploitaion metric since we are dividing the earnings by #emplyees. More the manipulation ratio, more the workload on employees; more they are exploitated to produce more earnings of the company.<img width="1301" alt="image" src="https://github.com/TabassumTanzim/Market_Analysis_Project/assets/75922668/ef6bf19b-dd31-49b8-a1cd-c6feb9654693">

6. More employees doesn't mean more revenue. Mc Donalds with half the highest empolyees of rank, is producing second largest revenue.<img width="957" alt="image" src="https://github.com/TabassumTanzim/Market_Analysis_Project/assets/75922668/b4297918-00ac-4c73-a57c-1715593afcd5">

7. Canada is ruling compare to Israel based on market cap.<img width="1107" alt="image" src="https://github.com/TabassumTanzim/Market_Analysis_Project/assets/75922668/34463064-85b9-4271-9b3b-16df74facc44">










### Build From Source:
1. Clone the repo
```bash
git clone https://github.com/TabassumTanzim/Market_Analysis_Project.git
```
2. Initialize and activate virtual environment
```bash
virtualenv --no-site-packages venv
source venv/bin/activate
```
3. Install dependecies
```bash
pip install -r requirements.txt
```
4. Download chromedriver from [here](https://chromedriver.chromium.org)
5. Run selenium_scraper to scrap data
6. You will get the scraped data from [here](https://github.com/TabassumTanzim/Market_Analysis_Project/tree/main/selenium_scraper/Scraped_Data)
7. For data manipulation and concatenation of csv files refer to this [folder](https://github.com/TabassumTanzim/Market_Analysis_Project/tree/main/data_manipulation)
8. Finally you will get the resultant data in this [directory](https://github.com/TabassumTanzim/Market_Analysis_Project/tree/main/final_data)
   
