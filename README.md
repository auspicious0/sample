# sample

## oracle 환경 변수
# .bash_profile

# Get the aliases and functions
if [ -f ~/.bashrc ]; then
        . ~/.bashrc
fi

# User specific environment and startup programs

export TMP=/tmp
export TMPDIR=/tmp
export ORACLE_BASE=/home/xecuredb/app/xecuredb
export ORACLE_SID=orcl
export ORACLE_HOME=/home/xecuredb/app/xecuredb/product/12.1.0/dbhome_2
export ORACLE_HOME_LISTNER=$ORACLE_HOME/bin/lsnrctl
export LD_LIBRARY_PATH=/home/xecuredb/z_package/server/lib:/home/xecuredb/z_package/api/c/lib:$ORACLE_HOME/lib:/usr/lib
export PATH=$ORACLE_HOME/bin:$PATH

