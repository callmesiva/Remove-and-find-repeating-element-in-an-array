# Remove-and-find-repeating-element-in-an-array



       int arr[] = {2,3,4,5,2};
       for(int i=0; i<arr.length; i++)
       {
         
         int count=0;
         for(int j=i; j<arr.length; j++)   
         {
           if(arr[i]==arr[j])
           {
             count++;
           }
         }
         
         if(count==1)
         {
           System.out.println(arr[i]);// if j=i & count ==1 print 3 4 5 2,,, if j=i &count==2 print 2,,, if j=0 & count ==1 print 3 4 5,,, 
         }
         
         
       }
