# SVM-KM : SVM and Kernel Methods Matlab Toolbox

# Version

Yes, this is another SVM Toolbox but the thing new  is that it is fully written in Matlab (even the QP solver).
Packages updated on 20/02/2008.  This new package proposes a renaming of the "dataset" function which
is already used in Matlab 2007.

# Key Features

- SVM Classification using linear and quadratic penalization of  misclassified examples ( penalization coefficients can be different for each examples)
- SVM Classification with Nearest Point Algorithm
- Multiclass SVM : one against all, one against one and M-SVM
- Large Scale SVM Classification/Regression
- SVM epsilon and nu regression
- One-Class SVM
- Regularisation Networks
- SVM bounds (Span estimate, radius/margin)
- Wavelet Kernel  
- SVM Based Feature Selection
- Kernel PCA
- Kernel Discriminant Analysis
- SVM Based Feature selection
- SVM AUC Optimization (Ranking SVM, ROC SVM) and RankBoost
- Kernel Basis Pursuit and Least Angle Regression (LARS) Algorithm
- Wavelet Kernel Regression with backfitting
- Interface with a version of libsvm

The list of references describing the works implemented in this toolbox is here

# Download

Matlab source code
Matlab examples
      

# Install

- Download the zip files
- Uncompress them in a appropriate directory
- Add the toolbox directory and all sub-directory in the Matlab path
- Launch TestSanityCheck.m in order to verify if everything is OK... (it should take few minutes)
- Have fun with SVM!

# Licensing Arrangements


The toolbox is provided free for non-commercial use under the terms of the GNU General Public License (license.txt), however, we would be grateful if:
you let me know about any bugs you find.

please reference the toolbox web page in any publication describing research performed using the toolbox.
A suitable BibTeX entry would look something like this:

```
@misc{SVM-KMToolbox,
   author       = "S. Canu  and Y. Grandvalet and V. Guigue and A. Rakotomamonjy",
   title        = "SVM and Kernel Methods Matlab Toolbox ",
   howpublished = "Perception Systèmes et Information, INSA de Rouen, Rouen, France",
   year         = 2005
} 
```
.
THIS SOFTWARE IS PROVIDED BY THE AUTHOR ``AS IS'' AND ANY EXPRESS OR IMPLIED WARRANTIES, INCLUDING, BUT NOT LIMITED TO, THE IMPLIED WARRANTIES OF MERCHANTABILITY AND FITNESS FOR A PARTICULAR PURPOSE ARE DISCLAIMED. IN NO EVENT SHALL THE AUTHOR BE LIABLE FOR ANY DIRECT, INDIRECT, INCIDENTAL, SPECIAL, EXEMPLARY, OR CONSEQUENTIAL DAMAGES (INCLUDING, BUT NOT LIMITED TO, PROCUREMENT OF SUBSTITUTE GOODS OR SERVICES; LOSS OF USE, DATA, OR PROFITS; OR BUSINESS INTERRUPTION) HOWEVER CAUSED AND ON ANY THEORY OF LIABILITY, WHETHER IN CONTRACT, STRICT LIABILITY, OR TORT (INCLUDING NEGLIGENCE OR OTHERWISE) ARISING IN ANY WAY OUT OF THE USE OF THIS SOFTWARE, EVEN IF ADVISED OF THE POSSIBILITY OF SUCH DAMAGE. 

# Contacts


Alain Rakotomamonjy    
Stephane Canu                        

Insa de Rouen - Avenue de l'Universitéé- 76801 Saint Etienne du Rouvray
Tel : (33) (0)2.32.95.97.03  
Fax : (33)  (0)2.32.95.97.08

Modified by A. Rakotomamonjy on 20/12/2005
Uploaded to GitHub by R. Flamary on 14/02/2025