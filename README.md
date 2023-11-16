# Picasso Rounded and Circle Transformation in Android

Add Picasso in your project
```bash
implementation 'com.squareup.picasso:picasso:2.8'
```

Get the source code of PicassoCircleTransformation and PicassoRoundedCornerTransformation

```java
final Transformation circleTransformation = new PicassoCircleTransformation();
Picasso.get()  
        .load(URL)  
        .transform(circleTransformation)  
        .into(ImageView);


final Transformation roundedTransformation = new PicassoRoundedCornerTransformation(32.0f);
Picasso.get().load(URL)  
        .transform(roundedTransformation)   
        .into(ImageView);
```