# Python-web-scraping-project-

![image](https://github.com/subhathra23/Python-web-scraping-project-/assets/137802431/53d1ef20-e6b5-4457-a744-998c971178d0)


List of largest companies in the United States by revenue


This list comprises the largest companies in the United States by revenue as of 2022, according to the Fortune 500 tally of companies.

This list includes only publicly traded companies, also including tax inversion companies. There are also corporations having foundation in the United States, such as corporate headquarters, operational headquarters and independent subsidiaries. The list excludes large privately held companies such as Cargill and Koch Industries whose financial data is not necessarily available to the public. However, this list does include several government-sponsored enterprises that were created by acts of Congress and later became publicly traded.


Web scraping is the process of extracting data from websites automatically using a program or script. It involves fetching the HTML content of a web page and then parsing it to extract the desired information. Wikipedia is a popular website that provides a wealth of information on various topics, and web scraping can be used to extract data from Wikipedia pages.

Here is a general overview of how web scraping works for Wikipedia:

Understanding the website's structure: Before scraping data from Wikipedia, it's important to understand the structure of the website and the specific page(s) you want to scrape. Each Wikipedia page typically has a consistent layout, which makes it easier to locate the desired information.

Choosing a scraping tool or library: There are various tools and libraries available for web scraping in different programming languages. Some popular options include Python libraries such as BeautifulSoup, Scrapy, and requests-html. These libraries provide functions and methods to fetch web pages, parse HTML content, and extract data efficiently.

Fetching the web page: Using the chosen scraping library, you can send an HTTP request to the URL of the Wikipedia page you want to scrape. The library will fetch the HTML content of the page.

Parsing the HTML content: Once you have the HTML content of the page, you can use the scraping library to parse it and extract the desired data. This involves locating specific HTML elements (such as tags, classes, or IDs) that contain the information you're interested in.

Extracting the data: Once you have identified the relevant HTML elements, you can extract the data from them using the scraping library's functions. For example, if you want to extract the text of a specific heading or table, you can use the library's methods to retrieve that data.

Cleaning and processing the data: After extracting the data, you may need to clean and process it further to remove any unnecessary characters, format it properly, or convert it to a desired format (such as CSV or python, visualization, tableau, excel ).


for row in column_data:
    
    row_data = row.find_all('td')
    
    individual_row_data = [data.text.strip() for data in row_data]
    
    print(individual_row_data)


   []
['1', 'Walmart', 'General merchandisers', '572,754', '2.4%', '2,300,000', 'Bentonville, Arkansas']
['2', 'Amazon', 'Retail and Cloud Computing', '469,822', '21.7%', '1,608,000', 'Seattle, Washington']
['3', 'Apple', 'Electronics industry', '365,817', '33.2%', '154,000', 'Cupertino, California']
['4', 'CVS Health', 'Healthcare', '292,111', '32.0%', '258,000', 'Woonsocket, Rhode Island']
['5', 'UnitedHealth Group', 'Healthcare', '287,597', '11.8%', '350,000', 'Minnetonka, Minnesota']
['6', 'Exxon Mobil', 'Petroleum industry', '285,640', '57.4%', '63,000', 'Spring, Texas']
['7', 'Berkshire Hathaway', 'Conglomerate', '276,094', '12.5%', '372,000', 'Omaha, Nebraska']
['8', 'Alphabet', 'Technology', '257,637', '41.2%', '156,000', 'Mountain View, California']
['9', 'McKesson Corporation', 'Health', '238,228', '3.1%', '67,500', 'Irving, Texas']
['10', 'AmerisourceBergen', 'Pharmaceutical industry', '213,989', '12.7%', '40,000', 'Chesterbrook, Pennsylvania']
['11', 'Microsoft', 'Technology', '198,087', '17.5%', '181,000', 'Redmond, Washington']
['12', 'Costco', 'Retail', '195,929', '17.5%', '288,000', 'Issaquah, Washington']
['13', 'Cigna', 'Health Insurance', '174,078', '8.5%', '72,963', 'Bloomfield, Connecticut']
['14', 'AT&T', 'Conglomerate', '168,864', '1.7%', '202,600', 'Dallas, Texas']
['15', 'Cardinal Health', 'Healthcare', '162,467', '6.2%', '46,827', 'Dublin, Ohio']
['16', 'Chevron Corporation', 'Petroleum industry', '162,465', '71.6%', '42,595', 'San Ramon, California']
['17', 'The Home Depot', 'Retail', '151,157', '14.4%', '490,600', 'Atlanta, Georgia']
['18', 'Walgreens Boots Alliance', 'Pharmaceutical industry', '148,579', '6.5%', '258,500', 'Deerfield, Illinois']
['19', 'Marathon Petroleum', 'Petroleum industry', '141,032', '58.5%', '17,700', 'Findlay, Ohio']
['20', 'Elevance Health', 'Healthcare', '138,639', '13.8%', '98,200', 'Indianapolis, Indiana']
['21', 'Kroger', 'Retail', '137,888', '4.1%', '420,000', 'Cincinnati, Ohio']
['22', 'Ford Motor Company', 'Automotive industry', '136,341', '7.2%', '183,000', 'Dearborn, Michigan']
['23', 'Verizon Communications', 'Telecommunications', '133,613', '4.1%', '118,400', 'New York City, New York']
['24', 'JPMorgan Chase', 'Financial services', '127,202', '1.8%', '271,025', 'New York City, New York']
['25', 'General Motors', 'Automotive', '127,004', '3.7%', '157,000', 'Detroit, Michigan']
['26', 'Centene', 'Healthcare', '125,982', '13.4%', '72,500', 'St. Louis, Missouri']
['27', 'Meta Platforms', 'Technology', '117,385', '37.2%', '71,970', 'Menlo Park, California']
['28', 'Comcast', 'Telecommunications', '116,385', '12.4%', '189,000', 'Philadelphia, Pennsylvania']
['29', 'Phillips 66', 'Petroleum industry', '114,852', '75.4%', '14,000', 'Houston, Texas']
['30', 'Valero Energy', 'Petroleum industry', '108,332', '80.2%', '9,804', 'San Antonio, Texas']
['31', 'Dell Technologies', 'Technology', '106,995', '13.6%', '133,000', 'Round Rock, Texas']
['32', 'Target Corporation', 'Retail', '106,005', '13.3%', '450,000', 'Minneapolis, Minnesota']
['33', 'Fannie Mae', 'Financials', '101,543', '4.6%', '7,400', 'Washington, D.C.']
['34', 'United Parcel Service', 'Transportation', '97,287', '15.0%', '400,945', 'Atlanta, Georgia']
['35', "Lowe's", 'Retail', '96,250', '7.4%', '270,000', 'Mooresville, North Carolina']
['36', 'Bank of America', 'Financials', '93,851', '0.1%', '208,248', 'Charlotte, North Carolina']
['37', 'Johnson & Johnson', 'Pharmaceutical industry', '93,775', '13.6%', '141,700', 'New Brunswick, New Jersey']
['38', 'Archer Daniels Midland', 'Food industry', '85,959', '32.5%', '39,979', 'Chicago, Illinois']
['39', 'FedEx', 'Transportation', '83,959', '21.3%', '484,000', 'Memphis, Tennessee']
['40', 'Humana', 'Health Insurance', '83,064', '7.7%', '95,500', 'Louisville, Kentucky']
['41', 'Wells Fargo', 'Financials', '82,407', '2.6%', '247,848', 'San Francisco, California']
['42', 'State Farm', 'Financials', '82,407', '4.2%', '53,586', 'Bloomington, Illinois']
['43', 'Pfizer', 'Pharmaceutical industry', '81,288', '94.0%', '79,000', 'New York City, New York']
['44', 'Citigroup', 'Financials', '79,865', '10.1%', '221,768', 'New York City, New York']
['45', 'PepsiCo', 'Beverage', '79,474', '12.9%', '309,000', 'Purchase, New York']
['46', 'Intel', 'Technology', '79,024', '1.5%', '121,100', 'Santa Clara, California']
['47', 'Procter & Gamble', 'Consumer products Manufacturing', '76,118', '7.3%', '101,000', 'Cincinnati, Ohio']
['48', 'General Electric', 'Conglomerate', '74,196', '6.8%', '168,000', 'Boston, Massachusetts']
['49', 'IBM', 'Technology', '72,344', '1.7%', '297,800', 'Armonk, New York']
['50', 'MetLife', 'Financials', '71,080', '4.8%', '43,000', 'New York City, New York']
['51', 'Prudential Financial', 'Financials', '70,934', '24.4%', '40,916', 'Newark, New Jersey']
['52', 'Albertsons', 'Retail', '69,690', '11.6%', '300,000', 'Boise, Idaho']
['53', 'The Walt Disney Company', 'Media', '67,418', '3.1%', '171,000', 'Burbank, California']
['54', 'Energy Transfer Partners', 'Petroleum industry', '67,418', '73.1%', '12,558', 'Dallas, Texas']
['55', 'Lockheed Martin', 'Aerospace and Defense', '67,044', '2.5%', '114,000', 'Bethesda, Maryland']
['56', 'Freddie Mac', 'Financials', '65,898', '0.5%', '7,301', 'McLean, Virginia']
['57', 'Goldman Sachs', 'Financials', '64,989', '2.7%', '43,900', 'New York City, New York']
['58', 'Raytheon Technologies', 'Conglomerate', '64,388', '13.8%', '174,000', 'Waltham, Massachusetts']
['59', 'HP', 'Technology', '63,487', '12.1%', '51,000', 'Palo Alto, California']
['60', 'Boeing', 'Aerospace and defense', '62,286', '7.1%', '142,000', 'Chicago, Illinois']
['61', 'Morgan Stanley', 'Financials', '61,121', '17.4%', '74,814', 'New York City, New York']
['62', 'HCA Healthcare', 'Healthcare', '58,752', '14.0%', '244,000', 'Nashville, Tennessee']
['63', 'AbbVie', 'Pharmaceutical industry', '56,197', '22.7%', '50,000', 'Lake Bluff, Illinois']
['64', 'Dow Chemical Company', 'Chemical industry', '54,968', '42.6%', '35,700', 'Midland, Michigan']
['65', 'Tesla', 'Automotive and Energy', '53,823', '70.7%', '99,290', 'Austin, Texas']
['66', 'Allstate', 'Insurance', '53,228', '18.8%', '54,500', 'Northfield Township, Cook County, Illinois']
['67', 'AIG', 'Insurance', '52,057', '19.0%', '36,600', 'New York City, New York']
['68', 'Best Buy', 'Retail', '51,761', '9.5%', '81,375', 'Richfield, Minnesota']
['69', 'Charter Communications', 'Telecommunications', '51,682', '7.5%', '93,700', 'Stamford, Connecticut']
['70', 'Sysco', 'Food Service', '51,298', '3.0%', '57,710', 'Houston, Texas']
['71', 'Merck & Co.', 'Pharmaceutical industry', '51,216', '6.7%', '67,500', 'Kenilworth, New Jersey']
['72', 'New York Life Insurance Company', 'Insurance', '51,199', '9.6%', '13,344', 'New York City, New York']
['73', 'Novartis', 'Pharmaceuticals', '51,332', '6.0%', '110,000', 'Cambridge, Massachusetts']
['74', 'Caterpillar', 'Machinery', '50,971', '22.1%', '107,700', 'Deerfield, Illinois']
['75', 'Cisco', 'Telecom Hardware Manufacturing', '49,818', '1.0%', '79,500', 'San Jose, California']
['76', 'TJX', 'Retail', '48,550', '51.1%', '340,000', 'Framingham, Massachusetts']
['77', 'Publix', 'Retail', '48,394', '7.1%', '232,000', 'Lakeland, Florida']
['78', 'ConocoPhillips', 'Petroleum industry', '48,349', '151.1%', '9,900', 'Houston, Texas']
['79', 'Liberty Mutual Group', 'Insurance', '48,200', '10.1%', '45,000', 'Boston, Massachusetts']
['80', 'Progressive Corporation', 'Insurance', '47,702', '11.8%', '49,077', 'Mayfield Village, Ohio']
['81', 'Nationwide Mutual Insurance Company', 'Financial', '47,376', '13.0%', '24,134', 'Columbus, Ohio']
['82', 'Tyson Foods', 'Food Processing', '47,049', '8.9%', '137,000', 'Springdale, Arkansas']
['83', 'Bristol-Myers Squibb', 'Pharmaceutical industry', '46,385', '9.1%', '32,200', 'New York City, New York']
['84', 'GSK plc', 'Pharmaceuticals', '44,700', '3.0%', '97,000', 'Philadelphia, Pennsylvania']
['85', 'Nike', 'Apparel', '44,538', '19.1%', '73,300', 'Beaverton, Oregon']
['86', 'John Deere', 'Agriculture manufacturing', '44,024', '23.9%', '75,550', 'Moline, Illinois']
['87', 'American Express', 'Financial', '43,663', '14.3%', '64,000', 'New York City, New York']
['88', 'Abbott Laboratories', 'Medical devices', '43,075', '24.5%', '113,000', 'Chicago, Illinois']
['89', 'StoneX Group', 'Financials', '42,534', '21.4%', '3,242', 'New York City, New York']
['90', 'Plains All American Pipeline', 'Petroleum industry', '42,078', '80.7%', '4,100', 'Houston, Texas']
['91', 'Enterprise Products', 'Petroleum industry', '40,807', '50.0%', '6,911', 'Houston, Texas']
['92', 'TIAA', 'Insurance', '40,526', '2.6%', '15,065', 'New York City, New York']
['93', 'Oracle Corporation', 'Software', '40,479', '3.6%', '132,000', 'Austin, Texas']
['94', 'Thermo Fisher Scientific', 'Laboratory instruments', '39,211', '21.7%', '129,000', 'Waltham, Massachusetts']
['95', 'Coca-Cola Company', 'Beverages', '38,655', '17.1%', '79,000', 'Atlanta, Georgia']
['96', 'General Dynamics', 'Airspace and defense', '38,469', '8.7%', '103,100', 'Reston, Virginia']
['97', 'CHS', 'Agriculture cooperative', '38,448', '1.4%', '9,941', 'Inver Grove Heights, Minnesota']
['98', 'USAA', 'Financials', '37,470', '3.2%', '37,335', 'San Antonio, Texas']
['99', 'Northwestern Mutual', 'Insurance', '36,751', '8.8%', '7,585', 'Milwaukee, Wisconsin']
['100', 'Nucor', 'Metals', '36,484', '81.2%', '28,800', 'Charlotte, North Carolina']
 for row in column_data[1:]: 




The images of company



![image](https://github.com/subhathra23/Python-web-scraping-project-/assets/137802431/6b4ff01e-d470-4aa8-aa47-2c79086d3c76)




for row in column_data[1:]:
    
    row_data = row.find_all('td')
    
    individual_row_data = [data.text.strip() for data in row_data]
    
    length = len(df)
    df.loc[length] = individual_row_data


    df




	
 Rank	Name	Industry	Revenue (USD millions)	Revenue growth	Employees	Headquarters

0	1	Walmart	General merchandisers	572,754	2.4%	2,300,000	Bentonville, Arkansas

1	2	Amazon	Retail and Cloud Computing	469,822	21.7%	1,608,000	Seattle, Washington

2	3	Apple	Electronics industry	365,817	33.2%	154,000	Cupertino, California

3	4	CVS Health	Healthcare	292,111	32.0%	258,000	Woonsocket, Rhode Island

4	5	UnitedHealth Group	Healthcare	287,597	11.8%	350,000	Minnetonka, Minnesota

...	...	...	...	...	...	...	...

95	96	General Dynamics	Airspace and defense	38,469	8.7%	103,100	Reston, Virginia

96	97	CHS	Agriculture cooperative	38,448	1.4%	9,941	Inver Grove Heights, Minnesota

97	98	USAA	Financials	37,470	3.2%	37,335	San Antonio, Texas

98	99	Northwestern Mutual	Insurance	36,751	8.8%	7,585	Milwaukee, Wisconsin

99	100	Nucor	Metals	36,484	81.2%	28,800	Charlotte, North Carolina

100 rows × 7 columns

    
    







