＃第二个实验

private static final String Instead = MainActivity.class.getSimpleName();

    @Override
    protected void onCreate(Bundle savedInstanceState) {
        super.onCreate(savedInstanceState);
        setContentView(R.layout.activity_main);
        Log.e(Instead,"onCreate");

    }

    @Override
    protected void onRestart() {
        super.onRestart();
        Log.e(Instead,"onRestart");
    }

    @Override
    protected void onStart() {
        super.onStart();
        Log.e(Instead,"onStart");
    }

    @Override
    protected void onResume() {
        super.onResume();
        Log.e(Instead,"onResume");
    }

    @Override
    protected void onStop() {
        super.onStop();
        Log.e(Instead,"onStop");
    }

    protected void onDestroy() {
        super.onDestroy();
        Log.e(Instead,"onDestroy");
    }
<img src="https://github.com/lintao2018/lab2/blob/master/images/1.png" height="100" alt="Screenshot"/>

<img src="https://github.com/lintao2018/lab2/blob/master/images/2.png" height="100" alt="Screenshot"/>
