# JavaRandomNumberCreator
    public static int randomNumberGenerate(int low, int high){
        Random r = new Random();
        int result = r.nextInt(high-low) + low;
        return result;
    }
