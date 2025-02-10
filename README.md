# EBT-Site3

This is the template repository for 
SC-Voice.net language-specific websites
such as:

* [ebt-site.sc-voice.net](https://ebt-site.sc-voice.net): the sample website for this template repository.
* [sc-voice.net](httsp://sc-voice.net): multilinguaal SC-Voice.net
* [Dhammarage.net](httsp://dhammaregen.net): DE SC-Voice.net
* [es.sc-voice.net](httsp://es.sc-voice.net): ES SC-Voice.net
* [fr.sc-voice.net](httsp://fr.sc-voice.net): FR SC-Voice.net
* [pt.sc-voice.net](httsp://pt.sc-voice.net): PT SC-Voice.net
* [ru.sc-voice.net](httsp://ru.sc-voice.net): RU SC-Voice.net

## Instructions

### Github Account

To create a language-specific ${appName} website, you'll need a
[Github account](https://docs.github.com/en/get-started/signing-up-for-github/signing-up-for-a-new-github-account) (Note: a free account is fine).
Your Github account will own and administer the new website.
Although your new website will share the 
SC-Voice.net API servers with other websites,
the new website will also have its own content
intended for a specific language community.

### Create an Organizational Account

For collaborative administration,
you new website will need a Github
[organizational account](https://docs.github.com/en/organizations/collaborating-with-groups-in-organizations/creating-a-new-organization-from-scratch).
An organizational account will help you work with others
on content creation within your language community.
Most SC-Voice.net websites are part of the SC-Voice organization.
You can also create your own organization (e.g., Dhammaregen).

### Account Settings

Your new website relies on 
[Github Actions](https://github.com/features/actions)
for updating content and software.
Navigate to your Github account and click <kbd>Settings</kbd>
In the left navbar, open the <kbd>Actions</kbd> panel.
Then select <kbd>General</kbd> and scroll down to 
_Workflow Permissions_.
Update workflow permissions as follows:

<a href="https://ebt-site.sc-voice.net/img/account-settings.png">
  <img style="height: 50%"
    src="https://ebt-site.sc-voice.net/img/account-settings.png" />
</a>

Click <kbd>Save</kbd> to update your workflow permissions.

### Create new repository

1. Login to Github
1. Then click the <kbd>Use this template</kbd>
button, and choose <kbd>Create new repository</kbd>.

<img src="https://ebt-site.sc-voice.net/img/use-this-template.png" />. 

### Configure new repository

After clicking <kbd>Create new repository</kbd>,
you'll see a new webpage form for you to fill out:

1. Specify the organizational account (e.g., "sc-voice")
1. Specify the new repository name (e.g., "ru_sc-voice_net")
1. Choose <kbd>Public</kbd> repository (free)
1. Select <kbd>Include all branches</kbd>
1. Review your form entries
1. When ready, click ```Create repository from template```

We now need to enable Github pages for your new repository.

### Enable Github pages

Navigate to your new repository and click <kbd>Settings</kbd>.
Then click the "Pages" link in the left navigation bar.
Configure the ```Build and deployment``` settings as shown below:

<a href="https://ebt-site.sc-voice.net/img/github-pages.png">
<img src="https://ebt-site.sc-voice.net/img/github-pages.png" style="width:35em">
</img>
</a>. 

Also verify that your repository has the following settings for
<kbd>Actions</kbd> <kbd>General</kbd>:

<a href="https://ebt-site.sc-voice.net/img/account-settings.png">
  <img style="height: 50%"
    src="https://ebt-site.sc-voice.net/img/account-settings.png" />
</a>

Next, you'll need to edit the EBT-Site configuration.
You won't be able to view your new website until you have configured it correctly.
See [EBT site configuration](#/wiki/design/config).

