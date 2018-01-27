# hana_trial
Hana Cloud Platform 20180127

C:\Users\gdcla>cf api https://api.cf.eu10.hana.ondemand.com
Setting api endpoint to https://api.cf.eu10.hana.ondemand.com...
OK

api endpoint:   https://api.cf.eu10.hana.ondemand.com
api version:    2.100.0
Not logged in. Use 'cf login' to log in.

C:\Users\gdcla>cf login
API endpoint: https://api.cf.eu10.hana.ondemand.com

Email> gareth.clarke@covarius.com

Password>
Authenticating...
OK

Targeted org P1942684425trial_trial

Targeted space dev



API endpoint:   https://api.cf.eu10.hana.ondemand.com (API version: 2.100.0)
User:           gareth.clarke@covarius.com
Org:            P1942684425trial_trial
Space:          dev

C:\Users\gdcla>cf buildpacks
Getting buildpacks...

buildpack               position   enabled   locked   filename
staticfile_buildpack    1          true      false    staticfile-buildpack-v1.4.20.zip
java_buildpack          2          true      false    java-buildpack-v4.7.zip
ruby_buildpack          3          true      false    ruby-buildpack-v1.7.7.zip
nodejs_buildpack        4          true      false    nodejs-buildpack-v1.6.12.zip
go_buildpack            5          true      false    go-buildpack-v1.8.14.zip
python_buildpack        6          true      false    python-buildpack-v1.6.3.zip
php_buildpack           7          true      false    php-buildpack-v4.3.44.zip
binary_buildpack        8          true      false    binary-buildpack-v1.0.15.zip
dotnet_core_buildpack   9          true      false    dotnet-core-buildpack-v1.0.32.zip
sap_java_buildpack      10         true      false    sap_java_buildpack-v1.6.15.zip

C:\Users\gdcla>cf marketplace
Getting services from marketplace in org P1942684425trial_trial / space dev as gareth.clarke@covarius.com...
OK

service            plans                                  description
api-management     lite                                   Expose your data and processes as APIs for omni-channel consumption and manage the lifecycle of those APIs.
application-logs   lite                                   Stream logs of bound applications to central application logging stack
autoscaler         lite                                   Automatically increase or decrease the number of application instances based on a policy you define.
connectivity       lite                                   Establishes a secure and reliable connectivity between cloud applications and on-premise systems.
destination        lite                                   [BETA] Provides a secure and reliable access to destination configurations
hanatrial          hdi-shared                             SAP HANA trial database
html5-apps-repo    app-host, app-runtime                  [BETA] Enables storage of HTML5 applications and provides runtime environment for HTML5 applications.
jobscheduler       lite                                   [Beta] Allows you to define and manage your jobs that run on one-time or recurring schedules
mongodb            v3.0-dev                               Store JSON-like documents in a document-oriented database.
portal-services    site-host*, site-content*, site-app*   Easily create SAP Fiori launchpad business sites for employees, customers and partners.
postgresql         v9.4-dev, v9.6-dev                     Relational database with an object-oriented model.
rabbitmq           v3.6-dev                               RabbitMQ messaging
xsuaa              application                            Manage application authorizations and trust to identity providers.

* These service plans have an associated cost. Creating a service instance will incur this cost.

TIP:  Use 'cf marketplace -s SERVICE' to view descriptions of individual plans of a given service.

C:\Users\gdcla>
