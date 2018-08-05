# Research-Software
If ComboBox1.Visible = True Then


            If ComboBox1.Text = "" Then


                MsgBox("Please select an A value")


            Else


                Dim H As Decimal


                '     H = 0.89 * (2.62 * ComboBox1.Text * Math.Log(1 + (360 / 235)))


                H = (2.43 * ComboBox1.Text) - 2.43


                H = Math.Round(H, 2)


                TextBox7.Text = H



                Dim I As Decimal


                ' I = 0.89 * (2.62 * ComboBox1.Text * Math.Log(1 + (540 / 235)))


                I = (3.13 * ComboBox1.Text) - 3.13


                I = Math.Round(I, 2)


                TextBox8.Text = I



                Dim J As Decimal


                '     J = 0.89 * (2.62 * ComboBox1.Text * Math.Log(1 + (720 / 235)))


                J = (3.65 * ComboBox1.Text) - 3.65


                J = Math.Round(J, 2)


                TextBox9.Text = J



                Dim K As Decimal


                '  K = 0.9 * (2.62 * ComboBox1.Text * Math.Log(1 + (900 / 235)))


                K = (4.16 * ComboBox1.Text) - 3.98


                K = Math.Round(K, 2)


                TextBox10.Text = K


                Button5.Enabled = True



            End If


        End If
