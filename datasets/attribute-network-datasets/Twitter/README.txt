Multi-View Twitter Datasets
Version: 2013-01-24
---------------------------------------------
This archive contains the datasets data used in the paper "Producing a Unified Graph Representation from Multiple Social Network Views". D. Greene, P. Cunningham (2013). 

For more details contact derek.greene@ucd.ie or visit http://mlg.ucd.ie/aggregation

This archive includes five datasets (football, olympics, politics-ie, politics-uk, rugby) collected from Twitter in 2012. The datasets are made available for further non-commercial and research purposes only. They are provided in pre-processed matrix format only. 

To comply with the Twitter TOS, we do not include any raw tweets or other full text content. Users and user lists are referenced by their unique Twitter IDs, as opposed to full names or screen names.

The datasets are provided in a single archive. Each dataset is contained within its own sub-directory, and 9 different "views" of each dataset are provided in sparse matrix representation. For a dataset <name>, the view files have the following prefixes:

    * <name>-follows, <name>-followedby, <name>-mentions, <name>-mentionedby, <name>-retweets, <name>-retweetedby,  <name>-listmerged500, <name>-lists500, <name>-tweets500 

The formats of the files in each sub-directory are as follows:

    * <name>.ids: List of all users for the dataset <name>, specified as one user ID per line.
    * <name>.communities: The ground truth community information, with one community per line. Community members are specified in terms of their user IDs.
    * <name>-<view>.mtx: Feature-User matrix for the <view> on the dataset the dataset <name>. The users (columns) are specified in terms of their user IDs.
    * <name>-<view>.features: The names or identifiers of the features corresponding to the Feature-User matrix for the <view> on the dataset the dataset <name>, with one feature name per line.

If you find this data useful, we would encourage you to cite the paper above.
