# Oche
Simple framework for making webpages which leverage a multitude of different services. This is essential for the Plane-Oche-Nextcloud-Docker (POND) Stack
#Status
A deployment plan, NOT A SOFTWARE PROJECT.
# Setup
Automated setup files will be added as we complete deployments to log more specific details on how to make these deployments come to life.
# Core Process
Oche starts by hosting CyberPanel, an open source website control panel which integrates WordPress and Docker.

Then we setup as follows:

    Do we need email?
        If yes we then setup email in CyberPanel
    Do we need a website?
        If yes then we setup a WordPress website through CyberPanel
        We setup Jetpack using the email hosted on CyberPanel
    Do we need to deploy any docker containers?
        If yes then we deploy docker containers 
    Are there any other accounts needed?
        If so then we set those up using our email.
    Link everything together into our website solution.

After that we are done, the plan has been completed and any accounts or other components can be integrated well into a single system, quickly. 
