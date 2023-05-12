mam amcha sample question ku answer iruku except python connectivity

code for python connectivity:

import cx_Oracle
con = cx_Oracle.connect("system/rec@XE")
cur = con.cursor()
cur.execute("select * from mark_details")
print(cur.fetchall())
con.close()
