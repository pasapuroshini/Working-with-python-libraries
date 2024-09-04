# Working with pickle files

```
# Write to pickle file
import pickle
ordering ={"First":1,"Second":2,"Third":3}
pickle.dump(ordering,open("new.pk1","wb"))
# write binary 
```

```
# Read from pickle file
reading_pickle =pickle.load(open("new.pk1","rb"))
# rb read binary
```
<img width="338" alt="Screenshot 2024-09-04 at 10 02 25 AM" src="https://github.com/user-attachments/assets/7da2f449-0095-409f-ad48-a15e81707eab">
