# Better Brave Browser  Preview
![image](https://github.com/user-attachments/assets/f61dedeb-80f5-4742-bef1-6a69087b3a2d)


# Synopsis

### Tired of having crypto in your browser? Tired of preinstalled ads in a browser? Tired of the annoying features nobody asked for? Look no further, remove all the garbage crypto scams, ads and AI chatbots from the Brave browser.


## Appearance Settings

Show old homepage (chromes): brave://new-tab-page/

![Screenshot From 2026-01-06 03-15-40 (1)](https://github.com/user-attachments/assets/4d2919fc-69e5-4983-a76d-337016df2251)

![Screenshot From 2026-01-06 03-23-38](https://github.com/user-attachments/assets/ed62dcbe-731b-435f-97b3-967d2bf37b8d)

## Data collection (Under Privacy and settings)

![image](https://github.com/user-attachments/assets/05f94aed-d9ae-4fef-b589-bd222f6103c0)

## Brave Flags
### Type this in the url bar: brave://flags/

![image](https://github.com/user-attachments/assets/15763528-b20b-4ba1-aa3e-5fd0e99c1106)

### Now this in the menu search each of the following in the flags bar and disable them:

Flags list (Disable them):

![image](https://github.com/user-attachments/assets/d39d10d2-5c3c-42c5-b6ac-90b4aafc3478)

Updated 1/06/26
- #brave-super-referral
- #brave-rewards-new-rewards-ui
- #brave-rewards-platform-creator-detection
- #native-brave-wallet
- #brave-wallet-zcash
- #brave-wallet-bitcoin
- #brave-wallet-cardano
- #brave-news-peek
- #brave-news-feed-update
- #brave-rewards-gemini
- #brave-ai-chat
- #brave-ai-first
- #brave-ai-chat-history
- #brave-ai-host-specific-distillation
- #brave-ai-chat-context-menu-rewrite-in-place
- #brave-ai-chat-page-content-refine
- #brave-ai-chat-allow-private-ips
- #brave-ai-chat-open-leo-from-brave-search
- #brave-ai-chat-web-content-association-default
- #brave-ai-rewriter
- #brave-omnibox-tab-switch-by-default
- #brave-history-more-search-results
- #brave-ntp-search-widget

## Windows Only
If you're using Windows, you can achieve even better results than the ones obtained by applying the section [Brave Flags](#brave-flags).

If you're not using Brave on Windows, please skip this section and go to [Brave Flags](#brave-flags) instead.

**Note:** If you apply this method, you should skip the [Brave Flags](#brave-flags) section, as we will completely disable all Brave bloatware at once.

### How to create and apply the registry file

1. Create a txt file wherever you want. For example, create a file in your Desktop called `brave_debloater.txt`

2. Open the file and paste the content below

```reg
Windows Registry Editor Version 5.00
[HKEY_LOCAL_MACHINE\Software\Policies\BraveSoftware\Brave]
"BraveRewardsDisabled"=dword:00000001
"BraveWalletDisabled"=dword:00000001
"BraveVPNDisabled"=dword:00000001
"BraveAIChatEnabled"=dword:00000000
```

3. Save the file and change its extension to `.reg`. We named the file `brave_debloater.txt` so we will change it to `brave_debloater.reg`

4. Close Brave Browser if opened

5. Execute and click yes when asked

Now, if you open Brave, all bloatware will be gone.

## uBlock filters:


---

> **Note:** As of **7/14/2025**, this section is no longer necessary. Brave's development team continues to ignore custom filter updates, these likely won't work as expected.

<details>
<summary><strong>⚠️ Deprecated Filters (Click to expand)</strong></summary>

<br>

![image](https://github.com/user-attachments/assets/ad43d99c-c330-47e1-8593-54b6de5a2d29)  
![image](https://github.com/user-attachments/assets/3810ed7f-811b-43c7-927d-d0503af18155)


~~### Links (They are hyper linked — right-click to copy)~~  
~~- Ads: [uBlock Ads](https://raw.githubusercontent.com/uBlockOrigin/uAssets/refs/heads/master/filters/filters.txt)~~  
~~- Privacy: [uBlock Privacy](https://raw.githubusercontent.com/uBlockOrigin/uAssets/refs/heads/master/filters/privacy.txt)~~  
~~- Quick fixes: [uBlock Quick Fixes](https://raw.githubusercontent.com/uBlockOrigin/uAssets/refs/heads/master/filters/quick-fixes.txt)~~  
~~- Unbreak: [uBlock Unbreak](https://raw.githubusercontent.com/uBlockOrigin/uAssets/refs/heads/master/filters/unbreak.txt)~~  
~~- Badware: [uBlock Badware](https://raw.githubusercontent.com/uBlockOrigin/uAssets/refs/heads/master/filters/badware.txt)~~  

~~### Adguard Filters~~  
~~- Adguard: [Adguard Base](https://raw.githubusercontent.com/AdguardTeam/FiltersRegistry/master/filters/filter_2_Base/filter.txt)~~  
~~- Adguard Tracking Protection: [Adguard Tracking](https://raw.githubusercontent.com/AdguardTeam/FiltersRegistry/master/filters/filter_3_Spyware/filter.txt)~~  
~~- Adguard Annoyance: [Adguard Annoyances](https://raw.githubusercontent.com/AdguardTeam/FiltersRegistry/master/filters/filter_14_Annoyances/filter.txt)~~  

~~### Easylist~~  
~~- Easylist: [Easylist](https://easylist.to/easylist/easylist.txt)~~  
~~- Easylist Privacy: [Easylist Privacy](https://easylist.to/easylist/easyprivacy.txt)~~  
~~- Easylist Cookies: [Easylist Cookies](https://secure.fanboy.co.nz/fanboy-cookiemonster.txt)~~  

~~### Malware / Phishing~~  
~~- [Malware Filter](https://malware-filter.gitlab.io/malware-filter/urlhaus-filter.txt)~~  
~~- [Phishing Filter](https://malware-filter.gitlab.io/malware-filter/phishing-filter.txt)~~

</details>

