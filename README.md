#### class heap{
    public static int arr[]=new int[5];
    public static int capacity=5;
    public static int size=0;
   ### public static int left(int i){
        return 2*i+1;
    }
   ### public static int right(int i){
        return 2*i+2;
   }
   ### public static int parent(int i){
        return (i-1)/2;
}
   ### public static void insert(int data) {                ///insert in heap this is  max heap insert implementation 
        
        if(size==0){
            size++;
            arr[size-1]=data;
        }
        else{
         size++;
         arr[size-1]=data;
         int largest=size-1;       
         while(largest>=0 && arr[parent(largest)]<arr[largest]){
            int temp=.arr[.parent(largest)];
            arr[heap1.parent(largest)]=arr[largest];
            arr[largest]=temp;
            largest=parent(largest);
        }}
}}
