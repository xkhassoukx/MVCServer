# MVCServer

# Project README

Restore NuGet Packages from solution file and Update-database in Console.

## 1. Project Built using .NET 7.0 MVC Template. Yes
  
## 2. Authentication Type Set to "Individual Accounts". Yes

## 3. User Registration, Login, and Logout. Yes from template.


Bug/Error in task 4 and 5 when trying to upload image. (Hardcoded images when logged in so its not empty).

## 4. When Logged In, Users Can:
   a) Upload Images with Title and Description
   - **Location:** Image upload functionality is implemented in `ImageController.cs`.

   b) See Images, Titles, and Descriptions from Each Other
   - **Location:** The gallery view is implemented in `Views/Image/Index.cshtml`.

## 5. When NOT Logged In, Users CANNOT:
   a) Upload Images with Title and Description
   - **Location:** Authorization checks are implemented in `ImageController.cs`.

   b) See Images, Titles, and Descriptions from Each Other
   - **Location:** Authorization checks are implemented in `ImageController.cs`.



## 6. Site Must Be Responsive
 `wwwroot/css/site.css` and Views/Shared/_Layout.cshtml/_Layout.cshtml.css has responsive design elements.

## 7. Site Must Use One Ajax Call.
 Simple ajax call added in: `Controllers/HomeController.cs` and in Views/Home/Index.cshtml

## 8. Only Allowed Frameworks: .NET 7.0 MVC. Yes.

## 9. Use README to Point to Code Locations. Yes.

## 10. Allowed Databases: SQLite, MySQL, MS SQL Server, PostgreSQL.

