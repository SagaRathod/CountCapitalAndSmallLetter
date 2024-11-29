# Count Capital and Small letter in "demo.txt" file in C language using pthread library.
# Description:
created two threads one thread is open that file and read the content and check capital letter
second thread wait for complte the first thread after completed first thread open that file and read the content and count
the small letter.
# function:
    pthread_create()
    pthread_join()
    pthread_exit()
  # System call
    open()
    close()

    
    
# POSIX thread
# refrence: https://www.cs.cmu.edu/afs/cs/academic/class/15492-f07/www/pthreads.html
