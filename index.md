<html>
	<header>
		<meta name="viewport" content="width=device-width, initial-scale=1, minimum-scale=1">
	</header>
	<body>
		<div>
			<h1>Hello world !</h1>
		</div>
		
		<div> Messaging here : <br/><br/>
			<script type='text/javascript'>
				function initEmbeddedMessaging() {
					try {
						embeddedservice_bootstrap.settings.language = 'fr'; // For example, enter 'en' or 'en-US'

						embeddedservice_bootstrap.init(
							'00D250000009bBX',
							'STEF_Connect_Web',
							'https://stef--preprod.sandbox.my.site.com/ESWSTEFConnectWeb1694002608297',
							{
								scrt2URL: 'https://stef--preprod.sandbox.my.salesforce-scrt.com'
							}
						);
					} catch (err) {
						console.error('Error loading Embedded Messaging: ', err);
					}
				};
			</script>
			<script type='text/javascript' src='https://stef--preprod.sandbox.my.site.com/ESWSTEFConnectWeb1694002608297/assets/js/bootstrap.min.js' onload='initEmbeddedMessaging()'></script>
			
		</div>
	</body>
</html>
