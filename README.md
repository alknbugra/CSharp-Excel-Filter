# CSharp-Excel-Filter

![Webp net-gifmaker](https://user-images.githubusercontent.com/29266933/58182181-d40c2000-7cb5-11e9-9e94-ef168b4ccd47.gif)

```sh

        // !note : dataView = anatable.DefaultView;
        

        private void comboBox1_SelectedIndexChanged(object sender, EventArgs e)
        {
            filtreCalistir();
        }
        
        private void comboBox2_SelectedIndexChanged(object sender, EventArgs e)
        {
            filtreCalistir();
        }
        
        .
        .
        .
        
        string kriterliFiltre = "";
        private void filtreCalistir()
        {
            kriterliFiltre = "";
            if (comboBox1.Text.ToString() != dizi[0].ToString())
            {
                if (kriterliFiltre != "")
                {
                    kriterliFiltre += " and " + anatable.Columns[0].ToString() + " IN ('" + comboBox1.Text.ToString() + "') ";
                }
                else
                {
                    kriterliFiltre = anatable.Columns[0].ToString() + " IN ('" + comboBox1.Text.ToString() + "') ";
                }
            }
            if (comboBox2.Text.ToString() != dizi[1].ToString())
            {
                if (kriterliFiltre != "")
                {
                    kriterliFiltre += " and " + anatable.Columns[1].ToString() + " IN ('" + comboBox2.Text.ToString() + "') ";
                }
                else
                {
                    kriterliFiltre = anatable.Columns[1].ToString() + " IN ('" + comboBox2.Text.ToString() + "') ";
                }
            }
            if (comboBox3.Text.ToString() != dizi[2].ToString())
            {
                if (kriterliFiltre != "")
                {
                    kriterliFiltre += " and " + anatable.Columns[2].ToString() + " IN ('" + comboBox3.Text.ToString() + "') ";
                }
                else
                {
                    kriterliFiltre = anatable.Columns[2].ToString() + " IN ('" + comboBox3.Text.ToString() + "') ";
                }
            }
            if (comboBox4.Text.ToString() != dizi[3].ToString())
            {
                if (kriterliFiltre != "")
                {
                    kriterliFiltre += " and " + anatable.Columns[3].ToString() + " IN ('" + comboBox4.Text.ToString() + "') ";
                }
                else
                {
                    kriterliFiltre = anatable.Columns[3].ToString() + " IN ('" + comboBox4.Text.ToString() + "') ";
                }
            }
            if (comboBox8.Text.ToString() != dizi[4].ToString())
            {
                if (kriterliFiltre != "")
                {
                    kriterliFiltre += " and " + anatable.Columns[4].ToString() + " IN ('" + comboBox8.Text.ToString() + "') ";
                }
                else
                {
                    kriterliFiltre = anatable.Columns[4].ToString() + " IN ('" + comboBox8.Text.ToString() + "') ";
                }
            }
            if (comboBox7.Text.ToString() != dizi[5].ToString())
            {
                if (kriterliFiltre != "")
                {
                    kriterliFiltre += " and " + anatable.Columns[5].ToString() + " IN ('" + comboBox7.Text.ToString() + "') ";
                }
                else
                {
                    kriterliFiltre = anatable.Columns[5].ToString() + " IN ('" + comboBox7.Text.ToString() + "') ";
                }
            }
            if (comboBox6.Text.ToString() != dizi[6].ToString())
            {
                if (kriterliFiltre != "")
                {
                    kriterliFiltre += " and " + anatable.Columns[6].ToString() + " IN ('" + comboBox6.Text.ToString() + "') ";
                }
                else
                {
                    kriterliFiltre = anatable.Columns[6].ToString() + " IN ('" + comboBox6.Text.ToString() + "') ";
                }
            }
            if (comboBox5.Text.ToString() != dizi[7].ToString())
            {
                if (kriterliFiltre != "")
                {
                    kriterliFiltre += " and " + anatable.Columns[7].ToString() + " IN ('" + comboBox5.Text.ToString() + "') ";
                }
                else
                {
                    kriterliFiltre = anatable.Columns[7].ToString() + " IN ('" + comboBox5.Text.ToString() + "') ";
                }
            }
            if (comboBox14.Text.ToString() != dizi[8].ToString())
            {
                if (kriterliFiltre != "")
                {
                    kriterliFiltre += " and " + anatable.Columns[8].ToString() + " IN ('" + comboBox14.Text.ToString() + "') ";
                }
                else
                {
                    kriterliFiltre = anatable.Columns[8].ToString() + " IN ('" + comboBox14.Text.ToString() + "') ";
                }
            }
            if (comboBox13.Text.ToString() != dizi[9].ToString())
            {
                if (kriterliFiltre != "")
                {
                    kriterliFiltre += " and " + anatable.Columns[9].ToString() + " IN ('" + comboBox13.Text.ToString() + "') ";
                }
                else
                {
                    kriterliFiltre = anatable.Columns[9].ToString() + " IN ('" + comboBox13.Text.ToString() + "') ";
                }
            }
            if (comboBox12.Text.ToString() != dizi[10].ToString())
            {
                if (kriterliFiltre != "")
                {
                    kriterliFiltre += " and " + anatable.Columns[10].ToString() + " IN ('" + comboBox12.Text.ToString() + "') ";
                }
                else
                {
                    kriterliFiltre = anatable.Columns[10].ToString() + " IN ('" + comboBox12.Text.ToString() + "') ";
                }
            }
            if (comboBox11.Text.ToString() != dizi[11].ToString())
            {
                if (kriterliFiltre != "")
                {
                    kriterliFiltre += " and " + anatable.Columns[11].ToString() + " IN ('" + comboBox11.Text.ToString() + "') ";
                }
                else
                {
                    kriterliFiltre = anatable.Columns[11].ToString() + " IN ('" + comboBox11.Text.ToString() + "') ";
                }
            }
            if (comboBox10.Text.ToString() != dizi[12].ToString())
            {
                if (kriterliFiltre != "")
                {
                    kriterliFiltre += " and " + anatable.Columns[12].ToString() + " IN ('" + comboBox10.Text.ToString() + "') ";
                }
                else
                {
                    kriterliFiltre = anatable.Columns[12].ToString() + " IN ('" + comboBox10.Text.ToString() + "') ";
                }
            }
            if (comboBox9.Text.ToString() != dizi[13].ToString())
            {
                if (kriterliFiltre != "")
                {
                    kriterliFiltre += " and " + anatable.Columns[13].ToString() + " IN ('" + comboBox9.Text.ToString() + "') ";
                }
                else
                {
                    kriterliFiltre = anatable.Columns[13].ToString() + " IN ('" + comboBox9.Text.ToString() + "') ";
                }
            }
            if (comboBox20.Text.ToString() != dizi[14].ToString())
            {
                if (kriterliFiltre != "")
                {
                    kriterliFiltre += " and " + anatable.Columns[14].ToString() + " IN ('" + comboBox20.Text.ToString() + "') ";
                }
                else
                {
                    kriterliFiltre = anatable.Columns[14].ToString() + " IN ('" + comboBox20.Text.ToString() + "') ";
                }
            }
            if (comboBox19.Text.ToString() != dizi[15].ToString())
            {
                if (kriterliFiltre != "")
                {
                    kriterliFiltre += " and " + anatable.Columns[15].ToString() + " IN ('" + comboBox19.Text.ToString() + "') ";
                }
                else
                {
                    kriterliFiltre = anatable.Columns[15].ToString() + " IN ('" + comboBox19.Text.ToString() + "') ";
                }
            }

            MessageBox.Show(kriterliFiltre);
            dataView.RowFilter = kriterliFiltre;
            dataGridView1.DataSource = dataView;
        }

```
