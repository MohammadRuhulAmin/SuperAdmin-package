# SuperAdmin-package

1)#Step-1)composer require teambravo/superadmin_pkg

2)#Step-2)\TeamBravo\SuperAdmin\SuperAdminServiceProvider::class, inside config/app.php , provider section

3)#Step-3)php artisan vendor:publish --provider="TeamBravo\SuperAdmin\SuperAdminServiceProvider" --tag="assets"

4)#Step-4)to save image create public/images

5)#Step-5)to save cv  create public/cvs

6)#Step-6)to save appoinment_letter create public/appoinment_letters

7)#Step-7)to save document file create public/documents

8)#Step-8)to save project documents file create public/project_documents

9)#Step-9)delete user migration file from main project

10)#Step-10) set database inside .env file

11)#Step-11)run : php artisan migrate

12)#Step-12) Hit localhost:8000/super_admin/

