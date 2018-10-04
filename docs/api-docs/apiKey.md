---
layout: default
title: Request an API Key
nav: key
---
ATTENTION: We have transitioned to include an email verification step for SAM Application Programming Interface (API) key sign up. All API keys used to access SAM APIs must have a verified email address. If your existing API key no longer works, please submit a new request.

{% raw %}
<div id="apidatagov_signup">Loading signup form...</div>
<script type="text/javascript">
  /* * * CONFIGURATION VARIABLES: EDIT BEFORE PASTING INTO YOUR WEBPAGE * * */
  var apiUmbrellaSignupOptions = {
    registrationSource: 'gsa-dss',
    apiKey: '2cnHYrvWoVvKnV7BahvMvxOWa8z4RHx9K7MtkS5G',
    emailFromName: 'DSS Team Developer Hub',
    verifyEmail: true
  };

  /* * * DON'T EDIT BELOW THIS LINE * * */
  (function() {
    var apiUmbrella = document.createElement('script'); apiUmbrella.type = 'text/javascript'; apiUmbrella.async = true;
    apiUmbrella.src = 'https://api.data.gov/static/javascripts/signup_embed.js';
    (document.getElementsByTagName('head')[0] || document.getElementsByTagName('body')[0]).appendChild(apiUmbrella);
  })();
</script>
<noscript>Please enable JavaScript to signup for an <a href="http://api.data.gov/">api.data.gov</a> API key.</noscript>
{% endraw %}
