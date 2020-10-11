Rucha Dandekar

1. Create a hyperlink with in a document. Sample link: www.google.com.
               <a href="www.google.com">Google Link</a>
2. How to create a hyperlink to take you to another part of the same HTML document?

            <a href="#Coffee...">This is a link to text within the same page</a>
       <!--put a #, when you want to link to content within the same page-->
3. HTML5: How to specify the number of columns a cell should span?
<table width:40% border="1" bgcolor=#90C2FF>
        <tr>
            <th>Firstname</th>
            <th>Lastname</th>
            <th>Age</th>
        </tr>
        <tr>
            <td>Jill</td>
            <td>Smith</td>
            <td>50</td>
        </tr>
        <tr>
            <td>R</td>
            <td>D</td>
            <td>20</td>
        </tr>
        <tr>
            <td colspan="2">Anon</td>
        </tr>
<!--Use colspan to span a cell over multiple cols-->
4. HTML5: How to specify one or more header cells a cell is related to?
<table width:40% border="1" bgcolor=#90C2FF>
       
        <tr>
            <th id="uid">User Id</th>
            <th id="name">User Name</th>
            <th id="address">Address</th>
            <th id="phone">Phone No</th>
        </tr>
        <tr>
             <td headers="uid">U001</td>
             <td headers="name">Sudha Chandan</td>
             <td headers="address","name">99,J.C.Bose Road,kal-125042</td>
             <td headers="phone">5612445470</td>
        </tr>
        <!--To relate a cell to a header, use header=-->  
            </table>
5. The <img>  tag is used to insert an image into an HTML document. HTML image from the source specified in the <img> tag.
              <img src="download.jpg" alt="width" />
