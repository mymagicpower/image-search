## Web Site：
http://aias.top/


### Image Search by Image
- Includes two projects to meet the needs of different scenarios

![Screenshot](https://aias-home.oss-cn-beijing.aliyuncs.com/products/image_search/images/arc.png)

### 1. Image Search without Vector Engine - simple_image_search
#### 1.1 Main Features
- Supports data volume up to 1 million
- Allows for data insertion, deletion, search, and update at any time

#### 1.2 Feature Introduction
- Image Search: Upload images for search
- Data Management: Provides image compression package (zip format) upload, image feature extraction


### 2. Image Search with Vector Engine - image_search
#### 2.1 Main Features
- Utilizes feature vector similarity search at the core
- Millisecond-level search on a single server for billions of data entries
- Near real-time search, supports distributed deployment
- Allows for insertion, deletion, search, and update of data at any time
- Supports online user management and server performance monitoring, with the ability to restrict single-user logins

#### 2.2 Feature Introduction
- Search Management: Provides image search, and image information viewing
- Storage Management: Provides image compression package (zip format) upload,  image feature extraction
- User Management: Offers user-related configurations, default password is 123456 after adding a new user
- Role Management: Assigns permissions and menus, can set role data permissions based on departments
- Menu Management: Implements dynamic menu routing, configurable backend, supports multi-level menus
- Department Management: Configurable system organizational structure, displayed as a tree table
- Position Management: Configures positions for various departments
- Dictionary Management: Maintains common fixed data, such as status, gender, etc.
- System Logs: Records user operation logs and exception logs for easy troubleshooting by developers
- SQL Monitoring: Uses Druid to monitor database access performance, default username is admin, password is 123456
- Scheduled Tasks: Integrates Quartz for scheduled tasks, includes task logs for clear task execution status
- Service Monitoring: Monitors server load conditions


#### 1.  Front-end Search Page Feature Introduction
- Home Page
1). Supports image drag and drop, paste search.
2).  Adapts to PC, Android, iOS browsers.
<div align="center">
<img src="https://aias-home.oss-cn-beijing.aliyuncs.com/products/image_search/images/simple_1.png"  width = "600"/>
</div> 

- Image List Page
1). Supports image drag and drop, paste search.
2).  Image layout is self-adaptive.
3). Image list auto-load when scrolling down.
<div align="center">
<img src="https://aias-home.oss-cn-beijing.aliyuncs.com/products/image_search/images/simple_2.png"  width = "600"/>
</div> 

#### 2.  Back-end Management Feature Introduction
- Login
<div align="center">
<img src="https://aias-home.oss-cn-beijing.aliyuncs.com/products/image_search/images/login.png"  width = "600"/>
</div> 

- User Management
<div align="center">
<img src="https://aias-home.oss-cn-beijing.aliyuncs.com/products/image_search/images/user.png"  width = "600"/>
</div> 

- Role Management
<div align="center">
<img src="https://aias-home.oss-cn-beijing.aliyuncs.com/products/image_search/images/role.png"  width = "600"/>
</div> 

- Operations Management
<div align="center">
<img src="https://aias-home.oss-cn-beijing.aliyuncs.com/products/image_search/images/ops.png"  width = "600"/>
</div> 

- Image Upload 
1). Supports zip compression package upload.
2). Supports server-side folder upload (for uploading a large number of images, such as hundreds of thousands of images into the library). 
3). Supports client-side folder upload.
<div align="center">
<img src="https://aias-home.oss-cn-beijing.aliyuncs.com/products/image_search/images/storage.png"  width = "600"/>
</div> 

- Image Search
<div align="center">
<img src="https://aias-home.oss-cn-beijing.aliyuncs.com/products/image_search/images/search.png"  width = "600"/>
</div> 
