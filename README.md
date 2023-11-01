# voken
拉取请求：写入
    步骤：
      - name : '自动分配问题'
        if : github.repository == ' lensterxyz/lenster '
        if : github.repository == ' heyxyz/hey '
        使用：pozil/auto-assign-issue@v1
        与：
          回购令牌：${{secrets.GITHUB_TOKEN}}
