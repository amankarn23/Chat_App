1. make database chatdb in sql
2. then import this file using workbench:- chatdb_users.sql  
3. ensure connectivity port , password at project configuration file.
4. now when the project is completed .
5. test it : a. run server(server started and waiting for the client to join.
             b. to open client connection with login page:

                           1st. D:\Projects\Chat-app\multiuserchatapp\bin : type cmd and open this location in cmd
          
          for server: java com.Aarush.chatapp.network.Server

          for client: java -cp .;"D:\Projects\Chat-app\multiuserchatapp\mysql-connector-j-8.0.32.jar" com.Aarush.chatapp.views.UserScreen  