```jobs``` = will show active jobs.  
```bg``` = Resume jobs to the background  
```fg``` = Resume jobs to the foreground  

- How to resume a specific job?
```bg % job_id```  
```fg % job_id```

---

## nice value

Niceness scale goes from -20 to 19. The lower the number more priority that task gets.  

Process priority = nice  
(ex:``` nice -n 5 process```)  

---

## nohup 

If you want our process keep running even after closing your terminal, you can use nohup  

```nohup process &```
```nohup process > /dev/null 2>&1 &```  







