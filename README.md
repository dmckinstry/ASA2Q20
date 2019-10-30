# App Specialist Airlift - Hands-on exercises

The following links are meant to help Airlift attendees get up-to-speed on GitHub as quickly as possible.  This repo is expected to be transitory and will be deleted, but before it is more official assets will be made available.

## 1 - I have a GitHub ID and it is linked to the Microsoft org

Start here if you don't already have a GitHub ID that is liked to the Microsoft org, including 2FA:
1. Sign up for a GitHub ID: https://github.com/join
1. Review Microsoft's policy on Open Source (as if I expect you to really do this):  https://docs.opensource.microsoft.com/
1. Link your account and join the appropriate MS orgs: https://docs.opensource.microsoft.com/tools/github/accounts/linking.html

## 2 - I know how to use GitHub and GitHub Learning Labs

Even if you've already used GitHub, Learning Lab is a great resource.  It can simulate multi-user interactions similar to real-world GitHub usage. It will guide you though common scenarios collaborating with a bot to drive the lessons. It is also great to be familiar with them so that you can share with customers.

https://lab.github.com - you can figure the rest out pretty easily.

## 3 - I know how to leverage GitHub Security features

Security will be a big reason for customers to consider GitHub in the enterprise.

1. Fork microsoft/ContosoAir which is a demo repo with a few vulnerabilities
1. Enable **Security Alerts** in your repo settings
1. Enable **Automated security fixes**
1. Review and accept and recommended fixes / PRs. 
1. You can delete the repo when you're done; you can replay this demo easily with customers.

## 4 - I have can use GitHub Actions to deploy to Azure

1. Familiarize yourself with GitHub Actions: https://github.com/features/actions
1. Search the [GitHub Marketplace](https://github.com/marketplace?type=actions&query=Azure) for Actions tagged with GitHub
1. Review the GitHub Actions for Azure repo: https://github.com/azure/actions
1. Review the GitHub Actions for Azure samples:  https://github.com/Azure/actions-workflow-samples
1. Run through the preview hands-on lab: https://github.com/microsoft/azuredevopslabs/tree/githubactions/labs/vstsextend/githubactions
1. Reverse engineer a GitHub Actions Challenge (in progress, including Secrets, Infra as Code, ...): https://github.com/dmckinstry/ContosoAir/

## 5 - I can integrate GitHub with other DevOps tools

1. Perform the Azure Board/GitHub integration lab: https://azuredevopslabs.com/labs/vstsextend/github-azureboards/
1. Perform the GitHub/Azure Pipelines integration lab: https://azuredevopslabs.com/labs/vstsextend/github-azurepipelines/
1. Exercise the VS Code integration: https://azuredevopslabs.com/labs/azuredevops/githubpullrequests/
1. Review the GitHub Marketplace for other integration opportunities:  https://github.com/marketplace

## 6 - Extra credit :)

I'm working on a challenge for a partner Challenge. Feel free to review and contribute to the challenge repo and the 'solution' repo.

1. Challenge repo (will eventually contain packaged source): https://github.com/dmckinstry/CY2019Q4-DevOpsChallenge
1. Challenge solution reference:  https://github.com/dmckinstry/ContosoAir

