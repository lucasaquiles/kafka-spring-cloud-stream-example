
scenarios using kafka and spring cloud stream


seed
$```
while :; do  
 curl -X POST "http://localhost:8080/" -H "accept: */*" -H "Content-Type: application/json" -d "{ \"description\": \"string\", \"lat\":"$ind" , \"lon\": "$ind"}"; 
 let ind=ind+1;
done
```



