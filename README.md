## ClassNotes | Online Text Editor

ClassNotes is a very simple text editor built with Django. It allows you to create, edit, and save plain text or PDF files online. With many basic tools, easily configurable, 100% open-source and no credits required.

### Getting Started

To get started with ClassNotes, follow these instructions:

- Clone the repository to your local machine:
  - https://git-scm.com/docs/git-clone
  - `git clone https://github.com/nom-utilisateur/nom-repo.git`
- Open a terminal and navigate to the root directory of the project.
- Install Django and its dependencie with: `pip install -r requirements.txt`
- Execute the migrations by running the following command: `python3 manage.py migrate`
- Navigate to the project directory and run the command `python3 manage.py runserver` to start the local server.
- Open your browser and go to http://127.0.0.1:8000/ to view the website.

### Usage

ClassNotes is a web-based text editor that lets you create and edit plain text or PDF files online. It features a simple toolbar with basic formatting options, including font size, color, and alignment. You can also save your files to your local machine as plain text or PDF files.

### Contributions

Contributions are welcome! If you would like to contribute to this project, please fork this repository and create a pull request with your changes.

### HTML Template

The ClassNotes HTML template includes:
- A basic structure with a files explorer (just in display, file management is not implemented)
- A text section with a toolbar
- A content area.

You can customize the template to fit your needs.

### License

ClassNotes is licensed under the MIT License. See the LICENSE file or right here:
```
MIT License

Permission  is hereby  granted, free of charge, to
any person  obtaining a  copy of this software and
associated documentation files  (the  "Software"),
to  deal in  the   Software   without restriction,
including  without  limitation  the rights to use,
copy,   modify,   merge,    publish,   distribute,
sublicense, and/or  sell  copies of  the Software,
and  to  permit persons  to  whom the  Software is
furnished  to do  so,  subject  to   the following
conditions:

The above  copyright   notice and  this permission
notice   shall  be included    in  all   copies or
substantial    portions     of    the    Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY
OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT
LIMITED  TO  THE  WARRANTIES  OF  MERCHANTABILITY,
FITNESS    FOR    A     PARTICULAR   PURPOSE   AND
NONINFRINGEMENT.  IN NO EVENT SHALL THE AUTHORS OR
COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES
OR  OTHER  LIABILITY, WHETHER    IN  AN  ACTION OF
CONTRACT, TORT OR OTHERWISE, ARISING FROM,  OUT OF
OR IN CONNECTION WITH  THE SOFTWARE OR THE  USE OR
OTHER DEALINGS IN THE SOFTWARE.
```
