Door43 Pages
============

This repository is kept for historical reasons, all the data here is
outdated.

For the most up to date information, please check out the repositories for
each language in the Door43 organization.  For example, all of the English
resources are available at https://github.com/Door43/d43-en.  The full list
may be seen at
https://github.com/search?o=desc&q=user%3ADoor43+d43-&s=updated&type=Repositories.

If you want to clone all ~7,000 of the repositories, you could run the
following on a Linux system:

    $CODES=`wget -q -O - https://api.unfoldingword.org/obs/txt/1/codes-d43.txt`
    for LANG in $CODES; do
        git clone https://github.com/Door43/d43-$LANG
    done

