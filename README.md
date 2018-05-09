# CpufreqScripts

These are a few python scripts designed for the purpose of tweaking the CPU frequency scaling settings on a Linux system.

I started writing these because my system kept shutting down when the system was at full performance; I suspect it's a PSU issue, but that's neither here nor there.  What is important is that I wrote these scripts to limit the system from running hard enough to reach the power-off point.

Each of these scripts are designed to apply the same setting to all cores, regardless of how many cores you have.  Additionally, they are designed to check for the appropriate options, so that improper options are not applied to the cpufreq system.

These scripts are written for Python 3.5.
