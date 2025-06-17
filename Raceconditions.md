# Race conditions
Look for multiple accounts that you can do things like transfer funds to
1. Navigte to site
2. Enable burp proxy
3. launch burp
4. Take the POST request and send it to the repeater
5. Create a group off of the first request
6. Create repeated posts (Control + R)
7. Set the group to **Send Group (parallel)**
8. This should transfer funds to another account
