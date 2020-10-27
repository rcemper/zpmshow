 ~~~
 This is a coding example working on IRIS 2020.1
 It will not be kept in sync with new versions      
 It is also NOT serviced by InterSystems Support !   
~~~ 

The offer of ZPM is growing daily and the shortnames and  
acronyms of the offer are sometimes hard to understand and   
also hard to type with my lazy fingers.

So I decided to have   
- a listing with the __descriptions__ from repository,   
- splitted in short junks to avoid backscroll,   
- controlled forward / backward scrolling,     
- the option to select my packages by __number__,   
- to install or uninstall with limited typing.  

It runs with __do ^zpmshow__

A snaphot from the screen:
~~~
USER>d ^zpmshow

  1  analyzethis                       1.1.4   -- not github --
  2  apps.rest                         1.0.0   -- no descripition --
  3  bitmap-adoption                   1.0.3  Bitmaps for nonstandard IDs
  4  blocksexplorer                    2.2.1   -- not github --
  5  bondar-nav                        1.0.1   -- no descripition --
  6  cache-fast-json                   1.0.3  produce pretty JSON output for
                                              Cache + Ensemble
  7  classexplorer                     1.21.3  -- no description --
  8  contest-rest-template             1.0.3   -- no description --
  9  csvgen                            1.1.6   -- no description --
 10  declarative-os                    1.0.2   -- no description --
 11  delete-helper                     1.0.1   -- no description --
 12  document-template                 1.0.0   -- not github --
 13  dsw                               2.1.51  -- no description --
 14  ecp-job                           1.0.1  Multi-Line in Terminal Command
 15  excel-light                       1.0.0  Light weight Excel download

action (i[nstall),u[ninstall],n[ext],b[back],q[quit]):i  package number: 6
  6  cache-fast-json                   1.0.3  produce pretty JSON output for
                                              Cache + Ensemble
   OK (y,n): y
zpm install cache-fast-json

[cache-fast-json]       Reload START
[cache-fast-json]       Reload SUCCESS
[cache-fast-json]       Module object refreshed.
[cache-fast-json]       Validate START
[cache-fast-json]       Validate SUCCESS
[cache-fast-json]       Compile START
[cache-fast-json]       Compile SUCCESS
[cache-fast-json]       Activate START
[cache-fast-json]       Configure START
[cache-fast-json]       Configure SUCCESS
[cache-fast-json]       Activate SUCCESS

  1  analyzethis                       1.1.4   -- not github --
  2  apps.rest                         1.0.0   -- no description --
  3  bitmap-adoption                   1.0.3  Bitmaps for nonstandard IDs
  4  blocksexplorer                    2.2.1   -- not github --
  5  bondar-nav                        1.0.1   -- no description --
  6  cache-fast-json                   1.0.3  produce pretty JSON output for
                                              Cache + Ensemble
  7  classexplorer                     1.21.3  -- no description --
  8  contest-rest-template             1.0.3   -- no description --
  9  csvgen                            1.1.6   -- no description --
 10  declarative-os                    1.0.2   -- no description --
 11  delete-helper                     1.0.1   -- no description --

~~~

[Article in DC](https://community.intersystems.com/post/zpmshow-helper-tired-fingers)
   [Video](https://youtu.be/T9D5CiLwu9o) 
