# *CV*
# **Prokopenko Roman**
### Contacts
* Location: Spain
* Phone: +34 *** ** ** **
* Email: *****************@gmail.com
* GitHub: Roman-PRV
### About Me
Worked as a researcher in the field of economic and mathematical modeling of the economy of Ukraine. Retrained as a software developer. 
I work as a developer in a small company, developing custom applications for its needs. I have hands-on experience in full-stack development, backend in PHP (Laravel), JavaScript frontend and, of course, SQL.
### Skills
* PHP/Laravel
* SQL/MySQL
* HTML, CSS/SASS, JavaScript
* Git, CI/CD, Vagrant, Docker
### Code Example
```
namespace App\Helpers;

use App\Models\User;

class UserHelper
{
    public static function getDrivers(): Collection
    {
        $drivers = User::whereHas('roles', function ($query) {
            $query->where('name', 'driver');
        })->get();
        return $drivers;
    }
...
```
### Experience
* Fullstack Developer: 2 years
* Scientific researcher: 11 years
* University professor: 5 years
### Education
* **University**: Donetsk National University, Ukraine
  - A specialist in Economic Cybernetics 
  - The PHD in Mathematical Economic Modeling
* **Courses**:
  - CEAM, S.L. (Academia GIL), Vitoria-Gazteiz, Spain.  ***Creation and publication of web pages (IFCD0110)***, 2021
  - prometheus.org.ua. ***Basics of programming in Java***, 2017
### Languages
* Ucranian: native
* Russian: native
* Spanish: B1
* English: A2
