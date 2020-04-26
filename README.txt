0. Please write down the full names and netids of all your team members.

	Oren Mendelow - om144
	Kevin Nehrbauer - kcn28

1. Briefly discuss how you implemented each functionality: setting up interfaces, setting up default routes, and setting up per-destination routes.

	setting up interfaces was done using "<hostname> ip addr add <ip-address> dev <hostname>-<eth0>" and "<routename> ip addr add <ip-address> dev <routename>-et<hostname>"
	setting up default routes was done using "<hostname> ip route add default dev <hostname>-eth0
	setting up per-destination routes was done using "<routename> ip route add <ip-address>/32 dev <routename>-et<hostname>

2. Are there known issues or functions that aren't working currently in your attached code? If so, explain.

	There are no known issues or functions that aren't working currently in my attached code.

3. What problems did you face developing code for this project?

	In testing, we couldn't get the traceroute command to work. Ping worked, however.

4. What did you learn by working on this project?

	By working on this project we learned how to set up our own IP network which was very cool!