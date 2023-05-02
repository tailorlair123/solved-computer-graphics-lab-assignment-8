Download Link: https://assignmentchef.com/product/solved-computer-graphics-lab-assignment-8
<br>
<strong>Computer Graphics, Lab Assignment 8 </strong>

+ LabAssignment2/

+ 1/

<ul>

 <li>py</li>

</ul>

+ 2/

<ul>

 <li>py</li>

</ul>

+ 3/

<ul>

 <li>py</li>

</ul>




<ul>

 <li>The submission time is determined not when the commit is made but when the git push is made.</li>

</ul>




<ol>

 <li>Write a program that draws a color-changing cube.

  <ol>

   <li>Set the window title to <strong>your student ID</strong> and the window size to (480,480).</li>

   <li>Start from the code in 7-Lighting&amp;Shading slides. Draw a flat-shaded cube. Make sure camera manipulation shortcuts ‘1’, ‘3’, ‘2’, ‘w’ work. C. Use the following light setting:</li>

  </ol></li>

</ol>

lightPos <strong>=</strong> <strong>(</strong>3.<strong>,</strong>4.<strong>,</strong>5.<strong>,</strong>1.<strong>)</strong>

glLightfv<strong>(</strong>GL_LIGHT0<strong>,</strong> GL_POSITION<strong>,</strong> lightPos<strong>)</strong>




ambientLightColor <strong>=</strong> <strong>(</strong>.1<strong>,</strong>.1<strong>,</strong>.1<strong>,</strong>1.<strong>)</strong>     glLightfv<strong>(</strong>GL_LIGHT0<strong>,</strong> GL_AMBIENT<strong>,</strong> ambientLightColor<strong>)</strong>




specularObjectColor <strong>=</strong> <strong>(</strong>1.<strong>,</strong>1.<strong>,</strong>1.<strong>,</strong>1.<strong>)</strong>     glMaterialfv<strong>(</strong>GL_FRONT<strong>,</strong> GL_SPECULAR<strong>,</strong> specularObjectColor<strong>)</strong>




glMaterialfv<strong>(</strong>GL_FRONT<strong>,</strong> GL_SHININESS<strong>,</strong> 10<strong>)</strong>




<ol>

 <li>If you press or repeat a key, the diffuse &amp; specular color of the light and the ambient &amp; diffuse color of the object should be changed as shown in the Table:</li>

</ol>

<table width="371">

 <tbody>

  <tr>

   <td width="36"><strong>Key </strong></td>

   <td width="335"><strong>Action </strong></td>

  </tr>

  <tr>

   <td width="36">A</td>

   <td width="335">Change the light color to red</td>

  </tr>

  <tr>

   <td width="36">S</td>

   <td width="335">Change the light color to green</td>

  </tr>

  <tr>

   <td width="36">D</td>

   <td width="335">Change the light color to blue</td>

  </tr>

  <tr>

   <td width="36">F</td>

   <td width="335">Change the light color to white</td>

  </tr>

  <tr>

   <td width="36">Z</td>

   <td width="335">Change the object color to red</td>

  </tr>

  <tr>

   <td width="36">X</td>

   <td width="335">Change the object color to green</td>

  </tr>

  <tr>

   <td width="36">C</td>

   <td width="335">Change the object color to blue</td>

  </tr>

  <tr>

   <td width="36">V</td>

   <td width="335">Change the object color to white</td>

  </tr>

 </tbody>

</table>

<ol>

 <li>Files to submit: A Python source file (Name the file whatever you want (in English). Extension should be .py)</li>

</ol>




<ol start="2">

 <li>Write a program that draws a smooth-shaded cube.

  <ol>

   <li>Set the window title to <strong>your student ID</strong> and the window size to (480,480).</li>

   <li>Start from the code in 8-Lighting&amp;Shading slides. Make sure camera manipulation shortcuts ‘1’, ‘3’, ‘2’, ‘w’ work.</li>

   <li>Use <strong>glDrawElements(),</strong> not glDrawArray(). Refer the code in 7-Hierarchy&amp;Mesh slides.</li>

   <li>Hint: In Gouraud shading, one vertex has only one normal. This makes using glDrawElements() easier.</li>

   <li>Use the following normal vector data:</li>

  </ol></li>

</ol>




<ol>

 <li>Files to submit: A Python source file (Name the file whatever you want (in English). Extension should be .py)</li>

</ol>


