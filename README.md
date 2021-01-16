# Spark_Funds-Investment_Analysis
Spark Funds, an asset management company wants to make investments in a few companies. The Management of Spark Funds wants to understand the global trends in investments so that they can take the investment decisions effectively. The objective of the analysis is to identify the suitable funding type, best English speaking countries and sectors for making investments.

# Business and Data Understanding
Spark Funds has two constraints for investments:
    1. It wants to invest between 5 to 15 million USD per round of investment
    2. It wants to invest only in English-speaking countries for the ease of communication
    
In analysis, a country is considered English speaking only if English is one of the official languages in that country. The list of countries is scraped from the Wiki page
https://en.wikipedia.org/wiki/List_of_territorial_entities_where_English_is_an_official_language

The strategy of Spark Funds is to invest where most other investors are investing. This pattern is often observed among early stage startup investors. The real investment data is taken from crunchbase.com, so the insights you get may be incredibly useful.

The business objectives and goals of data analysis are listed below.

    1. Business objective: The objective of the analysis is to identify the best sectors, countries, and a suitable investment type for making investments. The overall strategy is to invest where others are investing, implying that the best sectors and countries are the ones 'where most investors are investing'.

    2. Goals of data analysis: The goals of the analysis are divided into three sub-goals:
        a). Investment type analysis: Comparing the typical investment amounts in the venture, seed, angel, private equity etc. so that Spark Funds can choose the type that is best suited for their strategy.
        b). Country analysis: Identifying the countries which have been the most heavily invested in the past.
        c). Sector analysis: Understanding the distribution of investments across the eight main sectors. 

Note that we are interested in the eight 'main sectors' provided in the mapping file. The two files "companies and rounds2" have numerous sub-sector names; hence, one needs to map each sub-sector to its main sector.
