# Open Source Android Libraries Collection

> Some of the open source Android libraries that I've used in my own development have been found to be good~~( Continuous updating ...)



## 1. UI

### 1.1 Image customization

#### 1.1.1 CircleImageView 

> * **Homepage:**
>
>   https://github.com/hdodenhof/CircleImageView
>
> <br/>
>
> * **Use(app/build.gradle)：**
>
>   ```groovy
>   dependencies {
>   ...
>   implementation 'de.hdodenhof:circleimageview:2.2.0'
>   }
>   ```
>
> <br/>
>
> * **Description:**
>
>   To round an image, often used to customize a user's avatar.

<br/>

### 1.2 Menu

#### 1.2.1 BoomMenu

> * **Homepage:**
>
>   https://github.com/Nightonke/BoomMenu
>
> <br/>
>
> * **Use(app/build.gradle)：**
>
>   ```groovy
>   dependencies {
>     compile 'com.nightonke:boommenu:2.1.1'
>   }
>   ```
>
> <br/>





<br/>

***

## 2. network


<br/>

***

## 

## 3. Image Load

### 3.1 Glide
> * **Homepage：**
>
>   https://github.com/bumptech/glide
>
> <br/>
>
> * **Use(app/build.gradle)：**
>
>   ```groovy
>   repositories {
>     mavenCentral()
>     google()
>   }
>
>   dependencies {
>     implementation 'com.github.bumptech.glide:glide:4.8.0'
>     annotationProcessor 'com.github.bumptech.glide:compiler:4.8.0'
>   }
>   ```
>
>

<br/>


<br/>
***



## 4. Image Processing
### 4.1 Cropper

> * **Homepage:**
>
>   https://github.com/edmodo/cropper
>
> <br/>
>
> * **Use(app/build.gradle)：**
>
>   ```groovy
>   repositories {
>       mavenCentral()
>   }
>
>   dependencies {
>     compile 'com.edmodo:cropper:1.0.1'
>   }
>
>   ```
>   <br/>
>
> * **Description:**
>
>   This is a rather old clipping library, and UI definition is not high. The only advantage is that it is stable, efficient, and the cropped image returns Bitmap format, which makes subsequent operations more convenient.
>
>