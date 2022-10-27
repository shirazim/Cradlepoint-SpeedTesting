This script runs speed tests for every Cradlepoint device at our company. This speed test audit used to be done manually once per month and would take hours between multiple people.

Now, with the help of this script that utilizes the NetCloud API, we can run speed tests daily in a matter of minutes.

Also, I should note that this script uses 2 BASH scripts that actually initiate the POST API calls. The BASH scripts contain all of the Cradlepoint router IDs and it is much neater to have them segmented into their own files instead of having them all crammed into 1 giant powershell script.
