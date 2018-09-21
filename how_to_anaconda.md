# Installing Python with Anaconda

Instructions kindly provided by [Wil Ward](https://wilocw.gitlab.io/)

Anaconda is a distribution of the Python programming language that comes integrated with a number of precompiled libraries, and its own package and environment manager, called `conda`. It freely allows use of installation of packages and libraries via `conda` or <code>pip</code>. We recommend using Anaconda to manage your Python language environment, <em>particularly if you are new to Python</em>, and the following instructions will assume you are using Anaconda. If you are using a different Python distribution, you may have to tailor to following instructions, but you should ensure that you are using Python 3.5+.

### Installing 

The easiest way to get a working Python environment is to install Anaconda. It is fairly straightforward to install, but can take some time so you must make sure this is done before the lab.

1. Download and install the free version of Anaconda from its webpage: <a target="_blank" href="https://www.anaconda.com/download">https://www.anaconda.com/download</a>, selecting the <em>Python 3.6 version</em> appropriate for your operating system
           
	 -	Windows: the installer will be a <code>.exe</code> executable, and you can follow the setup as instructed
    - Linux: the installer is a <code>.sh</code> shell script, and you can run 		it in the terminal and follow the setup as instructed. Note you may have 		to enable execution of the file, by either
		- Right click the file and select Properties, and under <code>Permissions</code> check "Allow executing file as program"
                                <li><code>$ chmod +x /path/to/installationfile.sh</code></li>
                            
    - macOS: the installer is a <code>.pkg</code> software package, and you can follow the setup as instructed</li>
            </ul>
        </li>
        <li>Update Anaconda, <code>numpy</code>, <code>scipy</code>, and <code>matplotlib</code>: open a command prompt or terminal and execute the following commands
            <ol>
                <li><code>conda update -y anaconda</code></li>
                <li><code>conda update -y numpy scipy matplotlib</code></li>
            </ol>
        </li>
        <li>Update <code>jupyter</code>
            <ol>
                <li><code>conda update -y jupyter</code></li>
                <li>If you are not using Anaconda, you can install <code>jupyter</code> by calling <code>$ python3 -m pip install juypter</code></li>
            </ol>
        </li>
    </ol>
