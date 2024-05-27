<style>
    table {
        border: 1px solid;
    }

    .table-red {
        color: red;
        font-weight: bold;
    }

    .table-red ul {
        margin: 0;
        padding: 0;
        list-style: none;
    }
</style>

<h1> Rangkuman Quiz Scientific Computing </h1>

<h3> Outline: </h3>
<ul>
    <li>
        <a href="https://www.w3schools.com/python/default.asp"> 
            Python Fundamental 
        </a>
    </li>
    <li>
        <a href="#numpy"> 
            NumPy 
        </a>
    </li>
    <li>
        <a href="#pandas">
            Pandas
        </a> 
    </li>
    <li> 
        <a href="#matplotlib"> 
            Matplotlib
        </a> 
    </li>
    <li> Scipy </li>
    <li> System of Linear Equation </li>
    <li> Regression and Interpolation </li>
    <li> Root of Equation </li>
    <li> Numerical Differentiation and Integration  </li>
</ul>

<section>
    <h2 id="numpy"> NumPy </h2>
    <p> NumPy (Numerical Python) is an open source Python library that's used in almost every field of science and engineering. </p>
    <table>
        <thead>
            <th> Functions </th>
            <th> Description </th>
        </thead>
        <tbody>
            <tr>
                <td class="table-red">
                    np.array()
                </td>
                <td>
                    To create a NumPy array
                </td>
            </tr>
            <tr>
                <td class="table-red">
                    np.zeros()
                </td>
                <td>
                    To create an array filled with 0's
                </td>
            </tr>
            <tr>
                <td class="table-red">
                    np.ones()
                </td>
                <td>
                    To create an array filled with 1's
                </td>
            </tr> 
            <tr>
                <td class="table-red">
                    np.empty()
                </td>
                <td>
                    To create an empty array (initial content is random)
                </td>
            </tr>
            <tr>
                <td class="table-red">
                    np.arange()
                </td>
                <td>
                    To create an array that contains a range of evenly spaced intervals
                </td>
            </tr>
            <tr>
                <td class="table-red">
                    np.linspace()
                </td>
                <td>
                    To create an array that contains a range of evenly spaced intervals
                </td>
            </tr>
            <tr>
                <td class="table-red">
                    np.sort()
                </td>
                <td>
                    To sort element in array in ascending orders
                </td>
            </tr>
            <tr>
                <td class="table-red">
                    np.concatenate()
                </td>
                <td>
                    To concatenate  array
                </td>
            </tr>
            <tr>
                <td class="table-red">
                    ndarray.ndim
                </td>
                <td>
                    To tell the dimensions of the array
                </td>
            </tr>
            <tr>
                <td class="table-red">
                    ndarray.size
                </td>
                <td>
                    To tell the number of elements of the array
                </td>
            </tr>
            <tr>
                <td class="table-red">
                    ndarray.shape
                </td>
                <td>
                    To tell the number of elements stored along each dimension of the array
                </td>
            </tr>                                         <tr>
                <td class="table-red">
                    np.reshape()
                </td>
                <td>
                    To  give a new shape to an array without changing the data
                </td>
            </tr>                                          <tr>
                <td class="table-red">
                    np.hstack()
                </td>
                <td>
                    To stack two existing arrays horizontally
                </td>
            </tr>  
            <tr>
                <td class="table-red">
                    np.vstack()
                </td>
                <td>
                    To stack two existing arrays vertically
                </td>
            </tr>
            <tr>
                <td class="table-red">
                    <ul>
                        <li> ndarray.min() </li>
                        <li> ndarray.max() </li>
                        <li> ndarray.sum() </li>
                        <li> ndarray.mean() </li>
                        <li> ndarray.prod() </li>
                        <li> ndarray.std()</li>
                    </ul>
                </td>
                <td>
                    Aggregation functions
                </td>
            </tr> 
            <tr>
                <td class="table-red">
                    ndarray.T
                </td>
                <td>
                    To transposing an array
                </td>
            </tr>                                
        </tbody>
    </table>
    <p> Don't forgot to import the library first! </p>
    <code> import numpy as np </code><br><br>
    <p> For more information, read <a href="https://numpy.org/doc/stable/user/whatisnumpy.html"> NumPy official documentation </a></p>
</section>

<section>
    <h2 id="pandas"> Pandas </h2>
    <p> Pandas is a Python library used to analyze data. </p>
    <table>
        <thead>
            <th> Functions </th>
            <th> Description </th>
        </thead>
        <tbody>
            <td class="table-red"> pd.read_* </td>
            <td> 
                To read data stored as a * file. For example, <span class="table-red"> pd.read_csv </span> for reading a csv file, etc. 
            </td>
        </tbody>
    </table>
    <p> For more information, read <a href="https://pandas.pydata.org/docs/getting_started/intro_tutorials/01_table_oriented.html"> Pandas official documentation </a></p>
</section>

<section>
    <h2 id="matplotlib"> Matplotlib </h2>
    <p> Matplotlib is a comprehensive library for creating static, animated, and interactive visualizations. </p>
    <img src="https://matplotlib.org/cheatsheets/_images/handout-beginner.png"/>
    <img src="https://matplotlib.org/cheatsheets/_images/handout-intermediate.png"/>
    <img src="https://matplotlib.org/cheatsheets/_images/handout-tips.png"/>
    <img src="https://matplotlib.org/cheatsheets/_images/cheatsheets-1.png"/>
    <p> For more information, read <a href="https://matplotlib.org/stable/tutorials/pyplot.html#sphx-glr-tutorials-pyplot-py"> Matplotlib official documentation </a></p>
</section>
