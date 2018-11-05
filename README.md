# Open Source Android Libraries Collection

> Some of the open source Android libraries that I've used in my own development have been found to be good~~( Continuous updating ...)






## 1. UI

### 1.1 Button

#### 1.1.1 android-circlebutton

> * **Homepage:**
>
>   https://github.com/markushi/android-circlebutton
>
> <br/>
>
> * **Use(app/build.gradle):**
>
>   ```groovy
>   repositories {
>       mavenCentral()
>       mavenLocal()
>   }
>
>   ...
>
>   dependencies {
>       implementation 'com.github.markushi:circlebutton:1.1'
>   }
>   ```

<br/>


### 1.2 Image Customization

#### 1.2.1 CircleImageView 

> * **Homepage:**
>
>   https://github.com/hdodenhof/CircleImageView
>
> <br/>
>
> * **Use(app/build.gradle):**
>
>   ```groovy
>   dependencies {
>   	implementation 'de.hdodenhof:circleimageview:2.2.0'
>   }
>   ```
>
> <br/>
>
> * **Description:**
>
>   To round an image, often used to customize a user's avatar.

<br/>

### 1.3 Menu

#### 1.3.1 BoomMenu

> * **Homepage:**
>
>   https://github.com/Nightonke/BoomMenu
>
> <br/>
>
> * **Use(app/build.gradle):**
>
>   ```groovy
>   dependencies {
>     implementation 'com.nightonke:boommenu:2.1.1'
>   }
>   ```
>

<br/>

### 1.4 Bottom Navigation Bar

#### 1.4.1 BottomNavigation

> * **Homepage:**
>
>   https://github.com/Ashok-Varma/BottomNavigation
>
> <br/>
>
> * **Use(app/build.gradle):**
>
>   ```groovy
>   dependencies {
>     implementation 'com.ashokvarma.android:bottom-navigation-bar:2.1.0'
>   }
>   ```

<br/>

### 1.5 Immersion Status Bar

#### 1.5.1 ImmersionBar

> * **Homepage:**
>
>   https://github.com/gyf-dev/ImmersionBar
>
> <br/>
>
> * **Use(app/build.gradle):**
>
>   ```groovy
>   dependencies {
>     implementation 'com.gyf.immersionbar:immersionbar:2.3.2-beta01'
>   }
>   ```

<br/>

### 1.6 Pull Up Load & Pull Down Refresh

#### 1.6.1 SmartRefreshLayout

> * **Homepage:**
>
>   https://github.com/scwang90/SmartRefreshLayout
>
> <br/>
>
> * **Use(app/build.gradle):**'
>
>   ```groovy
>   dependencies {
>   	implementation 'com.scwang.smartrefresh:SmartRefreshLayout:1.1.0-alpha-14'
>   	implementation 'com.scwang.smartrefresh:SmartRefreshHeader:1.1.0-alpha-14'//If you use the special Header
>   	implementation 'com.android.support:appcompat-v7:25.3.1'
>   }
>   ```
>
>   ​







<br/>


<br/>

***

## 2. Network

### 2.1 retrofit

> * **Homepage:**
>
>   https://github.com/square/retrofit
>
> <br/>
>
> * **Use(app/build.gradle):**
>
>   ```groovy
>   dependencies {
>     implementation 'com.squareup.retrofit2:retrofit:2.4.0'
>   }
>   ```
>
>   ​

<br/>



<br/>

<br/>

***


## 3. Image Load

### 3.1 glide
> * **Homepage:**
>
>   https://github.com/bumptech/glide
>
> <br/>
>
> * **Use(app/build.gradle):**
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
### 4.1 cropper

> * **Homepage:**
>
>   https://github.com/edmodo/cropper
>
> <br/>
>
> * **Use(app/build.gradle):**
>
>   ```groovy
>   repositories {
>       mavenCentral()
>   }
>
>   dependencies {
>     implementation 'com.edmodo:cropper:1.0.1'
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

<br/>

<br/>

***



## 5. Dependency Injection 

### 5.1 butterknife

> * **Homepage:**
>
>   https://github.com/JakeWharton/butterknife
>
> <br/>
>
> * **Use(app/build.gradle):**
>
>   ```groovy
>   dependencies {
>     implementation 'com.jakewharton:butterknife:9.0.0-rc1'
>     annotationProcessor 'com.jakewharton:butterknife-compiler:9.0.0-rc1'
>   }
>   ```
>
> <br/>
>
> * **Description:**
>
>   Field and method binding for Android views which uses annotation processing to generate boilerplate code for you.
>
>   ​



<br/>

<br/>

***

