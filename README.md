# netdata-windows-dashboard
A simple web dashboard to seperate the Windows Monitoring of Netdata from all other monitoring, styled similarly to the standard dashboard.

To edit it to work with your own server, under all ```div```, replace the value of ```data-netdata``` to reflect your Netdata server.<br>
You should be able to find and replace ```hp``` with what your Windows Server is called in Netdata.<br>
Note that for graphs under ```Network```, you will likely need to replace the whole value as it identifies it by the name of your network interface.

Demo at https://hpdash.mattle.uk
