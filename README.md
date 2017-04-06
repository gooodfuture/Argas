# Argas
OpenFileDialog fileDialog = new OpenFileDialog();        
fileDialog.Multiselect = true;           
fileDialog.Title = "请选择文件";           
fileDialog.Filter = "所有文件(*.*)|*.*";           
if (fileDialog.ShowDialog() == DialogResult.OK)         
{                 string file = fileDialog.FileName;            
MessageBox.Show("已选择文件:" + file, "选择文件提示", MessageBoxButtons.OK, MessageBoxIcon.Information);             }
