# zendesk-private-comment

This app is a sidebar app for Zendesk tickets that allows the agent to add a Private Comment to the current ticket they are working on.

Please submit bug reports to Michael. Pull requests are welcome.

Uploading to Zendesk Instructions
Install Zendesk Apps Tools (ZAT) in order to Zip/Compress the file. NOTE: Trying to compress/zip file manually will throw an error when uploading. Follow these steps to successfully create zip file.

run gem install rake
run gem install zendesk_apps_tools
run zat package
This will create a new .zip file which can be found at zendesk-private-comment/tmp

Go to https://vidangel.zendesk.com/agent/admin/apps/manage and/or https://vidangelstudios.zendesk.com/agent/admin/apps/manage
On the Zendesk Private Comments app, click the gear icon and update the zipped file