# All-Topics-
1. Reverse an array in O(N) 
int arr []={9,8,7,6,5};

 int j= arr.length-1;
 for ( int i=0 ; i< arr.length/2 ;i++,j--){
    int temp =arr[i];
     arr[i]=arr[j];
     arr[j]=temp;

 }
        for (int k=0; k<arr.length;k++){
            System.out.println(arr[k]);
        }
