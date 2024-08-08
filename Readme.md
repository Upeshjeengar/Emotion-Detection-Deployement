## Some Key Features and Demo:
1. This model can **detect seven emotions**: 'Angry', 'Disgust', 'Fear', 'Happy', 'Neutral', 'Sad', 'Surprise'
2. The model was having **test accuracy of around 63.71%**.
3. The model is implemented on top of one of the best CNN model, **RESNET-50 architecture**.

# Guide to use this model
Requirements: <a href="https://www.python.org/downloads/"> `Python`</a>  Must be installed on your computer

As publishing big files is not allowed on github, we can diretly download models from this <a href="https://drive.google.com/file/d/116vQNP6Poh0VRbAmmjU2dbaL1rUGt_Wt/view?usp=sharing">gdrive link</a>

After downloading and unziping files Move to project's directory in **terminal**(VS Code terminal is recommended).   
It is recommended to create a virtual environment.

**Guide to create a Virtual Environment in python**  
1. Create the virtual environment : `python -m venv myenv `      
2. Activate the virtual environment:
    <div class="responsive-table__container"><table class="docutils align-default">
    <thead>
    <tr class="row-odd"><th class="head"><p>Platform</p></th>
    <th class="head"><p>Shell</p></th>
    <th class="head"><p>Command to activate virtual environment</p></th>
    </tr>
    </thead>
    <tbody>
    <tr class="row-even"><td rowspan="4"><p>POSIX</p></td>
    <td><p>bash/zsh</p></td>
    <td><p><code class="samp docutils literal notranslate"><span class="pre">$</span> <span class="pre">source</span> <em><span class="pre">&lt;venv&gt;</span></em><span class="pre">/bin/activate</span></code></p></td>
    </tr>
    <tr class="row-odd"><td><p>fish</p></td>
    <td><p><code class="samp docutils literal notranslate"><span class="pre">$</span> <span class="pre">source</span> <em><span class="pre">&lt;venv&gt;</span></em><span class="pre">/bin/activate.fish</span></code></p></td>
    </tr>
    <tr class="row-even"><td><p>csh/tcsh</p></td>
    <td><p><code class="samp docutils literal notranslate"><span class="pre">$</span> <span class="pre">source</span> <em><span class="pre">&lt;venv&gt;</span></em><span class="pre">/bin/activate.csh</span></code></p></td>
    </tr>
    <tr class="row-odd"><td><p>PowerShell</p></td>
    <td><p><code class="samp docutils literal notranslate"><span class="pre">$</span> <em><span class="pre">&lt;venv&gt;</span></em><span class="pre">/bin/Activate.ps1</span></code></p></td>
    </tr>
    <tr class="row-even"><td rowspan="2"><p>Windows</p></td>
    <td><p>cmd.exe</p></td>
    <td><p><code class="samp docutils literal notranslate"><span class="pre">C:\&gt;</span> <em><span class="pre">&lt;venv&gt;</span></em><span class="pre">\Scripts\activate.bat</span></code></p></td>
    </tr>
    <tr class="row-odd"><td><p>PowerShell</p></td>
    <td><p><code class="samp docutils literal notranslate"><span class="pre">PS</span> <span class="pre">C:\&gt;</span> <em><span class="pre">&lt;venv&gt;</span></em><span class="pre">\Scripts\Activate.ps1</span></code></p></td>
    </tr>
    </tbody>
    </table></div>
3.  Install packages: `pip install <package_name>`    

4. To Deactivate the virtual environment  `deactivate`           
     
After creating and activating virtual environment,install requirements.txt using this command: `pip install -r requirements.txt`

Now we are ready to test,
Run test.py using `python test.py` or `python3 test.py`
