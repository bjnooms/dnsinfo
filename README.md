# dnsinfo

                     **************************************
                     ************** DNS INFO **************
                     **************************************
                              Created by: bnewman

  Gathers registration, nameserver, and DNS information for a specific domain.

                             Script Syntax & Usage:

                            bash dnsinfo.sh $DOMAIN

  where $DOMAIN = a registered domain with information in the whois database.

       If the domain is not registered, the script will exit with error:
                          “Error: Unregistered Domain”

If multiple domains are passed as arguments to the script, it will exit with error:
                          “Error: Too Many Arguments”

If no domains are passed as arguments to the script, it will exit with error:
                          “Error: No Argument Passed”

If no whois server can be found for the specific TLD passed to the script, it will exit with error:
                          “Error: No whois Server Found”

      Email me at ben@bnewman.fail with any feedback and/or requests.


