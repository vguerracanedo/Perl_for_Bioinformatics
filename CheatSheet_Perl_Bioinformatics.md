## Cheat Sheet for Perl


# [Perl Functions by Category](https://perldoc.perl.org/functions)


| Functions for SCALARs or strings  | Description |
| --- | --- |
| [chomp](https://perldoc.perl.org/functions/chomp)| This safer version of chop removes any trailing string that corresponds to the current value of $/ . It returns the total number of characters removed from all its arguments. 
| chop |   |
| chr |   |
| crypt |   |
| fc |   |
| hex |   |
| index |   |
| lc |   |
| lcfirst |   |
| length |   |
| oct |   |
| ord |   |
| pack |   |
| q// |   |
| qq// |   |
| reverse |   |
| rindex |   |
| sprintf |   |
| substr |   |
| tr/// |   |
| uc |   |
| ucfirst |   |
| y/// |   |

| Regular expressions and pattern matching  | Description |
| --- | --- |
|m// |   |
| pos |   |
| qr// |   |
| quotemeta |   |
| s/// |   |
| split |   |
| study |   |

|Numeric functions  | Description |
| --- | --- |
abs |   |
| atan2 |   |
| cos |   |
| exp |   |
| hex |   |
| int |   |
| log |   |
| oct |   |
| rand |   |
| sin |   |
| sqrt |   |
| srand|   |

|Functions for real @ARRAYs  | Description |
| --- | --- |
each |   |
| keys |   |
| pop |   |
| push |   |
| shift |   |
| splice |   |
| unshift, |   |
| values |   |

|Functions for list data  | Description |
| --- | --- |
grep |   |
| join |   |
| map, |   |
| qw// |   |
| reverse |   |
| sort |   |
| unpack |   |

|Functions for real %HASHes  | Description |
| --- | --- |
delete |   |
| each |   |
| exists |   |
| keys |   |
| values |   |

|Input and output functions  | Description |
| --- | --- |
| binmode |   |
| close |   |
| closedir |   |
| dbmclose |   |
| dbmopen |   |
| die, eof |   |
| fileno |   |
| flock |   |
| ormat |   |
| getc |   |
| print |   |
| printf |   |
| ead |   |
| readdir |   |
| readline |   |
| rewinddir |   |
| say |   |
| seek |   |
| seekdir |   |
| select |   |
| syscall |   |
| sysread |   |
| sysseek |   |
| syswrite |   |
| tell |   |
| telldir |   |
| truncate |   |
| warn |   |
| write |   |

|Functions for fixed-length data or records  | Description |
| --- | --- |
| pack |   |
| read |   |
| syscall |   |
| sysread |   |
| sysseek |   |
| syswrite |   |
| unpack |   |
| vec |   |

|Functions for filehandles, files, or directories  | Description |
| --- | --- |
| -X |   |
| chdir |   |
| chmod |   |
| chown |   |
| chroot |   |
| fcntl |   |
| glob |   |
| ioctl |   |
| link |   |
| lstat |   |
| mkdir |   |
| open |   |
| opendir |   |
| readlink |   |
| rename |   |
| rmdir |   |
| select |   |
| stat |   |
| symlink |   |
| sysopen |   |
| umask |   |
| unlink |   |
| utime |   |

|Keywords related to the control flow of your Perl program  | Description |
| --- | --- |
| break |   |
| caller |   |
| continue |   |
| die |   |
| do |   |
| dump |   |
| eval |   |
| evalbytes |   |
| exit |   |
| __FILE__ |   |
| goto |   |
| last |   |
| __LINE__ |   |
| next |   |
| __PACKAGE__ |   |
| redo |   |
| return |   |
| sub |   |
| __SUB__ |   |
| wantarray |   |

|Keywords related to scoping  | Description |
| --- | --- |
| caller |   |
| import |   |
| local |   |
| my |   |
| our |   |
| package |   |
| state |   |
| use |   |

|Miscellaneous functions  | Description |
| --- | --- |
| defined |   |
| formline |   |
| lock |   |
| prototype |   |
| reset |   |
| scalar |   |
| undef |   |

|Functions for processes and process groups  | Description |
| --- | --- |
| alarm |   |
| exec |   |
| fork |   |
| getpgrp |   |
| getppid |   |
| getpriority |   |
| kill |   |
| pipe |   |
| qx// |   |
| readpipe |   |
| setpgrp |   |
| setpriority |   |
| sleep |   |
| system |   |
| times |   |
| wait |   |
| waitpid |   |

|Keywords related to Perl modules  | Description |
| --- | --- |
| do |   |
| import |   |
| no |   |
| package |   |
| require |   |
| use |   |

|Keywords related to classes and object-orientation  | Description |
| --- | --- |
| bless |   |
| dbmclose |   |
| dbmopen |   |
| package |   |
| ref |   |
| tie |   |
| tied |   |
| untie |   |
| use |   |

|Low-level socket functions  | Description |
| --- | --- |
| accept |   |
| bind |   |
| connect |   |
| getpeername |   |
| getsockname |   |
| getsockopt |   |
| listen |   |
| recv |   |
| send |   |
| setsockopt |   |
| shutdown |   |
| socket |   |
| ocketpair |   |

|System V interprocess communication functions  | Description |
| --- | --- |
| msgctl |   |
| msgget |   |
| msgrcv |   |
| msgsnd |   |
| semctl |   |
| semget |   |
| semop |   |
| shmctl |   |
| shmget |   |
| shmread |   |
| shmwrite |    |

|Fetching user and group info  | Description |
| --- | --- |
| endgrent |   |
| endhostent |   |
| endnetent |   |
| endpwent |   |
| getgrent |   |
| getgrgid |   |
| getgrnam |   |
| getlogin |   |
| getpwent |   |
| getpwnam |   |
| getpwuid |   |
| setgrent |   |
| setpwent |   |

|Fetching network info  | Description |
| --- | --- |
| endprotoent |   |
| endservent |   |
| gethostbyaddr |   |
| gethostbyname |   |
| gethostent |   |
| getnetbyaddr |   |
| getnetbyname |   |
| getnetent |   |
| getprotobyname |   |
| getprotobynumber |   |
| getprotoent |   |
| getservbyname |   |
| getservbyport |   |
| getservent |   |
| sethostent |   |
| setnetent |   |
| setprotoent |   |
| setservent |   |

|Time-related functions  | Description |
| --- | --- |
| gmtime |   |
| localtime |   |
| time |   |
| times |   |

|Non-function keywords  | Description |
| --- | --- |
| and |   |
| AUTOLOAD |   |
| BEGIN |   |
| HECK |   |
| cmp |   |
| CORE |   |
| __DATA__ |   |
| default |   |
| DESTROY |   |
| else |   |
| elseif |   |
| elsif |   |
| END |   |
| __END__ |   |
| eq, |   |
| for |   |
| foreach |   |
| ge |   |
| given |   |
| gt |   |
| if |   |
| INIT |   |
| le |   |
| lt |   |
| ne |   |
| not |   |
| or |   |
| UNITCHECK |   |
| unless |   |
| until |   |
| when |   |
| while |   |
| x |   |
| xor |   |


# [Perl operators and precedence](https://perldoc.perl.org/perlop)
# [Perl variables](https://perldoc.perl.org/variables)
# [Perl modules](https://perldoc.perl.org/modules)
# [Perl utilities](https://perldoc.perl.org/perlutil)


Functions acquired from https://perldoc.perl.org/
