# don't forget to switch user to unrealircd
```su - unrealircd```

# general info

* Directory layout:
 * Base directory: /home/unrealircd/unrealircd
  * Configuration files: /home/unrealircd/unrealircd/conf
  * Log files: /home/unrealircd/unrealircd/logs
  * Modules: /home/unrealircd/unrealircd/modules
* To start/stop UnrealIRCd run: /home/unrealircd/unrealircd/unrealircd"

* Consult the documentation online at:
  * https://www.unrealircd.org/docs/
  * https://www.unrealircd.org/docs/FAQ

* To ensure UnrealIRCd automatically starts on system startup:
  * Install a cron job: https://www.unrealircd.org/docs/Cron_job
  * Or, use systemd: https://www.unrealircd.org/docs/Using_systemd_with_UnrealIRCd

# setting up NPM for handling TLS (not ideal)
use streams for port 6697, fwd to internal server port 6667

# setting up for internal TLS/SSL w/ let's encrypt
https://www.unrealircd.org/docs/Setting_up_certbot_for_use_with_UnrealIRCd
https://www.unrealircd.org/docs/Using_Let's_Encrypt_with_UnrealIRCd

# anope install
reference - https://wiki.anope.org/index.php/2.0/Installation
reference - https://www.unrealircd.org/docs/Linking_UnrealIRCd_with_anope
