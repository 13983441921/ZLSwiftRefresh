# ZLSwiftRefresh
![image](https://github.com/MakeZL/ZLSwiftRefresh/blob/master/screenhost.gif)

This is Swift version pull Refresh code.
-------
## Use
	self.tableView.toRefreshAction({ () -> () in
            println("toRefreshAction success")
        })
       
	 self.tableView.toLoadMoreAction({ () -> () in
            println("toLoadMoreAction success")
        })

Continue to update!

