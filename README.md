# Instagram Data Scraping Solutions.md

![](https://ahmetozel.github.io/instagram_data_scraping_solution/logo.png)


###Description

- It has been developed by using PHP and NodeJS.
- Thanks to its simple logic, it can be easily converted to other programming languages such as Python, Ruby, .NET and etc. ( other platforms will be supported.)
- We can say that this is like an unofficial API but this is not API.
- It needs an instagram account and 2FA has to be closed for this account. (If you want to scrape private account, you need to follow with account that you will use in the software.)
- Thanks to“our IPv6 proxy solution", you will not get any rate limitation error. Also you can do multi-processing. (Additional fees will included for our IPv6 proxy solution.)
- Our PHP script has some functions. These are 'curl' and 'shell_exec'. Therefore you should not forget: You cannot use with shared hosting.

###FlowChart

```flow
st=>start: 
op1=>operation: $access_hash = shell_exec('node script.js some parameters');
op2=>operation: $data = CURL($url.'&'.$access_hash); with CURLOPT_PROXY
cond=>condition: Is data scraping finish?
e=>end: End

st->op1->op2->cond
cond(yes)->e
cond(no)->op2
```
<br /><br /><br /><br /><br /><br /><br /><br /><br /><br /><br /><br /><br /><br /><br /><br /><br /><br /><br /><br />
###Pricing
[View to prices](https://ahmetozel.github.io/instagram_data_scraping_solution/pricing.html "View to prices")

###Languages
![](https://ahmetozel.github.io/instagram_data_scraping_solution/usa.png)![](https://ahmetozel.github.io/instagram_data_scraping_solution/turkey.png)