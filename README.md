# WhatsApp Dark Theme

### Google Chrome Extension

This is a simple Google Chrome Extension to change the WhatsApp web app to the dark theme

If you don't know, WhatsApp has already a css class to change the theme to dark but, it's disabled by default.
&nbsp;

This code just add the class _"dark"_ to body tag of DOM on WhatsApp web page.

    (function () {
      const body = document.getElementsByTagName('body')[0];
      if (body.classList.contains('dark')) return;
      body.classList.add('dark');
    })();

&nbsp;

**🌚 🎉 You can check out the extension here: https://bit.ly/WhatsAppWebDark**
