1. Crea una cuenta en SenGrid: `<link>` : <https://sendgrid.com/>

2. Crea un ApiKey:

	**Settings > API Keys > Create API Key**
	
	**Coloca un nombre, concede Full Access y crea la apiKey, asegurate de guardarla ya que solo te la mostrara una vez.**

1. Configura un mail sender:

	**Settings > Sender Authentication > Single Sender Verification > Create New Sender**
	
	**Colocar un email del que SendGrid tendra uso solo para mostrar que viene de este remitente, ya que el envio lo hace desde sus dominios.**
	
	**Te llega un mail para verificar la cuenta.**

1.En el codigo ir a MensajeMailService > configurarYRealizarEnvioMail 

	**Colocar el apiKey y mail sender en la seccion correspondiente del codigo.**
