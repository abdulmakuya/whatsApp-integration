# whatsApp-integration


public void WhatsApp(View view){

        String number = "255672621315";
        //int long = 255672621315;

        String url = "https://api.whatsapp.com/send?phone="+number;
        Intent i = new Intent(Intent.ACTION_VIEW);
        i.setData(Uri.parse(url));
        startActivity(i);
    }
