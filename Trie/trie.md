trie is used when dfs is done along with moving in word search prefix dictionary,

best example is word search ii,
see how we have to use prefix set in order to reduce unnecessary dfs calls,
and avoid reaching same word again 
and continue search in same prefix if another word with prefix+char exists in dict.


trie is basically used as prefix tree. similar to tree of a prefix set needed in word search ii better code.
