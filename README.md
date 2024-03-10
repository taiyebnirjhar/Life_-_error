# Life\_&&\_error

---

#### sh: react-scripts: command not found

###### with npm: <code>npm install react-scripts@latest react@latest react-dom@latest</code>

###### with yarn: <code>yarn add react-scripts@latest react@latest react-dom@latest</code>

---

#### ReferenceError: process is not defined react (using vite)

###### >> If you are using Vite, use import.meta.env instead, process.env is removed. And make sure variables start with VITE\_ in .env file.

--- 

####  Firebase is not defined (firebase deploy),   even after installed globally

###### before deploying add these line in terminal: <code>alias firebase="`npm config get prefix`/bin/firebase"</code>

--- 

#### error: RPC failed; curl 18 transfer closed with outstanding read data remaining

###### It happens on a slow internet connection when trying to clone a decently huge git repository. The most common issue is that the connection closes and the whole clone is canceled. to fix it follow :
<code>$ git clone http://github.com/large-repository --depth 1 
$ cd large-repository 
$ git fetch unshallow
</code>
