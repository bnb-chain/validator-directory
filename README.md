# Validator-directory

## Dictionary
| Moniker               |                                                                                       |                                                                                                           |
|-----------------------|---------------------------------------------------------------------------------------|-----------------------------------------------------------------------------------------------------------|

## What is a Validator Profile?

Binance Smart Chain validators power the blockchain network by processing transactions and signing blocks. Validator candidates need to get supports from delegator community to increase their total voting power. This repository is a place for validator candidates to give potential delegators a brief introduction about your team and infrastructure, and present your ecosystem contributions.


## How to change your Validator Profile

1. Fork this repository to your own GitHub account.

2. Clone the repo from your own account. 

```sh
git clone git@github.com:xxxxxx/validator-directory.git
cd validator-directory/
```

3. Copy the template [README.md](./template/README.md) and [JSON Profile](./template/profile.json) into your folder inside `validators/<your-valoper-address>`.

4. Change the contents and add your information as necessary. You can modify anything within your own designated validator folder, including adding image files, new folders, etc.

5. Commit and push the information to your repo.

```sh
git add -A
git commit -m "Edit validator profile"
git push origin main
```

6. Under your repo page, click the “New pull request” button. Make a Pull Request with our repository with a summary of changes.

7. We will review your PR as soon as possible. 


### profile.json

Registered validators (validators who have submitted a profile) can opt-in to receive support by putting their contact information in `profile.json`. 

```javascript
{
    "contact": { // contact info for delegators / outreach
        "email": "validator@example.com",
        "telegram": "@validator"
    },
    "notifications": { // notification settings
        "email": "technicalemail@example.com" // email to receive notifications
    }
}
```

