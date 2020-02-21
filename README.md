# wildfly docker

This project is an adapted version of base wildfly image. It will add the following points to the original image
 * Provide beta versions too (If you are missing one please contact me)
 * Also expose and bind the management port for cli and web console on port 9990
 * Create a default user for cli and web console with credentials admin:Admin123!
 * Provide environment variables you can use in you own docker files based on this image
   * CONF_DIR - configuration directory (/opt/jboss/wildfly/standalone/configuration); You can place customized standalone.xml
     in here for example
   * DEPLOYMENT_DIR - deployment directory (/opt/jboss/wildfly/standalone/deployments); You can place your war file in here
     for example

If you find problems originating on this image please send me an issue or even better a pull request.
