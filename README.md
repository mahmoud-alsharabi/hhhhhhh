# hhhhhhh
fciucugckolhl
gouijpio[poip[

uiguhy9ighupo


+-----------------+          +--------------+
           |    Observer     |          |   GitHub     |
           |    Interface    |          |     API      |
           +-----------------+          +--------------+
                   |                            |
                   |                            |
                   |                            |
          +-------------------+       +-----------------+
          |    PullRequest   |  <--  | GitHubRepository|
          |    Observer      |       |  Implementation  |
          +-------------------+       +-----------------+
                   |                            |
                   |                            |
         +-----------------------+     +---------------------+
         | PullRequestObserver    |     | GitHubRepositoryObserver|
         +-----------------------+     +---------------------+
                   |                            |
                   |                            |
      +-------------------------+     +------------------------+
      | PullRequestObserverImpl  |     | GitHubRepositoryObserverImpl|
      +-------------------------+     +------------------------+
