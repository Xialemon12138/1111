[mitm]
hostname = *m6aw*,*3ju7q*,*gar48*,*68bhf*,*z0pf9*,*cloudfront*

[rewrite_local]
^http[s]?:\/\/.*(m6aw0|3ju7q|gar48|68bhf|z0pf9|cloudfront).+\/api\/app\/(recommend\/vid\/(list|ad)|mine\/info|ping\/domain\/h5|vid\/(section|info|list|user\/count)|recreation\/list) url script-response-body https://raw.githubusercontent.com/Yuheng0101/X/main/Scripts/PFDSP/pfdsp.js# 1111
