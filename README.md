# github-social-network
Example of using neo4j with rails to simulate a social network


Nodes:
  User
  PullRequests

Relationships:
  User hasOpen PullRequests
  User isAReviewerOn PullRequests
  User isFriends with Other Users

Attributes:
  PullRequests are Active
