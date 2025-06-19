# Walking an application playbook
1. Navigate around the pages that are available. Search for interesting information that may lead to future information
2. View the page source
  - Check different directories
  - Check for HTML notes
  - Check for framework information
3. Developer Tools
  - For paywall, inspect the block page, look for div.premium-customer-blocker. DIsplay should show as block. Change to none and it will appear
  - If you see a popup flash.
    - go to debugger
    - Find the .js page that looks associated
    - click on the {} option at the bottom to read it easier
    - Find the line that says ```{flash['remove']();},0x5);```
    - click on the line (this enters a break point)
