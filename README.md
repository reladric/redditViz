
#Reddit Analyzer
###A visual analysis of reddit’s most active communities - subreddits

####By
Li, Xiongjie  
Madhavan, Sarvothaman

##Abstract  
Reddit is a type of online community where users post "content" and vote on these content. The word Reddit is a word play on the phrase "read it?". Initially started as a community to share and vote on news links from the Internet, it quickly evolved into a platform where people share stories from Internet as well from thier own lives. Ability to comment on stories was later introduced and reddit comments add information, context and humour to the  stories. Reddit content is organized as communitites called 'subreddits' focussed on certain topic of interest. Anyone can create a subreddit; each subreddit is moderated by volunteers. [<sup>[1]</sup>](#One).  

Reddit Analyzer, in a very short term, attempts to find patterns in Reddit conversations. These conversations can happen around text based stories or around links that users share. A very simplified examples of some such patterns would be "What topic of discussion does the community on space interested in most?" "When is the community on nfl most active?". Ultimately, Reddit Analyzer can evolve into a either content discovery engine for reddit based on patterns and personal preferences or into a means for validating authenticity of arguments.

##Introduction
Since the identity of a person is not tied with Reddit persona, we can obtain “Honest” data i.e Semi-anonymity ensures honest opinions and thoughts are expressed. This makes the data valuable and potentially insightful. For any given topic it is very likely there is a subreddit. This opens up the chance to apply our analysis methodologies for any topics on any similar platform. This can have impacts in areas such as marketing, customer feedback, product development.


##Background and Related Work
Reddit Map is a project which uses similar dataset. In Reddit Map, subreddits are clustered based on thier shared  properties. The paper by <i>Choi, Ahn et al (Submitted) [<sup>[2]</sup>](#Two)</i> also uses similar dataset to quantify reddit comments in terms of Volume, Responsiveness and Virality. There are also projects such as snoopsnoo [<sup>[3]</sup>](#Three) which analyses user activity and Reddit Insight [<sup>[4]</sup>](#Four) which gives a overall visualization of subreddit statistics such as "The most popular nouns per SubReddit" and this relies on someone deliberately requesting to track a post or user.
Reddit Analyzer differs from above project in that it seeks to not only visually represent data from certain subreddit but also seeks to find meaningful patterns.

The initial data set to be used is from Aug 2015 subreddit posts available from google big query [<sup>[5]</sup>](#Five). Once the method and means of explaining patterns are established the methodology can be applied to dynamic rolling data.

##Research Questions and Working Hypothesis

The hypothesis that on which the project is based on is that for any given subreddit there are patterns in posts with respect to author, time, keywords (and hence topics). With that hypothesis in mind, some of the aspects which Reddit Analyzer will try to explore are,
1. Analyze the most popular posts using visualization such as word cloud.
2. Analyze authors on reddit by making visaluzations such as activity histogram. 
3. Analyze the website that are commonly used on reddit by url.


##References
[1] <a href="One"></a> [About Reddit](https://www.reddit.com/about)  
[2] <a href="Two"></a> D. Choi, Y. Ahn, J. Han, B. Chun, T. Chung, T. Kwon. Characterizing Conversation Patterns in Reddit: From the Perspectives of Content Properties and User Participation Behaviors. ACM Conference on Online Social Networks, 2015 (Submitted)  
[3] <a href="Three"></a> [SnoopSnoo](http://snoopsnoo.com)  
[4] <a href="Four"></a>[Reddit Insight](http://www.redditinsight.com)  
[5] <a href="Five"></a>[Big Query Data set](https://www.reddit.com/r/bigquery/comments/3cej2b/17_billion_reddit_comments_loaded_on_bigquery/)

