try
            {
                int i = Convert.ToInt16(textBox1.Text); //cái này chứ không phải
 //textBox1.Text.ToInt32() .Lúc này nhầm .sorry(:P)
            }
            catch (Exception ex)
            {
                MessageBox.Show("loi");
                textBox1.Text = "";
            }
