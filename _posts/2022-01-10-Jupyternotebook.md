## Data: Jupyter Notebook
### Install
```
pip install notebook    // Install
jupyter notebook        //Start

//However, install notebook by anaconda is better
//1. download and install anaconda 
conda install -c conda-forge notebook
jupyter notebook        //Start

```
### Difference between pip and conda

Comparison of conda and pip
<table>
<tr>
 <td>       </td>                <td>conda</td>	                      <td>pip</td>
</tr>
<tr> <td>manages</td>                 <td>binaries</td>	                     <td>wheel or source</td></tr>
<tr> <td>can require compilers</td>	  <td>no</td>	                           <td>yes</td></tr>
<tr> <td>package types</td>	          <td>any</td>	                         <td>Python-only</td></tr>
<tr> <td>create environment</td>	    <td>yes, built-in</td>	               <td>no, requires virtualenv or venv</td></tr>
<tr> <td>dependency checks</td>	      <td>yes</td>                           <td>no</td></tr>
<tr> <td>package sources</td>         <td>Anaconda repo and cloud</td>       <td>PyPI</td></tr>
  
</table>

### Change the Jupyter start-up folder

```
// For Jupyter Notebook and JupyterLab < 3.0
jupyter notebook --generate-config   // inpute in the terminal and open generated file

/*
Change 
#c.NotebookApp.notebook_dir = ''
to 
c.NotebookApp.notebook_dir = '/start-up_folder_path'
*/

// JupyterLab >= 3, Jupyter Notebook Classic, and RetroLab
jupyter server --generate-config // inpute in the terminal and open generated file

/*
Change 
#c.ServerApp.root_dir = ''
to 
c.ServerApp.root_dir = '/start-up_folder_path'
*/
```
