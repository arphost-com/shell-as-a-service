# shell-as-a-service
Shell commands run as a service in WHMCS

Shell as a Service Version 1 by ARPHost

1. Extact shellasaservice-1.0.zip to shellaservice.

Upload shellasaservice to your addons folder under modules in your whmcs directory.

Login to WHMCS and go to Syetm Settings -> Addon Modules and Active Shell as a Service.

Next Set Access controls, enter your license  and save changes.

Now you can setup a product or product addon with a shell script. Go to Product/Services. Add a new Product Group or use an existing. 

Create a new product. 

Go to the Modules settings tab of the product.

Select Shellasaservice from the Module Name dropdown. In createbash put the path to your shell script including the script. 

If you would like it to run after payment tick	Automatically setup the product as soon as the first payment is received

