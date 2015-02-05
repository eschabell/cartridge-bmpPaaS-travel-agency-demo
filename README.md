Cartridge for bpmPaaS with Travel Agency Demo
=============================================
This cartridge provides the **_Red Hat JBoss BPM Suite_** for easy deployment to OpenShift based bpmPaaS with pre-loaded Travel Agency Demo.


Install with one click in xPaaS (bpmPaaS)
-----------------------------------------
After clicking button, ensure `Gear` size is set to `medium`:

[![Click to install OpenShift](http://launch-shifter.rhcloud.com/launch/light/Install bpmPaaS.svg)](https://openshift.redhat.com/app/console/application_type/custom?&cartridges[]=https://raw.githubusercontent.com/jbossdemocentral/cartridge-bpmPaaS-travel-agency-demo/master/metadata/manifest.yml&name=bpmpaasgenericloan&gear_profile=medium&initial_git_url=)

Once installed you can use the JBoss BPM Suite logins: 

   * u:erics   p: bpmsuite  (admin)

   * u: alan   p: bpmsuite  (analyst)

   * u: daniel p: bpmsuite (developer)

   * u: ursla  p: bpmsuite (user)

   * u: mary   p: bpmsuite (manager)


Important Note
--------------
You need the ability to setup MEDIUM gears, which is freely available if you [upgrade your account to Bronze here] (https://www.openshift.com/products/pricing). 


Manual setup on OpenShift
-------------------------
Or if you want to use the [rhc command line](https://www.openshift.com/developers/rhc-client-tools-install) type:

    rhc app create -g medium <APP NAME> https://raw.githubusercontent.com/jbossdemocentral/cartridge-bpmPaaS-travel-agency-demo/master/metadata/manifest.yml

For more information on the [JBoss BPM Travel Agency Demo see here] (https://github.com/jbossdemocentral/bpms-travel-agency-demo).

Supporting Articles
-------------------
[Rocket into the Clouds with OpenShift bpmPaaS Quickstarts](http://www.schabell.org/2014/10/red-hat-openshift-bpmpaas-automated-demo-projects-updated.html)

[Red Hat OpenShift bpmPaaS - JBoss BPM Travel Agency now flying you to the Cloud] ()


Released versions
-----------------
See the tagged releases for the following versions of the product:

- v1.0 - bpmPaaS on OpenShift cartridge, JBoss BPM Suite 6.0.2 and JBoss BPM Travel Agency demo installed.


![Digital Sign Annoucement](https://github.com/jbossdemocentral/bpms-travel-agency-demo/blob/master/docs/demo-images/announce-sign.jpg?raw=true)

