This script runs speed tests for every Cradlepoint device at our company. This speed test audit used to be done manually once per month and would take hours between multiple people.

Now, with the help of this script that utilizes the NetCloud API, we can run speed tests daily in a matter of minutes.

Also, I should note that this script uses 2 BASH scripts that actually initiate the POST API calls. The BASH scripts contain all of the Cradlepoint router IDs and it is much neater to have them segmented into their own files instead of having them all crammed into 1 giant powershell script.

Update 5/22/23-
I migrated away from this process and now use a speed testing SDK that was provided by cradlepoint. The SDK is a much better solution for running these speed tests.

Update 8/12/2023-
The Speed Test SDK broke after we upgraded our Cradlepoints to the latest NCOS. Was unable to find a fix for it so I re-wrote this script and am using the API to run speed tests again. This script no longer relies on 2 Bash scripts. This script is exactly how you should run speed tests via the API
