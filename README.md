# Stand with Israel banner
We stand with Israel banner for a website.

The following is a zero-dependencies, zero-setup way to add a banner to your website supporting Israel and the Israeli people.
Simply paste the code below under the body tag in your index.html file.

```html
<style>
    body {
      margin-top: 50px;
    }

    .support-israel {
      position: absolute;
      left: 0;
      top: 0;
      right: 0;
      background: #20283e;
      display: flex;
      justify-content: center;
      padding-top: 5px;
      padding-bottom: 5px;
      z-index: 10000;
      text-decoration: none;
      font-family: arial;
      align-items: center;
    }

    .support-israel__flag {
      height: 40px;
      margin-right: 10px;
    }

    .support-israel__label {
      color: white;
      font-size: 20px;
    }
  </style>
  <div class="support-israel">
    <div class="support-israel__flag" role="img" aria-label="Flag of Israel">
      <svg width="40px" height="40px" viewBox="0 0 36 36" xmlns="http://www.w3.org/2000/svg"
        xmlns:xlink="http://www.w3.org/1999/xlink" aria-hidden="true" role="img" class="iconify iconify--twemoji"
        preserveAspectRatio="xMidYMid meet">
        <path fill="#EDECEC" d="M20.666 19l-.467.809h.934zM18 21.618l.467-.809h-.934z"></path>
        <path fill="#EEE" d="M0 25h36V11H0v14zM.294 7.5h35.413A4 4 0 0 0 32 5H4A3.999 3.999 0 0 0 .294 7.5z"></path>
        <path fill="#EDECEC"
          d="M21.133 16.191h-.934l.467.809zm-5.332 0h-.934l.467.809zm3.243 3.618L20.089 18l-1.045-1.809h-2.088L15.911 18l1.045 1.809zM15.334 19l-.467.809h.934zM18 14.382l-.467.809h.934z">
        </path>
        <path fill="#0038B8" d="M.294 7.5A3.982 3.982 0 0 0 0 9v2h36V9c0-.531-.106-1.036-.294-1.5H.294z"></path>
        <path fill="#EEE" d="M.294 28.5h35.413A4 4 0 0 1 32 31H4a3.999 3.999 0 0 1-3.706-2.5z"></path>
        <path fill="#0038B8"
          d="M.294 28.5A3.982 3.982 0 0 1 0 27v-2h36v2c0 .531-.106 1.036-.294 1.5H.294zm16.084-7.691L18 23.618l1.622-2.809h3.243L21.244 18l1.622-2.809h-3.243L18 12.382l-1.622 2.809h-3.243L14.756 18l-1.622 2.809h3.244zm1.622.809l-.467-.809h.934l-.467.809zm3.133-5.427l-.467.809l-.467-.808h.934zM20.666 19l.467.808h-.934l.467-.808zM18 14.382l.467.809h-.934l.467-.809zm-1.044 1.809h2.089L20.089 18l-1.044 1.809h-2.089L15.911 18l1.045-1.809zm-1.155 0l-.467.809l-.467-.808h.934zM15.334 19l.467.808h-.934l.467-.808z">
        </path>
      </svg>
    </div>
    <div class="support-israel__label">
      We stand with the people of Israel
    </div>
  </div>
```

Based on https://github.com/evermade/support-ukraine-banner
