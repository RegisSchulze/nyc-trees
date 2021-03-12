# Your first data cleaning project - NYC Trees

- Repository: `nyc-trees`
- Type of Challenge: `Learning`
- Duration: `1 day`
- Deadline: `12/03/2021 04:00 PM`
- Deployment strategy :
  - Github page
- Team challenge : `solo`

![NYC Picture (Image)](https://www.hudsonallergy.com/wp-content/uploads/2016/04/nyc-street-trees.jpg)

## Mission objectives

- Be able to use pandas
- Be able to clean a data set

## The Mission

The Department of Environmental Conservation, from New York city, has recently made the news by telling the people that they needed their help. Indeed, their request is simple: They needed the people of New York city, whether young or old, to go to the nearest tree in their street and gather information about that tree. This is all in an effort to make the population aware that nature is important, even in big Metropolis like NYC. Now that they have heard back from the people, the DEC noticed that they missed a crucial step. They forgot to give the people a data collection guide, and so the data they received back is a bit messy.

Can you help them clean the data so that they can begin to raise awareness to ecological issues, such as climate change ?

### Must-have features

- The dataset contains no missing values ("" or null)
- No duplicates.
- Values are consolidated
- Data format is correct
- No blank spaces (ex: " I love python " => "I love python")

### Nice-to-have features

- The more rows of data you use, the better. However, pay attention that the more data you have, the longer each operation needs to execute.

### Miscellanous information

An example dataset `data_100000.csv` has already been downloaded for you in
[../../additional_resources/datasets/NYC Trees/](../../additional_resources/datasets/NYC%20Trees/data_100000.csv), which has 100000 rows for around 21.5MB. The full file is more than 10x larger but it is not required to use the full file. However, **please use at least 100 000 rows** for the final version. Of course, you can always test your code on smaller data sets.

If you want to download a differently sized dataset, you can use the script `download.py` located in
[../../additional_resources/datasets/NYC Trees/](../../additional_resources/datasets/NYC%20Trees/download.py)
It will create a CSV file similar to `data_100000.csv` in your current directory.

See the usage of the script using

```bash
python download.py -h
```

You will need the `sodapy` library for downloading the data set.

```bash
pip install sodapy
```
