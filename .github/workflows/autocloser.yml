name: Autocloser
on: [issues]
jobs:
  autoclose:
    runs-on: ubuntu-latest
    steps:
    - name: Autoclose issues
      uses: roots/issue-closer@v1.1
      with:
        repo-token: ${{ secrets.GITHUB_TOKEN }}
        issue-close-message: "@${issue.user.login} bugs and new suggestions should be reported on the [Developer Community forum](https://developercommunity.visualstudio.com). It is centralized, better equipped for group voting, and has more visibility."
        issue-pattern: "a^"