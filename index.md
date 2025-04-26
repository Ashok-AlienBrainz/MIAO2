<html>
  <body>
  <script type='text/javascript'>
	function initEmbeddedMessaging() {
		try {
			embeddedservice_bootstrap.settings.language = 'en_US'; // For example, enter 'en' or 'en-US'

			embeddedservice_bootstrap.init(
				'00DdM00000MbtSK',
				'web_to_code_3',
				'https://orgfarm-ef8aaf07c5-dev-ed.develop.my.site.com/ESWwebtocode31745664578083',
				{
					scrt2URL: 'https://orgfarm-ef8aaf07c5-dev-ed.develop.my.salesforce-scrt.com'
				}
			);
		} catch (err) {
			console.error('Error loading Embedded Messaging: ', err);
		}
	};
</script>
<script type='text/javascript' src='https://orgfarm-ef8aaf07c5-dev-ed.develop.my.site.com/ESWwebtocode31745664578083/assets/js/bootstrap.min.js' onload='initEmbeddedMessaging()'></script>

  </body>
</html>
