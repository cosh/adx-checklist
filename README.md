# The Azure Data Explorer (kusto) Service Checklist

![Build and deploy on prod](https://github.com/cosh/adx-checklist/workflows/Build%20and%20deploy%20on%20prod/badge.svg?branch=master)

Deployed version can be found here: [aka.ms/adx.checklist](https://aka.ms/adx.checklist)
![ADX Checklist](https://raw.githubusercontent.com/cosh/adx-checklist/master/src/img/social/facebook-banner.jpg)

The ADX Checklist is a (tentatively) exhaustive list of all elements you need to think of when preparing a cluster for production. It is based on all common best practices agreed around Azure Data Explorer (kusto) or documented [here](https://docs.microsoft.com/en-us/azure/data-explorer).

## Author

**[Henning Rauch](https://github.com/cosh)**

## Contributors

**[Louis-Guillaume MORAND](https://github.com/lgmorand)**

## How to contribute

Fork the repo, add the best practices in the items.json file (at least in english which will remain the single source of trust) and then do a pull request **on the staging branch** ;-)

Be aware that we want to keep a list an exhaustive as possible but also a list which met **common usage**. Depending on your context, you may have custom best practices which may apply only to your case.

## How to add a translation

There are up to six steps:

- copy the folder **/data/en** and translate all information
- in the localized files, modify the URL to target your language (i.e: docs.microsoft.com/**YOURLANG**/link)
- copy the file **src/views/en.html** and translate it
- ensure that a flag is existing for your language (**/src/img/flags**)
- add a link for your lang in the header (**src/view/base/header.pug**)
- add your name to contributors

## Thanks

The source code itself is a modified version of the [Front-End Checklist](https://github.com/thedaviddias/Front-End-Checklist) which was created by [David Dias](https://github.com/thedaviddias)
Icons made by Freepik from [www.flaticon.com](www.flaticon.com) is licensed by CC 3.0 BY
The project has been forked from the [aks checklist project](https://github.com/lgmorand/aks-checklist) created by **[Louis-Guillaume MORAND](https://github.com/lgmorand)**. Thx a lot for your support!

## License

[![CC0](https://i.creativecommons.org/p/zero/1.0/88x31.png)](https://creativecommons.org/publicdomain/zero/1.0/)
