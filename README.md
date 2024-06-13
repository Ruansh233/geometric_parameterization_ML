# geometric_parameterization_ML

### A test case for geometrical parameterization using machine learning.

#### Steps for reproducing the simulation
You can follow the steps to run the case:

<ol>
  <li>generate_mesh.ipynb</li>
  <li>simulation_data/data_generation</li>
  <li>data_preprocessing.ipynb</li>
  <li>prediction
    <ol>
      <li>EZyRB_PODI.ipynb or PODI.ipynb
      <li>The three <strong>AE</strong> codes are still under programming.
    </ol>
  </li>
</ol>

#### Python packages
<ol>
  <li>The simulations are carried out by <strong>OpenFOAM v2306</strong>.</li>
  <li>It is recommended to use conda to manage the Python packages used in the case.
      The required packages are listed in the file <strong>package-list.txt</strong>. You can install it by running: 
      <code>conda create --name <env> --file package-list.txt</code>
  </li>
  <li>The EZyRB packages for PODI can be installed by running: 
      <code>pip install git+https://github.com/mathLab/EZyRB</code>. But there might be conflicts between the packages. Please create a new env if any problems with importing packages occur.
  </li>
</ol>

