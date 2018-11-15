# Fresco.initialize
Fresco.initialize(this);   Whenever app is open at that time this line generate exception in android



protected void onCreate(Bundle savedInstanceState) {
        super.onCreate(savedInstanceState);
        try {
            Fresco.initialize(this);   this line generate exeception 
            
            
        } catch (Exception e) {
            e.printStackTrace();
        }
    }
