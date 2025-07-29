# 01 Fork And Setup GitHub Actions
This step guides you through forking the repository and setting up GitHub Actions to prepare for the next steps in deploying a Go application to Sakura's AppRun service.

> [!IMPORTANT]
> Purpose: 使你初步了解如何在 GitHub Actions 中設置運行 Workflow 所需設定

> [!IMPORTANT]
> Goal: 設定 GitHub Actions 的 Permissions Secrets 和 Variables，並透過 Trigger 運行 Workflow 並確認

## How to enable GitHub Actions

## How to settings GitHub Actions Secrets and Variables

## To Do List
- [ ] Fork the (repository)[https://github.com/ippanpeople/test]
- [ ] Set up the GitHub Actions
    - [ ] ensure Workflow permissions are set to `Read and write` and `Allow GitHub Actions to create and approve pull requests`
    - [ ] Create Actions Secret `SLACK_WEBHOOK_URL` with your Slack Incoming Webhook URL
    - [ ] Create Actions Variable `AUTHOR_NAME` with your name
    - [ ] Create Actions Variable `REPOSITORY` with your GitHub repository link
- [ ] Configure the workflow to send a message to Slack
    - [ ] Update "text" in the workflow with your message
    - [ ] Push the changes to your repository
- [ ] Test the workflow to ensure it sends a message to Slack
    - [ ] Go to the Actions tab in your repository
    - [ ] Select the workflow and click on "Run workflow"
    - [ ] Verify the message appears in your Slack channel


