Terraform Backend Configuration

As we have seen the Terraform backend is configured for a given working directory within a terraform configuration file. 
A configuration can only provide one backend block per working directory. 
You do not need to specify every required argument in the backend configuration. 
Omitting certain arguments may be desirable if some arguments are provided automatically by an automation script running Terraform. 
When some or all of the arguments are omitted, we call this a partial configuration.

 
 1: Terraform backend block
 2: Partial backend configuration via a file
 3: Partial backend configuration via command line
 4: Declare backend configuration via interactive prompt
 5: Specifying multiple partial backend configurations
 6: Backend configuration from multiple locations
 7: Change state backend configuration back to default
