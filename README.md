# Research-Software

Imports System.IO


Imports System.Diagnostics


Imports System.Globalization



Public Class Form1



    Private Sub Button2_Click(sender As Object, e As EventArgs) Handles Button2.Click


        Label73.BackColor = Color.White


        Label74.BackColor = Color.White


        Label75.BackColor = Color.White


        Label76.BackColor = Color.White


        Label77.BackColor = Color.White


        Label78.BackColor = Color.White


        Label79.BackColor = Color.White


        Label80.BackColor = Color.White


        Label81.BackColor = Color.White


        Label82.BackColor = Color.White


        Label83.BackColor = Color.White


        Label84.BackColor = Color.White


        Label85.BackColor = Color.White


        Label86.BackColor = Color.White


        Label87.BackColor = Color.White


        Label88.BackColor = Color.White


        Label89.BackColor = Color.White


        Label90.BackColor = Color.White


        Label91.BackColor = Color.White


        Label92.BackColor = Color.White


        Label93.BackColor = Color.White


        Label94.BackColor = Color.White


        Label95.BackColor = Color.White


        Label96.BackColor = Color.White


        Label97.BackColor = Color.White


        Label98.BackColor = Color.White


        Label99.BackColor = Color.White


        If ComboBox1.Visible = True Then


            If ComboBox1.Text = "" Then


                MsgBox("Please select an A value")



            Else


                Dim D As String


                D = ComboBox1.Text


                Dim F As Decimal


                F = (2.62 * D * Math.Log(1 + (900 / 235)))


                F = Math.Round(F, 2)


                TextBox5.Text = F


                PictureBox6.Visible = True


                Label110.Visible = True


                Label7.ForeColor = Color.Red


                Button3.Enabled = True


                If TextBox5.Text > 44 Then


                    MsgBox("Seems your system's Microsoft Windows language is European. Please select the € symbol for the A value selection")


                End If


            End If


        End If


        If ComboBox4.Visible = True Then


            If ComboBox4.Text = "" Then


                MsgBox("Please select an A value")



            Else


                Dim D As String


                D = ComboBox4.Text


                Dim F As Decimal


                F = (2.62 * D * Math.Log(1 + (900 / 235)))


                F = Math.Round(F, 2)


                TextBox5.Text = F


                PictureBox6.Visible = True


                Label7.ForeColor = Color.Red


                Button3.Enabled = True


                If TextBox5.Text > 44 Then


                    MsgBox("Seems your system's Microsoft Windows language is English. Please select the $ or £ symbol for the A value selection")


                End If


            End If


        End If



    End Sub



    Private Sub Button3_Click(sender As Object, e As EventArgs) Handles Button3.Click


        Label73.BackColor = Color.White


        Label74.BackColor = Color.White


        Label75.BackColor = Color.White


        Label76.BackColor = Color.White


        Label77.BackColor = Color.White


        Label78.BackColor = Color.White


        Label79.BackColor = Color.White


        Label80.BackColor = Color.White


        Label81.BackColor = Color.White


        Label82.BackColor = Color.White


        Label83.BackColor = Color.White


        Label84.BackColor = Color.White


        Label85.BackColor = Color.White


        Label86.BackColor = Color.White


        Label87.BackColor = Color.White


        Label88.BackColor = Color.White


        Label89.BackColor = Color.White


        Label90.BackColor = Color.White


        Label91.BackColor = Color.White


        Label92.BackColor = Color.White


        Label93.BackColor = Color.White


        Label94.BackColor = Color.White


        Label95.BackColor = Color.White


        Label96.BackColor = Color.White


        Label97.BackColor = Color.White


        Label98.BackColor = Color.White


        Label99.BackColor = Color.White



        If ComboBox1.Visible = True Then


            If ComboBox1.Text = "" Then


                MsgBox("Please select an A value")


                PictureBox5.Visible = False



            Else



                Label3.Visible = True


                Label4.Visible = True


                Label103.Visible = True


                Dim G As Decimal


                G = (4.16 * ComboBox1.Text) - 3.98


                G = Math.Round(G, 2)


                TextBox6.Text = G


                TextBox11.Text = Math.Round(G, 0)


                Button4.Enabled = True


                PictureBox7.Visible = True


                PictureBox3.Visible = True


                Label111.Visible = True


                PictureBox5.Image = My.Resources.red_arrow


            End If


        End If



        If ComboBox4.Visible = True Then


            If ComboBox4.Text = "" Then


                MsgBox("Please select an A value")


                PictureBox5.Visible = False



            Else


                Label3.Visible = True


                Label4.Visible = True



　


                Dim G As Decimal


                G = (4.16 * ComboBox4.Text) - 3.98


                G = Math.Round(G, 2)


                TextBox6.Text = G


                TextBox11.Text = Math.Round(G, 0)


                Button4.Enabled = True


                PictureBox7.Visible = True


                PictureBox5.Image = My.Resources.red_arrow


            End If


        End If


        If TextBox5.Text > 44 Then


            MsgBox("Seems your system's Microsoft Windows language is European. Please select the € symbol for the A value selection")


        End If



    End Sub



    Private Sub Button4_Click(sender As Object, e As EventArgs) Handles Button4.Click


        Label73.BackColor = Color.White


        Label74.BackColor = Color.White


        Label75.BackColor = Color.White


        Label76.BackColor = Color.White


        Label77.BackColor = Color.White


        Label78.BackColor = Color.White


        Label79.BackColor = Color.White


        Label80.BackColor = Color.White


        Label81.BackColor = Color.White


        Label82.BackColor = Color.White


        Label83.BackColor = Color.White


        Label84.BackColor = Color.White


        Label85.BackColor = Color.White


        Label86.BackColor = Color.White


        Label87.BackColor = Color.White


        Label88.BackColor = Color.White


        Label89.BackColor = Color.White


        Label90.BackColor = Color.White


        Label91.BackColor = Color.White


        Label92.BackColor = Color.White


        Label93.BackColor = Color.White


        Label94.BackColor = Color.White


        Label95.BackColor = Color.White


        Label96.BackColor = Color.White


        Label97.BackColor = Color.White


        Label98.BackColor = Color.White


        Label99.BackColor = Color.White



        '  If TextBox5.Text > 44 Then


        ' MsgBox("Seems your system's Microsoft Windows language is European. Please select the € symbol for the A value selection")


        'End If



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



        If ComboBox4.Visible = True Then



            If ComboBox4.Text = "" Then


                MsgBox("Please select an A value")



            Else


                Dim H As Decimal


                '  H = 0.89 * (2.62 * ComboBox4.Text * Math.Log(1 + (360 / 235)))


                H = (2.43 * ComboBox4.Text) - 2.43


                H = Math.Round(H, 2)


                TextBox7.Text = H



                Dim I As Decimal


                ' I = 0.89 * (2.62 * ComboBox4.Text * Math.Log(1 + (540 / 235)))


                I = (3.13 * ComboBox4.Text) - 3.13


                I = Math.Round(I, 2)


                TextBox8.Text = I



                Dim J As Decimal


                ' J = 0.89 * (2.62 * ComboBox4.Text * Math.Log(1 + (720 / 235)))


                J = (3.65 * ComboBox4.Text) - 3.65


                J = Math.Round(J, 2)


                TextBox9.Text = J



                Dim K As Decimal


                '  K = 0.9 * (2.62 * ComboBox4.Text * Math.Log(1 + (900 / 235)))


                K = (4.16 * ComboBox4.Text) - 3.98


                K = Math.Round(K, 2)


                TextBox10.Text = K


                Button5.Enabled = True



            End If


        End If


        If TextBox5.Text > 44 Then


            MsgBox("Seems your system's Microsoft Windows language is European. Please select the € symbol for the A value selection")


        End If



    End Sub



　


　


    Private Sub TextBox11_TextChanged(sender As Object, e As EventArgs) Handles TextBox11.TextChanged


        If ComboBox1.Visible = True Then



　


            If TextBox11.Text = 26 Then


                Label18.Text = 0


                Label19.Text = 1


                Label20.Text = 2


                Label21.Text = 3


                Label22.Text = 4


                Label23.Text = 5


                Label24.Text = 6


                Label25.Text = 7


                Label26.Text = 8


                Label27.Text = 9


                Label28.Text = 10


                Label29.Text = 11


                Label30.Text = 12


                Label31.Text = 13


                Label32.Text = 14


                Label33.Text = 15


                Label34.Text = 16


                Label35.Text = 17


                Label36.Text = 18


                Label37.Text = 19


                Label38.Text = 20


                Label39.Text = 21


                Label40.Text = 22


                Label41.Text = 23


                Label42.Text = 24


                Label43.Text = 25


                Label44.Text = 26


                Label45.Text = ""


                Label46.Text = ""


                Label47.Text = ""


                Label48.Text = ""


                Label49.Text = ""


                Label50.Text = ""


                Label51.Text = ""


                Label52.Text = ""


                Label53.Text = ""


                Label54.Text = ""


                Label55.Text = ""


                Label56.Text = ""


                Label57.Text = ""


                Label58.Text = ""


            End If


            If TextBox11.Text = 27 Then


                Label18.Text = 0


                Label19.Text = 1


                Label20.Text = 2


                Label21.Text = 3


                Label22.Text = 4


                Label23.Text = 5


                Label24.Text = 6


                Label25.Text = 7


                Label26.Text = 8


                Label27.Text = 9


                Label28.Text = 10


                Label29.Text = 11


                Label30.Text = 12


                Label31.Text = 13


                Label32.Text = 14


                Label33.Text = 15


                Label34.Text = 16


                Label35.Text = 17


                Label36.Text = 18


                Label37.Text = 19


                Label38.Text = 20


                Label39.Text = 21


                Label40.Text = 22


                Label41.Text = 23


                Label42.Text = 24


                Label43.Text = 25


                Label44.Text = 26


                Label45.Text = 27


                Label46.Text = ""


                Label47.Text = ""


                Label48.Text = ""


                Label49.Text = ""


                Label50.Text = ""


                Label51.Text = ""


                Label52.Text = ""


                Label53.Text = ""


                Label54.Text = ""


                Label55.Text = ""


                Label56.Text = ""


                Label57.Text = ""


                Label58.Text = ""


            End If


            If TextBox11.Text = 28 Then


                Label18.Text = 0


                Label19.Text = 1


                Label20.Text = 2


                Label21.Text = 3


                Label22.Text = 4


                Label23.Text = 5


                Label24.Text = 6


                Label25.Text = 7


                Label26.Text = 8


                Label27.Text = 9


                Label28.Text = 10


                Label29.Text = 11


                Label30.Text = 12


                Label31.Text = 13


                Label32.Text = 14


                Label33.Text = 15


                Label34.Text = 16


                Label35.Text = 17


                Label36.Text = 18


                Label37.Text = 19


                Label38.Text = 20


                Label39.Text = 21


                Label40.Text = 22


                Label41.Text = 23


                Label42.Text = 24


                Label43.Text = 25


                Label44.Text = 26


                Label45.Text = 27


                Label46.Text = 28


                Label47.Text = ""


                Label48.Text = ""


                Label49.Text = ""


                Label50.Text = ""


                Label51.Text = ""


                Label52.Text = ""


                Label53.Text = ""


                Label54.Text = ""


                Label55.Text = ""


                Label56.Text = ""


                Label57.Text = ""


                Label58.Text = ""


            End If


            If TextBox11.Text = 29 Then


                Label18.Text = 0


                Label19.Text = 1


                Label20.Text = 2


                Label21.Text = 3


                Label22.Text = 4


                Label23.Text = 5


                Label24.Text = 6


                Label25.Text = 7


                Label26.Text = 8


                Label27.Text = 9


                Label28.Text = 10


                Label29.Text = 11


                Label30.Text = 12


                Label31.Text = 13


                Label32.Text = 14


                Label33.Text = 15


                Label34.Text = 16


                Label35.Text = 17


                Label36.Text = 18


                Label37.Text = 19


                Label38.Text = 20


                Label39.Text = 21


                Label40.Text = 22


                Label41.Text = 23


                Label42.Text = 24


                Label43.Text = 25


                Label44.Text = 26


                Label45.Text = 27


                Label46.Text = 28


                Label47.Text = 29


                Label48.Text = ""


                Label49.Text = ""


                Label50.Text = ""


                Label51.Text = ""


                Label52.Text = ""


                Label53.Text = ""


                Label54.Text = ""


                Label55.Text = ""


                Label56.Text = ""


                Label57.Text = ""


                Label58.Text = ""


            End If


            If TextBox11.Text = 30 Then


                Label18.Text = 0


                Label19.Text = 1


                Label20.Text = 2


                Label21.Text = 3


                Label22.Text = 4


                Label23.Text = 5


                Label24.Text = 6


                Label25.Text = 7


                Label26.Text = 8


                Label27.Text = 9


                Label28.Text = 10


                Label29.Text = 11


                Label30.Text = 12


                Label31.Text = 13


                Label32.Text = 14


                Label33.Text = 15


                Label34.Text = 16


                Label35.Text = 17


                Label36.Text = 18


                Label37.Text = 19


                Label38.Text = 20


                Label39.Text = 21


                Label40.Text = 22


                Label41.Text = 23


                Label42.Text = 24


                Label43.Text = 25


                Label44.Text = 26


                Label45.Text = 27


                Label46.Text = 28


                Label47.Text = 29


                Label48.Text = 30


                Label49.Text = ""


                Label50.Text = ""


                Label51.Text = ""


                Label52.Text = ""


                Label53.Text = ""


                Label54.Text = ""


                Label55.Text = ""


                Label56.Text = ""


                Label57.Text = ""


                Label58.Text = ""


            End If


            If TextBox11.Text = 31 Then


                Label18.Text = 0


                Label19.Text = 1


                Label20.Text = 2


                Label21.Text = 3


                Label22.Text = 4


                Label23.Text = 5


                Label24.Text = 6


                Label25.Text = 7


                Label26.Text = 8


                Label27.Text = 9


                Label28.Text = 10


                Label29.Text = 11


                Label30.Text = 12


                Label31.Text = 13


                Label32.Text = 14


                Label33.Text = 15


                Label34.Text = 16


                Label35.Text = 17


                Label36.Text = 18


                Label37.Text = 19


                Label38.Text = 20


                Label39.Text = 21


                Label40.Text = 22


                Label41.Text = 23


                Label42.Text = 24


                Label43.Text = 25


                Label44.Text = 26


                Label45.Text = 27


                Label46.Text = 28


                Label47.Text = 29


                Label48.Text = 30


                Label49.Text = 31


                Label50.Text = ""


                Label51.Text = ""


                Label52.Text = ""


                Label53.Text = ""


                Label54.Text = ""


                Label55.Text = ""


                Label56.Text = ""


                Label57.Text = ""


                Label58.Text = ""


            End If


            If TextBox11.Text = 32 Then


                Label18.Text = 0


                Label19.Text = 1


                Label20.Text = 2


                Label21.Text = 3


                Label22.Text = 4


                Label23.Text = 5


                Label24.Text = 6


                Label25.Text = 7


                Label26.Text = 8


                Label27.Text = 9


                Label28.Text = 10


                Label29.Text = 11


                Label30.Text = 12


                Label31.Text = 13


                Label32.Text = 14


                Label33.Text = 15


                Label34.Text = 16


                Label35.Text = 17


                Label36.Text = 18


                Label37.Text = 19


                Label38.Text = 20


                Label39.Text = 21


                Label40.Text = 22


                Label41.Text = 23


                Label42.Text = 24


                Label43.Text = 25


                Label44.Text = 26


                Label45.Text = 27


                Label46.Text = 28


                Label47.Text = 29


                Label48.Text = 30


                Label49.Text = 31


                Label50.Text = 32


                Label51.Text = ""


                Label52.Text = ""


                Label53.Text = ""


                Label54.Text = ""


                Label55.Text = ""


                Label56.Text = ""


                Label57.Text = ""


                Label58.Text = ""


            End If


            If TextBox11.Text = 33 Then


                Label18.Text = 0


                Label19.Text = 1


                Label20.Text = 2


                Label21.Text = 3


                Label22.Text = 4


                Label23.Text = 5


                Label24.Text = 6


                Label25.Text = 7


                Label26.Text = 8


                Label27.Text = 9


                Label28.Text = 10


                Label29.Text = 11


                Label30.Text = 12


                Label31.Text = 13


                Label32.Text = 14


                Label33.Text = 15


                Label34.Text = 16


                Label35.Text = 17


                Label36.Text = 18


                Label37.Text = 19


                Label38.Text = 20


                Label39.Text = 21


                Label40.Text = 22


                Label41.Text = 23


                Label42.Text = 24


                Label43.Text = 25


                Label44.Text = 26


                Label45.Text = 27


                Label46.Text = 28


                Label47.Text = 29


                Label48.Text = 30


                Label49.Text = 31


                Label50.Text = 32


                Label51.Text = 33


                Label52.Text = ""


                Label53.Text = ""


                Label54.Text = ""


                Label55.Text = ""


                Label56.Text = ""


                Label57.Text = ""


                Label58.Text = ""


            End If


            If TextBox11.Text = 34 Then


                Label18.Text = 0


                Label19.Text = 1


                Label20.Text = 2


                Label21.Text = 3


                Label22.Text = 4


                Label23.Text = 5


                Label24.Text = 6


                Label25.Text = 7


                Label26.Text = 8


                Label27.Text = 9


                Label28.Text = 10


                Label29.Text = 11


                Label30.Text = 12


                Label31.Text = 13


                Label32.Text = 14


                Label33.Text = 15


                Label34.Text = 16


                Label35.Text = 17


                Label36.Text = 18


                Label37.Text = 19


                Label38.Text = 20


                Label39.Text = 21


                Label40.Text = 22


                Label41.Text = 23


                Label42.Text = 24


                Label43.Text = 25


                Label44.Text = 26


                Label45.Text = 27


                Label46.Text = 28


                Label47.Text = 29


                Label48.Text = 30


                Label49.Text = 31


                Label50.Text = 32


                Label51.Text = 33


                Label52.Text = 34


                Label53.Text = ""


                Label54.Text = ""


                Label55.Text = ""


                Label56.Text = ""


                Label57.Text = ""


                Label58.Text = ""


            End If


            If TextBox11.Text = 35 Then


                Label18.Text = 0


                Label19.Text = 1


                Label20.Text = 2


                Label21.Text = 3


                Label22.Text = 4


                Label23.Text = 5


                Label24.Text = 6


                Label25.Text = 7


                Label26.Text = 8


                Label27.Text = 9


                Label28.Text = 10


                Label29.Text = 11


                Label30.Text = 12


                Label31.Text = 13


                Label32.Text = 14


                Label33.Text = 15


                Label34.Text = 16


                Label35.Text = 17


                Label36.Text = 18


                Label37.Text = 19


                Label38.Text = 20


                Label39.Text = 21


                Label40.Text = 22


                Label41.Text = 23


                Label42.Text = 24


                Label43.Text = 25


                Label44.Text = 26


                Label45.Text = 27


                Label46.Text = 28


                Label47.Text = 29


                Label48.Text = 30


                Label49.Text = 31


                Label50.Text = 32


                Label51.Text = 33


                Label52.Text = 34


                Label53.Text = 35


                Label54.Text = ""


                Label55.Text = ""


                Label56.Text = ""


                Label57.Text = ""


                Label58.Text = ""


            End If


            If TextBox11.Text = 36 Then


                Label18.Text = 0


                Label19.Text = 1


                Label20.Text = 2


                Label21.Text = 3


                Label22.Text = 4


                Label23.Text = 5


                Label24.Text = 6


                Label25.Text = 7


                Label26.Text = 8


                Label27.Text = 9


                Label28.Text = 10


                Label29.Text = 11


                Label30.Text = 12


                Label31.Text = 13


                Label32.Text = 14


                Label33.Text = 15


                Label34.Text = 16


                Label35.Text = 17


                Label36.Text = 18


                Label37.Text = 19


                Label38.Text = 20


                Label39.Text = 21


                Label40.Text = 22


                Label41.Text = 23


                Label42.Text = 24


                Label43.Text = 25


                Label44.Text = 26


                Label45.Text = 27


                Label46.Text = 28


                Label47.Text = 29


                Label48.Text = 30


                Label49.Text = 31


                Label50.Text = 32


                Label51.Text = 33


                Label52.Text = 34


                Label53.Text = 35


                Label54.Text = 36


                Label55.Text = ""


                Label56.Text = ""


                Label57.Text = ""


                Label58.Text = ""


            End If


            If TextBox11.Text = 37 Then


                Label18.Text = 0


                Label19.Text = 1


                Label20.Text = 2


                Label21.Text = 3


                Label22.Text = 4


                Label23.Text = 5


                Label24.Text = 6


                Label25.Text = 7


                Label26.Text = 8


                Label27.Text = 9


                Label28.Text = 10


                Label29.Text = 11


                Label30.Text = 12


                Label31.Text = 13


                Label32.Text = 14


                Label33.Text = 15


                Label34.Text = 16


                Label35.Text = 17


                Label36.Text = 18


                Label37.Text = 19


                Label38.Text = 20


                Label39.Text = 21


                Label40.Text = 22


                Label41.Text = 23


                Label42.Text = 24


                Label43.Text = 25


                Label44.Text = 26


                Label45.Text = 27


                Label46.Text = 28


                Label47.Text = 29


                Label48.Text = 30


                Label49.Text = 31


                Label50.Text = 32


                Label51.Text = 33


                Label52.Text = 34


                Label53.Text = 35


                Label54.Text = 36


                Label55.Text = 37


                Label56.Text = ""


                Label57.Text = ""


                Label58.Text = ""


            End If


            If TextBox11.Text = 38 Then


                Label18.Text = 0


                Label19.Text = 1


                Label20.Text = 2


                Label21.Text = 3


                Label22.Text = 4


                Label23.Text = 5


                Label24.Text = 6


                Label25.Text = 7


                Label26.Text = 8


                Label27.Text = 9


                Label28.Text = 10


                Label29.Text = 11


                Label30.Text = 12


                Label31.Text = 13


                Label32.Text = 14


                Label33.Text = 15


                Label34.Text = 16


                Label35.Text = 17


                Label36.Text = 18


                Label37.Text = 19


                Label38.Text = 20


                Label39.Text = 21


                Label40.Text = 22


                Label41.Text = 23


                Label42.Text = 24


                Label43.Text = 25


                Label44.Text = 26


                Label45.Text = 27


                Label46.Text = 28


                Label47.Text = 29


                Label48.Text = 30


                Label49.Text = 31


                Label50.Text = 32


                Label51.Text = 33


                Label52.Text = 34


                Label53.Text = 35


                Label54.Text = 36


                Label55.Text = 37


                Label56.Text = 38


                Label57.Text = ""


                Label58.Text = ""


            End If


            If TextBox11.Text = 39 Then


                Label18.Text = 0


                Label19.Text = 1


                Label20.Text = 2


                Label21.Text = 3


                Label22.Text = 4


                Label23.Text = 5


                Label24.Text = 6


                Label25.Text = 7


                Label26.Text = 8


                Label27.Text = 9


                Label28.Text = 10


                Label29.Text = 11


                Label30.Text = 12


                Label31.Text = 13


                Label32.Text = 14


                Label33.Text = 15


                Label34.Text = 16


                Label35.Text = 17


                Label36.Text = 18


                Label37.Text = 19


                Label38.Text = 20


                Label39.Text = 21


                Label40.Text = 22


                Label41.Text = 23


                Label42.Text = 24


                Label43.Text = 25


                Label44.Text = 26


                Label45.Text = 27


                Label46.Text = 28


                Label47.Text = 29


                Label48.Text = 30


                Label49.Text = 31


                Label50.Text = 32


                Label51.Text = 33


                Label52.Text = 34


                Label53.Text = 35


                Label54.Text = 36


                Label55.Text = 37


                Label56.Text = 38


                Label57.Text = 39


                Label58.Text = ""


            End If


            If TextBox11.Text = 40 Then


                Label18.Text = 0


                Label19.Text = 1


                Label20.Text = 2


                Label21.Text = 3


                Label22.Text = 4


                Label23.Text = 5


                Label24.Text = 6


                Label25.Text = 7


                Label26.Text = 8


                Label27.Text = 9


                Label28.Text = 10


                Label29.Text = 11


                Label30.Text = 12


                Label31.Text = 13


                Label32.Text = 14


                Label33.Text = 15


                Label34.Text = 16


                Label35.Text = 17


                Label36.Text = 18


                Label37.Text = 19


                Label38.Text = 20


                Label39.Text = 21


                Label40.Text = 22


                Label41.Text = 23


                Label42.Text = 24


                Label43.Text = 25


                Label44.Text = 26


                Label45.Text = 27


                Label46.Text = 28


                Label47.Text = 29


                Label48.Text = 30


                Label49.Text = 31


                Label50.Text = 32


                Label51.Text = 33


                Label52.Text = 34


                Label53.Text = 35


                Label54.Text = 36


                Label55.Text = 37


                Label56.Text = 38


                Label57.Text = 39


                Label58.Text = 40


            End If


        End If


        If ComboBox4.Visible = True Then


            If TextBox11.Text = 26 Then


                Label18.Text = 0


                Label19.Text = 1


                Label20.Text = 2


                Label21.Text = 3


                Label22.Text = 4


                Label23.Text = 5


                Label24.Text = 6


                Label25.Text = 7


                Label26.Text = 8


                Label27.Text = 9


                Label28.Text = 10


                Label29.Text = 11


                Label30.Text = 12


                Label31.Text = 13


                Label32.Text = 14


                Label33.Text = 15


                Label34.Text = 16


                Label35.Text = 17


                Label36.Text = 18


                Label37.Text = 19


                Label38.Text = 20


                Label39.Text = 21


                Label40.Text = 22


                Label41.Text = 23


                Label42.Text = 24


                Label43.Text = 25


                Label44.Text = 26


                Label45.Text = ""


                Label46.Text = ""


                Label47.Text = ""


                Label48.Text = ""


                Label49.Text = ""


                Label50.Text = ""


                Label51.Text = ""


                Label52.Text = ""


                Label53.Text = ""


                Label54.Text = ""


                Label55.Text = ""


                Label56.Text = ""


                Label57.Text = ""


                Label58.Text = ""



            End If


            If TextBox11.Text = 27 Then


                Label18.Text = 0


                Label19.Text = 1


                Label20.Text = 2


                Label21.Text = 3


                Label22.Text = 4


                Label23.Text = 5


                Label24.Text = 6


                Label25.Text = 7


                Label26.Text = 8


                Label27.Text = 9


                Label28.Text = 10


                Label29.Text = 11


                Label30.Text = 12


                Label31.Text = 13


                Label32.Text = 14


                Label33.Text = 15


                Label34.Text = 16


                Label35.Text = 17


                Label36.Text = 18


                Label37.Text = 19


                Label38.Text = 20


                Label39.Text = 21


                Label40.Text = 22


                Label41.Text = 23


                Label42.Text = 24


                Label43.Text = 25


                Label44.Text = 26


                Label45.Text = 27


                Label46.Text = ""


                Label47.Text = ""


                Label48.Text = ""


                Label49.Text = ""


                Label50.Text = ""


                Label51.Text = ""


                Label52.Text = ""


                Label53.Text = ""


                Label54.Text = ""


                Label55.Text = ""


                Label56.Text = ""


                Label57.Text = ""


                Label58.Text = ""


            End If


            If TextBox11.Text = 28 Then


                Label18.Text = 0


                Label19.Text = 1


                Label20.Text = 2


                Label21.Text = 3


                Label22.Text = 4


                Label23.Text = 5


                Label24.Text = 6


                Label25.Text = 7


                Label26.Text = 8


                Label27.Text = 9


                Label28.Text = 10


                Label29.Text = 11


                Label30.Text = 12


                Label31.Text = 13


                Label32.Text = 14


                Label33.Text = 15


                Label34.Text = 16


                Label35.Text = 17


                Label36.Text = 18


                Label37.Text = 19


                Label38.Text = 20


                Label39.Text = 21


                Label40.Text = 22


                Label41.Text = 23


                Label42.Text = 24


                Label43.Text = 25


                Label44.Text = 26


                Label45.Text = 27


                Label46.Text = 28


                Label47.Text = ""


                Label48.Text = ""


                Label49.Text = ""


                Label50.Text = ""


                Label51.Text = ""


                Label52.Text = ""


                Label53.Text = ""


                Label54.Text = ""


                Label55.Text = ""


                Label56.Text = ""


                Label57.Text = ""


                Label58.Text = ""


            End If


            If TextBox11.Text = 29 Then


                Label18.Text = 0


                Label19.Text = 1


                Label20.Text = 2


                Label21.Text = 3


                Label22.Text = 4


                Label23.Text = 5


                Label24.Text = 6


                Label25.Text = 7


                Label26.Text = 8


                Label27.Text = 9


                Label28.Text = 10


                Label29.Text = 11


                Label30.Text = 12


                Label31.Text = 13


                Label32.Text = 14


                Label33.Text = 15


                Label34.Text = 16


                Label35.Text = 17


                Label36.Text = 18


                Label37.Text = 19


                Label38.Text = 20


                Label39.Text = 21


                Label40.Text = 22


                Label41.Text = 23


                Label42.Text = 24


                Label43.Text = 25


                Label44.Text = 26


                Label45.Text = 27


                Label46.Text = 28


                Label47.Text = 29


                Label48.Text = ""


                Label49.Text = ""


                Label50.Text = ""


                Label51.Text = ""


                Label52.Text = ""


                Label53.Text = ""


                Label54.Text = ""


                Label55.Text = ""


                Label56.Text = ""


                Label57.Text = ""


                Label58.Text = ""


            End If


            If TextBox11.Text = 30 Then


                Label18.Text = 0


                Label19.Text = 1


                Label20.Text = 2


                Label21.Text = 3


                Label22.Text = 4


                Label23.Text = 5


                Label24.Text = 6


                Label25.Text = 7


                Label26.Text = 8


                Label27.Text = 9


                Label28.Text = 10


                Label29.Text = 11


                Label30.Text = 12


                Label31.Text = 13


                Label32.Text = 14


                Label33.Text = 15


                Label34.Text = 16


                Label35.Text = 17


                Label36.Text = 18


                Label37.Text = 19


                Label38.Text = 20


                Label39.Text = 21


                Label40.Text = 22


                Label41.Text = 23


                Label42.Text = 24


                Label43.Text = 25


                Label44.Text = 26


                Label45.Text = 27


                Label46.Text = 28


                Label47.Text = 29


                Label48.Text = 30


                Label49.Text = ""


                Label50.Text = ""


                Label51.Text = ""


                Label52.Text = ""


                Label53.Text = ""


                Label54.Text = ""


                Label55.Text = ""


                Label56.Text = ""


                Label57.Text = ""


                Label58.Text = ""


            End If


            If TextBox11.Text = 31 Then


                Label18.Text = 0


                Label19.Text = 1


                Label20.Text = 2


                Label21.Text = 3


                Label22.Text = 4


                Label23.Text = 5


                Label24.Text = 6


                Label25.Text = 7


                Label26.Text = 8


                Label27.Text = 9


                Label28.Text = 10


                Label29.Text = 11


                Label30.Text = 12


                Label31.Text = 13


                Label32.Text = 14


                Label33.Text = 15


                Label34.Text = 16


                Label35.Text = 17


                Label36.Text = 18


                Label37.Text = 19


                Label38.Text = 20


                Label39.Text = 21


                Label40.Text = 22


                Label41.Text = 23


                Label42.Text = 24


                Label43.Text = 25


                Label44.Text = 26


                Label45.Text = 27


                Label46.Text = 28


                Label47.Text = 29


                Label48.Text = 30


                Label49.Text = 31


                Label50.Text = ""


                Label51.Text = ""


                Label52.Text = ""


                Label53.Text = ""


                Label54.Text = ""


                Label55.Text = ""


                Label56.Text = ""


                Label57.Text = ""


                Label58.Text = ""


            End If


            If TextBox11.Text = 32 Then


                Label18.Text = 0


                Label19.Text = 1


                Label20.Text = 2


                Label21.Text = 3


                Label22.Text = 4


                Label23.Text = 5


                Label24.Text = 6


                Label25.Text = 7


                Label26.Text = 8


                Label27.Text = 9


                Label28.Text = 10


                Label29.Text = 11


                Label30.Text = 12


                Label31.Text = 13


                Label32.Text = 14


                Label33.Text = 15


                Label34.Text = 16


                Label35.Text = 17


                Label36.Text = 18


                Label37.Text = 19


                Label38.Text = 20


                Label39.Text = 21


                Label40.Text = 22


                Label41.Text = 23


                Label42.Text = 24


                Label43.Text = 25


                Label44.Text = 26


                Label45.Text = 27


                Label46.Text = 28


                Label47.Text = 29


                Label48.Text = 30


                Label49.Text = 31


                Label50.Text = 32


                Label51.Text = ""


                Label52.Text = ""


                Label53.Text = ""


                Label54.Text = ""


                Label55.Text = ""


                Label56.Text = ""


                Label57.Text = ""


                Label58.Text = ""


            End If


            If TextBox11.Text = 33 Then


                Label18.Text = 0


                Label19.Text = 1


                Label20.Text = 2


                Label21.Text = 3


                Label22.Text = 4


                Label23.Text = 5


                Label24.Text = 6


                Label25.Text = 7


                Label26.Text = 8


                Label27.Text = 9


                Label28.Text = 10


                Label29.Text = 11


                Label30.Text = 12


                Label31.Text = 13


                Label32.Text = 14


                Label33.Text = 15


                Label34.Text = 16


                Label35.Text = 17


                Label36.Text = 18


                Label37.Text = 19


                Label38.Text = 20


                Label39.Text = 21


                Label40.Text = 22


                Label41.Text = 23


                Label42.Text = 24


                Label43.Text = 25


                Label44.Text = 26


                Label45.Text = 27


                Label46.Text = 28


                Label47.Text = 29


                Label48.Text = 30


                Label49.Text = 31


                Label50.Text = 32


                Label51.Text = 33


                Label52.Text = ""


                Label53.Text = ""


                Label54.Text = ""


                Label55.Text = ""


                Label56.Text = ""


                Label57.Text = ""


                Label58.Text = ""


            End If


            If TextBox11.Text = 34 Then


                Label18.Text = 0


                Label19.Text = 1


                Label20.Text = 2


                Label21.Text = 3


                Label22.Text = 4


                Label23.Text = 5


                Label24.Text = 6


                Label25.Text = 7


                Label26.Text = 8


                Label27.Text = 9


                Label28.Text = 10


                Label29.Text = 11


                Label30.Text = 12


                Label31.Text = 13


                Label32.Text = 14


                Label33.Text = 15


                Label34.Text = 16


                Label35.Text = 17


                Label36.Text = 18


                Label37.Text = 19


                Label38.Text = 20


                Label39.Text = 21


                Label40.Text = 22


                Label41.Text = 23


                Label42.Text = 24


                Label43.Text = 25


                Label44.Text = 26


                Label45.Text = 27


                Label46.Text = 28


                Label47.Text = 29


                Label48.Text = 30


                Label49.Text = 31


                Label50.Text = 32


                Label51.Text = 33


                Label52.Text = 34


                Label53.Text = ""


                Label54.Text = ""


                Label55.Text = ""


                Label56.Text = ""


                Label57.Text = ""


                Label58.Text = ""


            End If


            If TextBox11.Text = 35 Then


                Label18.Text = 0


                Label19.Text = 1


                Label20.Text = 2


                Label21.Text = 3


                Label22.Text = 4


                Label23.Text = 5


                Label24.Text = 6


                Label25.Text = 7


                Label26.Text = 8


                Label27.Text = 9


                Label28.Text = 10


                Label29.Text = 11


                Label30.Text = 12


                Label31.Text = 13


                Label32.Text = 14


                Label33.Text = 15


                Label34.Text = 16


                Label35.Text = 17


                Label36.Text = 18


                Label37.Text = 19


                Label38.Text = 20


                Label39.Text = 21


                Label40.Text = 22


                Label41.Text = 23


                Label42.Text = 24


                Label43.Text = 25


                Label44.Text = 26


                Label45.Text = 27


                Label46.Text = 28


                Label47.Text = 29


                Label48.Text = 30


                Label49.Text = 31


                Label50.Text = 32


                Label51.Text = 33


                Label52.Text = 34


                Label53.Text = 35


                Label54.Text = ""


                Label55.Text = ""


                Label56.Text = ""


                Label57.Text = ""


                Label58.Text = ""


            End If


            If TextBox11.Text = 36 Then


                Label18.Text = 0


                Label19.Text = 1


                Label20.Text = 2


                Label21.Text = 3


                Label22.Text = 4


                Label23.Text = 5


                Label24.Text = 6


                Label25.Text = 7


                Label26.Text = 8


                Label27.Text = 9


                Label28.Text = 10


                Label29.Text = 11


                Label30.Text = 12


                Label31.Text = 13


                Label32.Text = 14


                Label33.Text = 15


                Label34.Text = 16


                Label35.Text = 17


                Label36.Text = 18


                Label37.Text = 19


                Label38.Text = 20


                Label39.Text = 21


                Label40.Text = 22


                Label41.Text = 23


                Label42.Text = 24


                Label43.Text = 25


                Label44.Text = 26


                Label45.Text = 27


                Label46.Text = 28


                Label47.Text = 29


                Label48.Text = 30


                Label49.Text = 31


                Label50.Text = 32


                Label51.Text = 33


                Label52.Text = 34


                Label53.Text = 35


                Label54.Text = 36


                Label55.Text = ""


                Label56.Text = ""


                Label57.Text = ""


                Label58.Text = ""


            End If


            If TextBox11.Text = 37 Then


                Label18.Text = 0


                Label19.Text = 1


                Label20.Text = 2


                Label21.Text = 3


                Label22.Text = 4


                Label23.Text = 5


                Label24.Text = 6


                Label25.Text = 7


                Label26.Text = 8


                Label27.Text = 9


                Label28.Text = 10


                Label29.Text = 11


                Label30.Text = 12


                Label31.Text = 13


                Label32.Text = 14


                Label33.Text = 15


                Label34.Text = 16


                Label35.Text = 17


                Label36.Text = 18


                Label37.Text = 19


                Label38.Text = 20


                Label39.Text = 21


                Label40.Text = 22


                Label41.Text = 23


                Label42.Text = 24


                Label43.Text = 25


                Label44.Text = 26


                Label45.Text = 27


                Label46.Text = 28


                Label47.Text = 29


                Label48.Text = 30


                Label49.Text = 31


                Label50.Text = 32


                Label51.Text = 33


                Label52.Text = 34


                Label53.Text = 35


                Label54.Text = 36


                Label55.Text = 37


                Label56.Text = ""


                Label57.Text = ""


                Label58.Text = ""


            End If


            If TextBox11.Text = 38 Then


                Label18.Text = 0


                Label19.Text = 1


                Label20.Text = 2


                Label21.Text = 3


                Label22.Text = 4


                Label23.Text = 5


                Label24.Text = 6


                Label25.Text = 7


                Label26.Text = 8


                Label27.Text = 9


                Label28.Text = 10


                Label29.Text = 11


                Label30.Text = 12


                Label31.Text = 13


                Label32.Text = 14


                Label33.Text = 15


                Label34.Text = 16


                Label35.Text = 17


                Label36.Text = 18


                Label37.Text = 19


                Label38.Text = 20


                Label39.Text = 21


                Label40.Text = 22


                Label41.Text = 23


                Label42.Text = 24


                Label43.Text = 25


                Label44.Text = 26


                Label45.Text = 27


                Label46.Text = 28


                Label47.Text = 29


                Label48.Text = 30


                Label49.Text = 31


                Label50.Text = 32


                Label51.Text = 33


                Label52.Text = 34


                Label53.Text = 35


                Label54.Text = 36


                Label55.Text = 37


                Label56.Text = 38


                Label57.Text = ""


                Label58.Text = ""


            End If


            If TextBox11.Text = 39 Then


                Label18.Text = 0


                Label19.Text = 1


                Label20.Text = 2


                Label21.Text = 3


                Label22.Text = 4


                Label23.Text = 5


                Label24.Text = 6


                Label25.Text = 7


                Label26.Text = 8


                Label27.Text = 9


                Label28.Text = 10


                Label29.Text = 11


                Label30.Text = 12


                Label31.Text = 13


                Label32.Text = 14


                Label33.Text = 15


                Label34.Text = 16


                Label35.Text = 17


                Label36.Text = 18


                Label37.Text = 19


                Label38.Text = 20


                Label39.Text = 21


                Label40.Text = 22


                Label41.Text = 23


                Label42.Text = 24


                Label43.Text = 25


                Label44.Text = 26


                Label45.Text = 27


                Label46.Text = 28


                Label47.Text = 29


                Label48.Text = 30


                Label49.Text = 31


                Label50.Text = 32


                Label51.Text = 33


                Label52.Text = 34


                Label53.Text = 35


                Label54.Text = 36


                Label55.Text = 37


                Label56.Text = 38


                Label57.Text = 39


                Label58.Text = ""


            End If


            If TextBox11.Text = 40 Then


                Label18.Text = 0


                Label19.Text = 1


                Label20.Text = 2


                Label21.Text = 3


                Label22.Text = 4


                Label23.Text = 5


                Label24.Text = 6


                Label25.Text = 7


                Label26.Text = 8


                Label27.Text = 9


                Label28.Text = 10


                Label29.Text = 11


                Label30.Text = 12


                Label31.Text = 13


                Label32.Text = 14


                Label33.Text = 15


                Label34.Text = 16


                Label35.Text = 17


                Label36.Text = 18


                Label37.Text = 19


                Label38.Text = 20


                Label39.Text = 21


                Label40.Text = 22


                Label41.Text = 23


                Label42.Text = 24


                Label43.Text = 25


                Label44.Text = 26


                Label45.Text = 27


                Label46.Text = 28


                Label47.Text = 29


                Label48.Text = 30


                Label49.Text = 31


                Label50.Text = 32


                Label51.Text = 33


                Label52.Text = 34


                Label53.Text = 35


                Label54.Text = 36


                Label55.Text = 37


                Label56.Text = 38


                Label57.Text = 39


                Label58.Text = 40


            End If


        End If


    End Sub


    Private Sub Button5_Click(sender As Object, e As EventArgs) Handles Button5.Click


        Button1.Enabled = True


        Button9.Enabled = True


        If TextBox5.Text > 44 Then


            MsgBox("Seems your system's Microsoft Windows language is European. Please select the € symbol for the A value selection")


        End If



        If ComboBox1.Visible = True Then


            If ComboBox1.Text = "" Then


                MsgBox("Please select an A value")


                If TextBox6.Text = "" Then


                    MsgBox("Hey, you skipped clicking 3 buttons in front")


                    PictureBox4.Visible = False


                End If



            Else


                Dim sg As Single


                sg = TextBox6.Text * 0.41


                sg = Math.Round(sg, 1)


                TextBox4.Text = sg



                Panel6.Visible = True


                TextBox4.Visible = True


                Label106.Visible = True


                Label107.Visible = True


                Label105.Visible = True


                PictureBox12.Visible = True


                PictureBox11.Visible = True


                PictureBox10.Visible = True


                Label166.Visible = True


                Label145.Visible = True


                Label146.Visible = True


                Label147.Visible = True


                Label148.Visible = True


                Label149.Visible = True


                Label150.Visible = True


                Label151.Visible = True


                Label152.Visible = True


                Label153.Visible = True


                Label154.Visible = True


                Label155.Visible = True


                Label156.Visible = True


                Label157.Visible = True


                Label158.Visible = True


                Label159.Visible = True


                Label160.Visible = True


                Label161.Visible = True


                Label162.Visible = True


                Label163.Visible = True


                Label164.Visible = True


                Label165.Visible = True



                If TextBox11.Text = 25 Then


                    PictureBox12.Image = My.Resources._7_0


                    Label99.Text = ""


                    Label98.Text = ""


                    Label97.Text = ""


                    Label96.Text = ""


                    Label95.Text = ""


                    Label94.Text = ""


                    Label93.Text = ""


                    Label92.Text = ""


                    Label91.Text = ""


                    Label90.Text = ""


                    Label89.Text = ""


                    Label88.Text = ""


                    Label87.Text = ""


                    Label86.Text = ""


                    Label85.Text = ""


                    Label84.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((25 - 25) / 25))) - 0.88) / 1000), 2)


                    Label83.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((25 - 24) / 25))) - 0.88) / 1000), 2)


                    Label82.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((25 - 23) / 25))) - 0.88) / 1000), 2)


                    Label81.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((25 - 22) / 25))) - 0.88) / 1000), 2)


                    Label80.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((25 - 21) / 25))) - 0.88) / 1000), 2)


                    Label79.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((25 - 20) / 25))) - 0.88) / 1000), 2)


                    Label78.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((25 - 19) / 25))) - 0.88) / 1000), 2)


                    Label77.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((25 - 18) / 25))) - 0.88) / 1000), 2)


                    Label76.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((25 - 17) / 25))) - 0.88) / 1000), 2)


                    Label75.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((25 - 16) / 25))) - 0.88) / 1000), 2)


                    Label74.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((25 - 15) / 25))) - 0.88) / 1000), 2)


                    Label73.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((25 - 14) / 25))) - 0.88) / 1000), 2)


                    Label72.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((25 - 13) / 25))) - 0.88) / 1000), 2)


                    Label71.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((25 - 12) / 25))) - 0.88) / 1000), 2)


                    Label70.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((25 - 11) / 25))) - 0.88) / 1000), 2)


                    Label69.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((25 - 10) / 25))) - 0.88) / 1000), 2)


                    Label68.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((25 - 9) / 25))) - 0.88) / 1000), 2)


                    Label67.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((25 - 8) / 25))) - 0.88) / 1000), 2)


                    Label66.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((25 - 7) / 25))) - 0.88) / 1000), 2)


                    Label65.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((25 - 6) / 25))) - 0.88) / 1000), 2)


                    Label64.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((25 - 5) / 25))) - 0.88) / 1000), 2)


                    Label63.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((25 - 4) / 25))) - 0.88) / 1000), 2)


                    Label62.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((25 - 3) / 25))) - 0.88) / 1000), 2)


                    Label61.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((25 - 2) / 25))) - 0.88) / 1000), 2)


                    Label60.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((25 - 1) / 25))) - 0.88) / 1000), 2)


                    Label59.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((25 - 0) / 25))) - 0.88) / 1000), 2)


                End If



                If TextBox11.Text = 26 Then


                    PictureBox12.Image = My.Resources._7_0


                    Label99.Text = ""


                    Label98.Text = ""


                    Label97.Text = ""


                    Label96.Text = ""


                    Label95.Text = ""


                    Label94.Text = ""


                    Label93.Text = ""


                    Label92.Text = ""


                    Label91.Text = ""


                    Label90.Text = ""


                    Label89.Text = ""


                    Label88.Text = ""


                    Label87.Text = ""


                    Label86.Text = ""


                    Label85.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((26 - 26) / 26))) - 0.88) / 1000), 2)


                    Label84.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((26 - 25) / 26))) - 0.88) / 1000), 2)


                    Label83.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((26 - 24) / 26))) - 0.88) / 1000), 2)


                    Label82.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((26 - 23) / 26))) - 0.88) / 1000), 2)


                    Label81.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((26 - 22) / 26))) - 0.88) / 1000), 2)


                    Label80.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((26 - 21) / 26))) - 0.88) / 1000), 2)


                    Label79.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((26 - 20) / 26))) - 0.88) / 1000), 2)


                    Label78.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((26 - 19) / 26))) - 0.88) / 1000), 2)


                    Label77.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((26 - 18) / 26))) - 0.88) / 1000), 2)


                    Label76.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((26 - 17) / 26))) - 0.88) / 1000), 2)


                    Label75.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((26 - 16) / 26))) - 0.88) / 1000), 2)


                    Label74.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((26 - 15) / 26))) - 0.88) / 1000), 2)


                    Label73.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((26 - 14) / 26))) - 0.88) / 1000), 2)


                    Label72.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((26 - 13) / 26))) - 0.88) / 1000), 2)


                    Label71.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((26 - 12) / 26))) - 0.88) / 1000), 2)


                    Label70.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((26 - 11) / 26))) - 0.88) / 1000), 2)


                    Label69.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((26 - 10) / 26))) - 0.88) / 1000), 2)


                    Label68.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((26 - 9) / 26))) - 0.88) / 1000), 2)


                    Label67.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((26 - 8) / 26))) - 0.88) / 1000), 2)


                    Label66.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((26 - 7) / 26))) - 0.88) / 1000), 2)


                    Label65.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((26 - 6) / 26))) - 0.88) / 1000), 2)


                    Label64.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((26 - 5) / 26))) - 0.88) / 1000), 2)


                    Label63.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((26 - 4) / 26))) - 0.88) / 1000), 2)


                    Label62.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((26 - 3) / 26))) - 0.88) / 1000), 2)


                    Label61.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((26 - 2) / 26))) - 0.88) / 1000), 2)


                    Label60.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((26 - 1) / 26))) - 0.88) / 1000), 2)


                    Label59.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((26 - 0) / 26))) - 0.88) / 1000), 2)


                End If



                If TextBox11.Text = 27 Then


                    PictureBox12.Image = My.Resources._7_2


                    Label99.Text = ""


                    Label98.Text = ""


                    Label97.Text = ""


                    Label96.Text = ""


                    Label95.Text = ""


                    Label94.Text = ""


                    Label93.Text = ""


                    Label92.Text = ""


                    Label91.Text = ""


                    Label90.Text = ""


                    Label89.Text = ""


                    Label88.Text = ""


                    Label87.Text = ""


                    Label86.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 27) / 27))) - 0.88) / 1000), 2)


                    Label85.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 26) / 27))) - 0.88) / 1000), 2)


                    Label84.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 25) / 27))) - 0.88) / 1000), 2)


                    Label83.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 24) / 27))) - 0.88) / 1000), 2)


                    Label82.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 23) / 27))) - 0.88) / 1000), 2)


                    Label81.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 22) / 27))) - 0.88) / 1000), 2)


                    Label80.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 21) / 27))) - 0.88) / 1000), 2)


                    Label79.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 20) / 27))) - 0.88) / 1000), 2)


                    Label78.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 19) / 27))) - 0.88) / 1000), 2)


                    Label77.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 18) / 27))) - 0.88) / 1000), 2)


                    Label76.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 17) / 27))) - 0.88) / 1000), 2)


                    Label75.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 16) / 27))) - 0.88) / 1000), 2)


                    Label74.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 15) / 27))) - 0.88) / 1000), 2)


                    Label73.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 14) / 27))) - 0.88) / 1000), 2)


                    Label72.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 13) / 27))) - 0.88) / 1000), 2)


                    Label71.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 12) / 27))) - 0.88) / 1000), 2)


                    Label70.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 11) / 27))) - 0.88) / 1000), 2)


                    Label69.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 10) / 27))) - 0.88) / 1000), 2)


                    Label68.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 9) / 27))) - 0.88) / 1000), 2)


                    Label67.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 8) / 27))) - 0.88) / 1000), 2)


                    Label66.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 7) / 27))) - 0.88) / 1000), 2)


                    Label65.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 6) / 27))) - 0.88) / 1000), 2)


                    Label64.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 5) / 27))) - 0.88) / 1000), 2)


                    Label63.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 4) / 27))) - 0.88) / 1000), 2)


                    Label62.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 3) / 27))) - 0.88) / 1000), 2)


                    Label61.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 2) / 27))) - 0.88) / 1000), 2)


                    Label60.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 1) / 27))) - 0.88) / 1000), 2)


                    Label59.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 0) / 27))) - 0.88) / 1000), 2)


                End If



                If TextBox11.Text = 28 Then


                    PictureBox12.Image = My.Resources._7_4


                    Label99.Text = ""


                    Label98.Text = ""


                    Label97.Text = ""


                    Label96.Text = ""


                    Label95.Text = ""


                    Label94.Text = ""


                    Label93.Text = ""


                    Label92.Text = ""


                    Label91.Text = ""


                    Label90.Text = ""


                    Label89.Text = ""


                    Label88.Text = ""


                    Label87.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 28) / 28))) - 0.88) / 1000), 2)


                    Label86.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 27) / 28))) - 0.88) / 1000), 2)


                    Label85.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 26) / 28))) - 0.88) / 1000), 2)


                    Label84.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 25) / 28))) - 0.88) / 1000), 2)


                    Label83.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 24) / 28))) - 0.88) / 1000), 2)


                    Label82.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 23) / 28))) - 0.88) / 1000), 2)


                    Label81.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 22) / 28))) - 0.88) / 1000), 2)


                    Label80.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 21) / 28))) - 0.88) / 1000), 2)


                    Label79.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 20) / 28))) - 0.88) / 1000), 2)


                    Label78.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 19) / 28))) - 0.88) / 1000), 2)


                    Label77.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 18) / 28))) - 0.88) / 1000), 2)


                    Label76.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 17) / 28))) - 0.88) / 1000), 2)


                    Label75.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 16) / 28))) - 0.88) / 1000), 2)


                    Label74.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 15) / 28))) - 0.88) / 1000), 2)


                    Label73.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 14) / 28))) - 0.88) / 1000), 2)


                    Label72.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 13) / 28))) - 0.88) / 1000), 2)


                    Label71.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 12) / 28))) - 0.88) / 1000), 2)


                    Label70.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 11) / 28))) - 0.88) / 1000), 2)


                    Label69.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 10) / 28))) - 0.88) / 1000), 2)


                    Label68.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 9) / 28))) - 0.88) / 1000), 2)


                    Label67.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 8) / 28))) - 0.88) / 1000), 2)


                    Label66.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 7) / 28))) - 0.88) / 1000), 2)


                    Label65.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 6) / 28))) - 0.88) / 1000), 2)


                    Label64.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 5) / 28))) - 0.88) / 1000), 2)


                    Label63.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 4) / 28))) - 0.88) / 1000), 2)


                    Label62.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 3) / 28))) - 0.88) / 1000), 2)


                    Label61.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 2) / 28))) - 0.88) / 1000), 2)


                    Label60.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 1) / 28))) - 0.88) / 1000), 2)


                    Label59.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 0) / 28))) - 0.88) / 1000), 2)


                End If



                If TextBox11.Text = 29 Then


                    PictureBox12.Image = My.Resources._7_6


                    Label99.Text = ""


                    Label98.Text = ""


                    Label97.Text = ""


                    Label96.Text = ""


                    Label95.Text = ""


                    Label94.Text = ""


                    Label93.Text = ""


                    Label92.Text = ""


                    Label91.Text = ""


                    Label90.Text = ""


                    Label89.Text = ""


                    Label88.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 29) / 29))) - 0.88) / 1000), 2)


                    Label87.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 28) / 29))) - 0.88) / 1000), 2)


                    Label85.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 26) / 29))) - 0.88) / 1000), 2)


                    Label84.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 25) / 29))) - 0.88) / 1000), 2)


                    Label83.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 24) / 29))) - 0.88) / 1000), 2)


                    Label82.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 23) / 29))) - 0.88) / 1000), 2)


                    Label81.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 22) / 29))) - 0.88) / 1000), 2)


                    Label80.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 21) / 29))) - 0.88) / 1000), 2)


                    Label79.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 20) / 29))) - 0.88) / 1000), 2)


                    Label78.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 19) / 29))) - 0.88) / 1000), 2)


                    Label77.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 18) / 29))) - 0.88) / 1000), 2)


                    Label76.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 17) / 29))) - 0.88) / 1000), 2)


                    Label75.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 16) / 29))) - 0.88) / 1000), 2)


                    Label74.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 15) / 29))) - 0.88) / 1000), 2)


                    Label73.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 14) / 29))) - 0.88) / 1000), 2)


                    Label72.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 13) / 29))) - 0.88) / 1000), 2)


                    Label71.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 12) / 29))) - 0.88) / 1000), 2)


                    Label70.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 11) / 29))) - 0.88) / 1000), 2)


                    Label69.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 10) / 29))) - 0.88) / 1000), 2)


                    Label68.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 9) / 29))) - 0.88) / 1000), 2)


                    Label67.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 8) / 29))) - 0.88) / 1000), 2)


                    Label66.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 7) / 29))) - 0.88) / 1000), 2)


                    Label65.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 6) / 29))) - 0.88) / 1000), 2)


                    Label64.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 5) / 29))) - 0.88) / 1000), 2)


                    Label63.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 4) / 29))) - 0.88) / 1000), 2)


                    Label62.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 3) / 29))) - 0.88) / 1000), 2)


                    Label61.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 2) / 29))) - 0.88) / 1000), 2)


                    Label60.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 1) / 29))) - 0.88) / 1000), 2)


                    Label59.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 0) / 29))) - 0.88) / 1000), 2)


                End If



                If TextBox11.Text = 30 Then


                    PictureBox12.Image = My.Resources._7_8


                    Label99.Text = ""


                    Label98.Text = ""


                    Label97.Text = ""


                    Label96.Text = ""


                    Label95.Text = ""


                    Label94.Text = ""


                    Label93.Text = ""


                    Label92.Text = ""


                    Label91.Text = ""


                    Label90.Text = ""


                    Label89.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 30) / 30))) - 0.88) / 1000), 2)


                    Label88.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 29) / 30))) - 0.88) / 1000), 2)


                    Label87.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 28) / 30))) - 0.88) / 1000), 2)


                    Label86.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 27) / 30))) - 0.88) / 1000), 2)


                    Label85.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 26) / 30))) - 0.88) / 1000), 2)


                    Label84.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 25) / 30))) - 0.88) / 1000), 2)


                    Label83.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 24) / 30))) - 0.88) / 1000), 2)


                    Label82.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 23) / 30))) - 0.88) / 1000), 2)


                    Label81.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 22) / 30))) - 0.88) / 1000), 2)


                    Label80.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 21) / 30))) - 0.88) / 1000), 2)


                    Label79.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 20) / 30))) - 0.88) / 1000), 2)


                    Label78.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 19) / 30))) - 0.88) / 1000), 2)


                    Label77.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 18) / 30))) - 0.88) / 1000), 2)


                    Label76.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 17) / 30))) - 0.88) / 1000), 2)


                    Label75.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 16) / 30))) - 0.88) / 1000), 2)


                    Label74.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 15) / 30))) - 0.88) / 1000), 2)


                    Label73.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 14) / 30))) - 0.88) / 1000), 2)


                    Label72.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 13) / 30))) - 0.88) / 1000), 2)


                    Label71.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 12) / 30))) - 0.88) / 1000), 2)


                    Label70.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 11) / 30))) - 0.88) / 1000), 2)


                    Label69.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 10) / 30))) - 0.88) / 1000), 2)


                    Label68.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 9) / 30))) - 0.88) / 1000), 2)


                    Label67.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 8) / 30))) - 0.88) / 1000), 2)


                    Label66.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 7) / 30))) - 0.88) / 1000), 2)


                    Label65.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 6) / 30))) - 0.88) / 1000), 2)


                    Label64.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 5) / 30))) - 0.88) / 1000), 2)


                    Label63.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 4) / 30))) - 0.88) / 1000), 2)


                    Label62.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 3) / 30))) - 0.88) / 1000), 2)


                    Label61.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 2) / 30))) - 0.88) / 1000), 2)


                    Label60.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 1) / 30))) - 0.88) / 1000), 2)


                    Label59.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 0) / 30))) - 0.88) / 1000), 2)


                End If



                If TextBox11.Text = 31 Then


                    PictureBox12.Image = My.Resources._8_2


                    Label99.Text = ""


                    Label98.Text = ""


                    Label97.Text = ""


                    Label96.Text = ""


                    Label95.Text = ""


                    Label94.Text = ""


                    Label93.Text = ""


                    Label92.Text = ""


                    Label91.Text = ""


                    Label90.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 31) / 31))) - 0.88) / 1000), 2)


                    Label89.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 30) / 31))) - 0.88) / 1000), 2)


                    Label88.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 29) / 31))) - 0.88) / 1000), 2)


                    Label87.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 28) / 31))) - 0.88) / 1000), 2)


                    Label86.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 27) / 31))) - 0.88) / 1000), 2)


                    Label85.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 26) / 31))) - 0.88) / 1000), 2)


                    Label84.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 25) / 31))) - 0.88) / 1000), 2)


                    Label83.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 24) / 31))) - 0.88) / 1000), 2)


                    Label82.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 23) / 31))) - 0.88) / 1000), 2)


                    Label81.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 22) / 31))) - 0.88) / 1000), 2)


                    Label80.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 21) / 31))) - 0.88) / 1000), 2)


                    Label79.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 20) / 31))) - 0.88) / 1000), 2)


                    Label78.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 19) / 31))) - 0.88) / 1000), 2)


                    Label77.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 18) / 31))) - 0.88) / 1000), 2)


                    Label76.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 17) / 31))) - 0.88) / 1000), 2)


                    Label75.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 16) / 31))) - 0.88) / 1000), 2)


                    Label74.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 15) / 31))) - 0.88) / 1000), 2)


                    Label73.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 14) / 31))) - 0.88) / 1000), 2)


                    Label72.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 13) / 31))) - 0.88) / 1000), 2)


                    Label71.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 12) / 31))) - 0.88) / 1000), 2)


                    Label70.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 11) / 31))) - 0.88) / 1000), 2)


                    Label69.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 10) / 31))) - 0.88) / 1000), 2)


                    Label68.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 9) / 31))) - 0.88) / 1000), 2)


                    Label67.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 8) / 31))) - 0.88) / 1000), 2)


                    Label66.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 7) / 31))) - 0.88) / 1000), 2)


                    Label65.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 6) / 31))) - 0.88) / 1000), 2)


                    Label64.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 5) / 31))) - 0.88) / 1000), 2)


                    Label63.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 4) / 31))) - 0.88) / 1000), 2)


                    Label62.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 3) / 31))) - 0.88) / 1000), 2)


                    Label61.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 2) / 31))) - 0.88) / 1000), 2)


                    Label60.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 1) / 31))) - 0.88) / 1000), 2)


                    Label59.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 0) / 31))) - 0.88) / 1000), 2)


                End If



                If TextBox11.Text = 32 Then


                    PictureBox12.Image = My.Resources._8_6


                    Label99.Text = ""


                    Label98.Text = ""


                    Label97.Text = ""


                    Label96.Text = ""


                    Label95.Text = ""


                    Label94.Text = ""


                    Label93.Text = ""


                    Label92.Text = ""


                    Label91.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 32) / 32))) - 0.88) / 1000), 2)


                    Label90.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 31) / 32))) - 0.88) / 1000), 2)


                    Label89.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 30) / 32))) - 0.88) / 1000), 2)


                    Label88.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 29) / 32))) - 0.88) / 1000), 2)


                    Label87.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 28) / 32))) - 0.88) / 1000), 2)


                    Label86.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 27) / 32))) - 0.88) / 1000), 2)


                    Label85.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 26) / 32))) - 0.88) / 1000), 2)


                    Label84.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 25) / 32))) - 0.88) / 1000), 2)


                    Label83.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 24) / 32))) - 0.88) / 1000), 2)


                    Label82.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 23) / 32))) - 0.88) / 1000), 2)


                    Label81.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 22) / 32))) - 0.88) / 1000), 2)


                    Label80.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 21) / 32))) - 0.88) / 1000), 2)


                    Label79.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 20) / 32))) - 0.88) / 1000), 2)


                    Label78.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 19) / 32))) - 0.88) / 1000), 2)


                    Label77.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 18) / 32))) - 0.88) / 1000), 2)


                    Label76.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 17) / 32))) - 0.88) / 1000), 2)


                    Label75.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 16) / 32))) - 0.88) / 1000), 2)


                    Label74.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 15) / 32))) - 0.88) / 1000), 2)


                    Label73.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 14) / 32))) - 0.88) / 1000), 2)


                    Label72.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 13) / 32))) - 0.88) / 1000), 2)


                    Label71.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 12) / 32))) - 0.88) / 1000), 2)


                    Label70.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 11) / 32))) - 0.88) / 1000), 2)


                    Label69.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 10) / 32))) - 0.88) / 1000), 2)


                    Label68.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 9) / 32))) - 0.88) / 1000), 2)


                    Label67.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 8) / 32))) - 0.88) / 1000), 2)


                    Label66.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 7) / 32))) - 0.88) / 1000), 2)


                    Label65.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 6) / 32))) - 0.88) / 1000), 2)


                    Label64.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 5) / 32))) - 0.88) / 1000), 2)


                    Label63.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 4) / 32))) - 0.88) / 1000), 2)


                    Label62.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 3) / 32))) - 0.88) / 1000), 2)


                    Label61.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 2) / 32))) - 0.88) / 1000), 2)


                    Label60.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 1) / 32))) - 0.88) / 1000), 2)


                    Label59.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 0) / 32))) - 0.88) / 1000), 2)


                End If



                If TextBox11.Text = 33 Then


                    PictureBox12.Image = My.Resources._8_8


                    Label99.Text = ""


                    Label98.Text = ""


                    Label97.Text = ""


                    Label96.Text = ""


                    Label95.Text = ""


                    Label94.Text = ""


                    Label93.Text = ""


                    Label92.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 33) / 33))) - 0.88) / 1000), 2)


                    Label91.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 32) / 33))) - 0.88) / 1000), 2)


                    Label90.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 31) / 33))) - 0.88) / 1000), 2)


                    Label89.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 30) / 33))) - 0.88) / 1000), 2)


                    Label88.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 29) / 33))) - 0.88) / 1000), 2)


                    Label87.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 28) / 33))) - 0.88) / 1000), 2)


                    Label86.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 27) / 33))) - 0.88) / 1000), 2)


                    Label85.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 26) / 33))) - 0.88) / 1000), 2)


                    Label84.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 25) / 33))) - 0.88) / 1000), 2)


                    Label83.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 24) / 33))) - 0.88) / 1000), 2)


                    Label82.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 23) / 33))) - 0.88) / 1000), 2)


                    Label81.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 22) / 33))) - 0.88) / 1000), 2)


                    Label80.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 21) / 33))) - 0.88) / 1000), 2)


                    Label79.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 20) / 33))) - 0.88) / 1000), 2)


                    Label78.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 19) / 33))) - 0.88) / 1000), 2)


                    Label77.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 18) / 33))) - 0.88) / 1000), 2)


                    Label76.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 17) / 33))) - 0.88) / 1000), 2)


                    Label75.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 16) / 33))) - 0.88) / 1000), 2)


                    Label74.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 15) / 33))) - 0.88) / 1000), 2)


                    Label73.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 14) / 33))) - 0.88) / 1000), 2)


                    Label72.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 13) / 33))) - 0.88) / 1000), 2)


                    Label71.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 12) / 33))) - 0.88) / 1000), 2)


                    Label70.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 11) / 33))) - 0.88) / 1000), 2)


                    Label69.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 10) / 33))) - 0.88) / 1000), 2)


                    Label68.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 9) / 33))) - 0.88) / 1000), 2)


                    Label67.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 8) / 33))) - 0.88) / 1000), 2)


                    Label66.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 7) / 33))) - 0.88) / 1000), 2)


                    Label65.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 6) / 33))) - 0.88) / 1000), 2)


                    Label64.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 5) / 33))) - 0.88) / 1000), 2)


                    Label63.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 4) / 33))) - 0.88) / 1000), 2)


                    Label62.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 3) / 33))) - 0.88) / 1000), 2)


                    Label61.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 2) / 33))) - 0.88) / 1000), 2)


                    Label60.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 1) / 33))) - 0.88) / 1000), 2)


                    Label59.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 0) / 33))) - 0.88) / 1000), 2)


                End If



                If TextBox11.Text = 34 Then


                    PictureBox12.Image = My.Resources._9_0


                    Label99.Text = ""


                    Label98.Text = ""


                    Label97.Text = ""


                    Label96.Text = ""


                    Label95.Text = ""


                    Label94.Text = ""


                    Label93.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 34) / 34))) - 0.88) / 1000), 2)


                    Label92.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 33) / 34))) - 0.88) / 1000), 2)


                    Label91.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 32) / 34))) - 0.88) / 1000), 2)


                    Label90.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 31) / 34))) - 0.88) / 1000), 2)


                    Label89.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 30) / 34))) - 0.88) / 1000), 2)


                    Label88.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 29) / 34))) - 0.88) / 1000), 2)


                    Label87.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 28) / 34))) - 0.88) / 1000), 2)


                    Label86.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 27) / 34))) - 0.88) / 1000), 2)


                    Label85.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 26) / 34))) - 0.88) / 1000), 2)


                    Label84.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 25) / 34))) - 0.88) / 1000), 2)


                    Label83.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 24) / 34))) - 0.88) / 1000), 2)


                    Label82.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 23) / 34))) - 0.88) / 1000), 2)


                    Label81.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 22) / 34))) - 0.88) / 1000), 2)


                    Label80.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 21) / 34))) - 0.88) / 1000), 2)


                    Label79.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 20) / 34))) - 0.88) / 1000), 2)


                    Label78.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 19) / 34))) - 0.88) / 1000), 2)


                    Label77.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 18) / 34))) - 0.88) / 1000), 2)


                    Label76.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 17) / 34))) - 0.88) / 1000), 2)


                    Label75.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 16) / 34))) - 0.88) / 1000), 2)


                    Label74.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 15) / 34))) - 0.88) / 1000), 2)


                    Label73.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 14) / 34))) - 0.88) / 1000), 2)


                    Label72.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 13) / 34))) - 0.88) / 1000), 2)


                    Label71.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 12) / 34))) - 0.88) / 1000), 2)


                    Label70.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 11) / 34))) - 0.88) / 1000), 2)


                    Label69.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 10) / 34))) - 0.88) / 1000), 2)


                    Label68.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 9) / 34))) - 0.88) / 1000), 2)


                    Label67.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 8) / 34))) - 0.88) / 1000), 2)


                    Label66.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 7) / 34))) - 0.88) / 1000), 2)


                    Label65.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 6) / 34))) - 0.88) / 1000), 2)


                    Label64.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 5) / 34))) - 0.88) / 1000), 2)


                    Label63.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 4) / 34))) - 0.88) / 1000), 2)


                    Label62.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 3) / 34))) - 0.88) / 1000), 2)


                    Label61.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 2) / 34))) - 0.88) / 1000), 2)


                    Label60.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 1) / 34))) - 0.88) / 1000), 2)


                    Label59.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 0) / 34))) - 0.88) / 1000), 2)


                End If



                If TextBox11.Text = 35 Then


                    PictureBox12.Image = My.Resources._9_4


                    Label99.Text = ""


                    Label98.Text = ""


                    Label97.Text = ""


                    Label96.Text = ""


                    Label95.Text = ""


                    Label94.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 35) / 35))) - 0.88) / 1000), 2)


                    Label93.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 34) / 35))) - 0.88) / 1000), 2)


                    Label92.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 33) / 35))) - 0.88) / 1000), 2)


                    Label91.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 32) / 35))) - 0.88) / 1000), 2)


                    Label90.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 31) / 35))) - 0.88) / 1000), 2)


                    Label89.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 30) / 35))) - 0.88) / 1000), 2)


                    Label88.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 29) / 35))) - 0.88) / 1000), 2)


                    Label87.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 28) / 35))) - 0.88) / 1000), 2)


                    Label86.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 27) / 35))) - 0.88) / 1000), 2)


                    Label85.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 26) / 35))) - 0.88) / 1000), 2)


                    Label84.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 25) / 35))) - 0.88) / 1000), 2)


                    Label83.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 24) / 35))) - 0.88) / 1000), 2)


                    Label82.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 23) / 35))) - 0.88) / 1000), 2)


                    Label81.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 22) / 35))) - 0.88) / 1000), 2)


                    Label80.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 21) / 35))) - 0.88) / 1000), 2)


                    Label79.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 20) / 35))) - 0.88) / 1000), 2)


                    Label78.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 19) / 35))) - 0.88) / 1000), 2)


                    Label77.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 18) / 35))) - 0.88) / 1000), 2)


                    Label76.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 17) / 35))) - 0.88) / 1000), 2)


                    Label75.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 16) / 35))) - 0.88) / 1000), 2)


                    Label74.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 15) / 35))) - 0.88) / 1000), 2)


                    Label73.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 14) / 35))) - 0.88) / 1000), 2)


                    Label72.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 13) / 35))) - 0.88) / 1000), 2)


                    Label71.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 12) / 35))) - 0.88) / 1000), 2)


                    Label70.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 11) / 35))) - 0.88) / 1000), 2)


                    Label69.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 10) / 35))) - 0.88) / 1000), 2)


                    Label68.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 9) / 35))) - 0.88) / 1000), 2)


                    Label67.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 8) / 35))) - 0.88) / 1000), 2)


                    Label66.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 7) / 35))) - 0.88) / 1000), 2)


                    Label65.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 6) / 35))) - 0.88) / 1000), 2)


                    Label64.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 5) / 35))) - 0.88) / 1000), 2)


                    Label63.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 4) / 35))) - 0.88) / 1000), 2)


                    Label62.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 3) / 35))) - 0.88) / 1000), 2)


                    Label61.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 2) / 35))) - 0.88) / 1000), 2)


                    Label60.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 1) / 35))) - 0.88) / 1000), 2)


                    Label59.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 0) / 35))) - 0.88) / 1000), 2)


                End If



                If TextBox11.Text = 36 Then


                    PictureBox12.Image = My.Resources._9_7


                    Label99.Text = ""


                    Label98.Text = ""


                    Label97.Text = ""


                    Label96.Text = ""


                    Label95.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 36) / 36))) - 0.88) / 1000), 2)


                    Label94.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 35) / 36))) - 0.88) / 1000), 2)


                    Label93.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 34) / 36))) - 0.88) / 1000), 2)


                    Label92.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 33) / 36))) - 0.88) / 1000), 2)


                    Label91.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 32) / 36))) - 0.88) / 1000), 2)


                    Label90.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 31) / 36))) - 0.88) / 1000), 2)


                    Label89.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 30) / 36))) - 0.88) / 1000), 2)


                    Label88.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 29) / 36))) - 0.88) / 1000), 2)


                    Label87.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 28) / 36))) - 0.88) / 1000), 2)


                    Label86.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 27) / 36))) - 0.88) / 1000), 2)


                    Label85.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 26) / 36))) - 0.88) / 1000), 2)


                    Label84.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 25) / 36))) - 0.88) / 1000), 2)


                    Label83.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 24) / 36))) - 0.88) / 1000), 2)


                    Label82.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 23) / 36))) - 0.88) / 1000), 2)


                    Label81.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 22) / 36))) - 0.88) / 1000), 2)


                    Label80.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 21) / 36))) - 0.88) / 1000), 2)


                    Label79.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 20) / 36))) - 0.88) / 1000), 2)


                    Label78.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 19) / 36))) - 0.88) / 1000), 2)


                    Label77.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 18) / 36))) - 0.88) / 1000), 2)


                    Label76.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 17) / 36))) - 0.88) / 1000), 2)


                    Label75.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 16) / 36))) - 0.88) / 1000), 2)


                    Label74.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 15) / 36))) - 0.88) / 1000), 2)


                    Label73.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 14) / 36))) - 0.88) / 1000), 2)


                    Label72.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 13) / 36))) - 0.88) / 1000), 2)


                    Label71.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 12) / 36))) - 0.88) / 1000), 2)


                    Label70.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 11) / 36))) - 0.88) / 1000), 2)


                    Label69.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 10) / 36))) - 0.88) / 1000), 2)


                    Label68.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 9) / 36))) - 0.88) / 1000), 2)


                    Label67.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 8) / 36))) - 0.88) / 1000), 2)


                    Label66.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 7) / 36))) - 0.88) / 1000), 2)


                    Label65.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 6) / 36))) - 0.88) / 1000), 2)


                    Label64.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 5) / 36))) - 0.88) / 1000), 2)


                    Label63.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 4) / 36))) - 0.88) / 1000), 2)


                    Label62.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 3) / 36))) - 0.88) / 1000), 2)


                    Label61.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 2) / 36))) - 0.88) / 1000), 2)


                    Label60.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 1) / 36))) - 0.88) / 1000), 2)


                    Label59.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 0) / 36))) - 0.88) / 1000), 2)


                End If



                If TextBox11.Text = 37 Then


                    PictureBox12.Image = My.Resources._9_9


                    Label99.Text = ""


                    Label98.Text = ""


                    Label97.Text = ""


                    Label96.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 37) / 37))) - 0.88) / 1000), 2)


                    Label95.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 36) / 37))) - 0.88) / 1000), 2)


                    Label94.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 35) / 37))) - 0.88) / 1000), 2)


                    Label93.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 34) / 37))) - 0.88) / 1000), 2)


                    Label92.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 33) / 37))) - 0.88) / 1000), 2)


                    Label91.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 32) / 37))) - 0.88) / 1000), 2)


                    Label90.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 31) / 37))) - 0.88) / 1000), 2)


                    Label89.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 30) / 37))) - 0.88) / 1000), 2)


                    Label88.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 29) / 37))) - 0.88) / 1000), 2)


                    Label87.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 28) / 37))) - 0.88) / 1000), 2)


                    Label86.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 27) / 37))) - 0.88) / 1000), 2)


                    Label85.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 26) / 37))) - 0.88) / 1000), 2)


                    Label84.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 25) / 37))) - 0.88) / 1000), 2)


                    Label83.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 24) / 37))) - 0.88) / 1000), 2)


                    Label82.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 23) / 37))) - 0.88) / 1000), 2)


                    Label81.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 22) / 37))) - 0.88) / 1000), 2)


                    Label80.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 21) / 37))) - 0.88) / 1000), 2)


                    Label79.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 20) / 37))) - 0.88) / 1000), 2)


                    Label78.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 19) / 37))) - 0.88) / 1000), 2)


                    Label77.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 18) / 37))) - 0.88) / 1000), 2)


                    Label76.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 17) / 37))) - 0.88) / 1000), 2)


                    Label75.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 16) / 37))) - 0.88) / 1000), 2)


                    Label74.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 15) / 37))) - 0.88) / 1000), 2)


                    Label73.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 14) / 37))) - 0.88) / 1000), 2)


                    Label72.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 13) / 37))) - 0.88) / 1000), 2)


                    Label71.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 12) / 37))) - 0.88) / 1000), 2)


                    Label70.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 11) / 37))) - 0.88) / 1000), 2)


                    Label69.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 10) / 37))) - 0.88) / 1000), 2)


                    Label68.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 9) / 37))) - 0.88) / 1000), 2)


                    Label67.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 8) / 37))) - 0.88) / 1000), 2)


                    Label66.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 7) / 37))) - 0.88) / 1000), 2)


                    Label65.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 6) / 37))) - 0.88) / 1000), 2)


                    Label64.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 5) / 37))) - 0.88) / 1000), 2)


                    Label63.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 4) / 37))) - 0.88) / 1000), 2)


                    Label62.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 3) / 37))) - 0.88) / 1000), 2)


                    Label61.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 2) / 37))) - 0.88) / 1000), 2)


                    Label60.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 1) / 37))) - 0.88) / 1000), 2)


                    Label59.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 0) / 37))) - 0.88) / 1000), 2)


                End If



                If TextBox11.Text = 38 Then


                    PictureBox12.Image = My.Resources._10_1


                    Label99.Text = ""


                    Label98.Text = ""


                    Label97.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 38) / 38))) - 0.88) / 1000), 2)


                    Label96.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 37) / 38))) - 0.88) / 1000), 2)


                    Label95.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 36) / 38))) - 0.88) / 1000), 2)


                    Label94.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 35) / 38))) - 0.88) / 1000), 2)


                    Label93.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 34) / 38))) - 0.88) / 1000), 2)


                    Label92.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 33) / 38))) - 0.88) / 1000), 2)


                    Label91.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 32) / 38))) - 0.88) / 1000), 2)


                    Label90.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 31) / 38))) - 0.88) / 1000), 2)


                    Label89.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 30) / 38))) - 0.88) / 1000), 2)


                    Label88.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 29) / 38))) - 0.88) / 1000), 2)


                    Label87.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 28) / 38))) - 0.88) / 1000), 2)


                    Label86.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 27) / 38))) - 0.88) / 1000), 2)


                    Label85.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 26) / 38))) - 0.88) / 1000), 2)


                    Label84.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 25) / 38))) - 0.88) / 1000), 2)


                    Label83.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 24) / 38))) - 0.88) / 1000), 2)


                    Label82.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 23) / 38))) - 0.88) / 1000), 2)


                    Label81.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 22) / 38))) - 0.88) / 1000), 2)


                    Label80.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 21) / 38))) - 0.88) / 1000), 2)


                    Label79.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 20) / 38))) - 0.88) / 1000), 2)


                    Label78.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 19) / 38))) - 0.88) / 1000), 2)


                    Label77.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 18) / 38))) - 0.88) / 1000), 2)


                    Label76.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 17) / 38))) - 0.88) / 1000), 2)


                    Label75.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 16) / 38))) - 0.88) / 1000), 2)


                    Label74.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 15) / 38))) - 0.88) / 1000), 2)


                    Label73.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 14) / 38))) - 0.88) / 1000), 2)


                    Label72.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 13) / 38))) - 0.88) / 1000), 2)


                    Label71.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 12) / 38))) - 0.88) / 1000), 2)


                    Label70.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 11) / 38))) - 0.88) / 1000), 2)


                    Label69.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 10) / 38))) - 0.88) / 1000), 2)


                    Label68.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 9) / 38))) - 0.88) / 1000), 2)


                    Label67.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 8) / 38))) - 0.88) / 1000), 2)


                    Label66.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 7) / 38))) - 0.88) / 1000), 2)


                    Label65.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 6) / 38))) - 0.88) / 1000), 2)


                    Label64.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 5) / 38))) - 0.88) / 1000), 2)


                    Label63.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 4) / 38))) - 0.88) / 1000), 2)


                    Label62.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 3) / 38))) - 0.88) / 1000), 2)


                    Label61.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 2) / 38))) - 0.88) / 1000), 2)


                    Label60.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 1) / 38))) - 0.88) / 1000), 2)


                    Label59.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 0) / 38))) - 0.88) / 1000), 2)


                End If



                If TextBox11.Text = 39 Then


                    PictureBox12.Image = My.Resources._10_3


                    Label99.Text = ""


                    Label98.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 39) / 39))) - 0.88) / 1000), 2)


                    Label97.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 38) / 39))) - 0.88) / 1000), 2)


                    Label96.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 37) / 39))) - 0.88) / 1000), 2)


                    Label95.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 36) / 39))) - 0.88) / 1000), 2)


                    Label94.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 35) / 39))) - 0.88) / 1000), 2)


                    Label93.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 34) / 39))) - 0.88) / 1000), 2)


                    Label92.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 33) / 39))) - 0.88) / 1000), 2)


                    Label91.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 32) / 39))) - 0.88) / 1000), 2)


                    Label90.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 31) / 39))) - 0.88) / 1000), 2)


                    Label89.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 30) / 39))) - 0.88) / 1000), 2)


                    Label88.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 29) / 39))) - 0.88) / 1000), 2)


                    Label87.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 28) / 39))) - 0.88) / 1000), 2)


                    Label86.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 27) / 39))) - 0.88) / 1000), 2)


                    Label85.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 26) / 39))) - 0.88) / 1000), 2)


                    Label84.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 25) / 39))) - 0.88) / 1000), 2)


                    Label83.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 24) / 39))) - 0.88) / 1000), 2)


                    Label82.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 23) / 39))) - 0.88) / 1000), 2)


                    Label81.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 22) / 39))) - 0.88) / 1000), 2)


                    Label80.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 21) / 39))) - 0.88) / 1000), 2)


                    Label79.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 20) / 39))) - 0.88) / 1000), 2)


                    Label78.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 19) / 39))) - 0.88) / 1000), 2)


                    Label77.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 18) / 39))) - 0.88) / 1000), 2)


                    Label76.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 17) / 39))) - 0.88) / 1000), 2)


                    Label75.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 16) / 39))) - 0.88) / 1000), 2)


                    Label74.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 15) / 39))) - 0.88) / 1000), 2)


                    Label73.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 14) / 39))) - 0.88) / 1000), 2)


                    Label72.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 13) / 39))) - 0.88) / 1000), 2)


                    Label71.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 12) / 39))) - 0.88) / 1000), 2)


                    Label70.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 11) / 39))) - 0.88) / 1000), 2)


                    Label69.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 10) / 39))) - 0.88) / 1000), 2)


                    Label68.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 9) / 39))) - 0.88) / 1000), 2)


                    Label67.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 8) / 39))) - 0.88) / 1000), 2)


                    Label66.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 7) / 39))) - 0.88) / 1000), 2)


                    Label65.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 6) / 39))) - 0.88) / 1000), 2)


                    Label64.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 5) / 39))) - 0.88) / 1000), 2)


                    Label63.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 4) / 39))) - 0.88) / 1000), 2)


                    Label62.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 3) / 39))) - 0.88) / 1000), 2)


                    Label61.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 2) / 39))) - 0.88) / 1000), 2)


                    Label60.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 1) / 39))) - 0.88) / 1000), 2)


                    Label59.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 0) / 30))) - 0.88) / 1000), 2)


                End If



                If TextBox11.Text = 40 Then


                    PictureBox12.Image = My.Resources._10_5


                    Label99.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 40) / 40))) - 0.88) / 1000), 2)


                    Label98.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 39) / 40))) - 0.88) / 1000), 2)


                    Label97.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 38) / 40))) - 0.88) / 1000), 2)


                    Label96.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 37) / 40))) - 0.88) / 1000), 2)


                    Label95.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 36) / 40))) - 0.88) / 1000), 2)


                    Label94.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 35) / 40))) - 0.88) / 1000), 2)


                    Label93.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 34) / 40))) - 0.88) / 1000), 2)


                    Label92.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 33) / 40))) - 0.88) / 1000), 2)


                    Label91.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 32) / 40))) - 0.88) / 1000), 2)


                    Label90.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 31) / 40))) - 0.88) / 1000), 2)


                    Label89.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 30) / 40))) - 0.88) / 1000), 2)


                    Label88.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 29) / 40))) - 0.88) / 1000), 2)


                    Label87.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 28) / 40))) - 0.88) / 1000), 2)


                    Label86.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 27) / 40))) - 0.88) / 1000), 2)


                    Label85.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 26) / 40))) - 0.88) / 1000), 2)


                    Label84.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 25) / 40))) - 0.88) / 1000), 2)


                    Label83.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 24) / 40))) - 0.88) / 1000), 2)


                    Label82.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 23) / 40))) - 0.88) / 1000), 2)


                    Label81.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 22) / 40))) - 0.88) / 1000), 2)


                    Label80.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 21) / 40))) - 0.88) / 1000), 2)


                    Label79.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 20) / 40))) - 0.88) / 1000), 2)


                    Label78.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 19) / 40))) - 0.88) / 1000), 2)


                    Label77.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 18) / 40))) - 0.88) / 1000), 2)


                    Label76.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 17) / 40))) - 0.88) / 1000), 2)


                    Label75.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 16) / 40))) - 0.88) / 1000), 2)


                    Label74.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 15) / 40))) - 0.88) / 1000), 2)


                    Label73.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 14) / 40))) - 0.88) / 1000), 2)


                    Label72.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 13) / 40))) - 0.88) / 1000), 2)


                    Label71.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 12) / 40))) - 0.88) / 1000), 2)


                    Label70.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 11) / 40))) - 0.88) / 1000), 2)


                    Label69.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 10) / 40))) - 0.88) / 1000), 2)


                    Label68.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 9) / 40))) - 0.88) / 1000), 2)


                    Label67.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 8) / 40))) - 0.88) / 1000), 2)


                    Label66.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 7) / 40))) - 0.88) / 1000), 2)


                    Label65.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 6) / 40))) - 0.88) / 1000), 2)


                    Label64.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 5) / 40))) - 0.88) / 1000), 2)


                    Label63.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 4) / 40))) - 0.88) / 1000), 2)


                    Label62.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 3) / 40))) - 0.88) / 1000), 2)


                    Label61.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 2) / 40))) - 0.88) / 1000), 2)


                    Label60.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 1) / 40))) - 0.88) / 1000), 2)


                    Label59.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 0) / 40))) - 0.88) / 1000), 2)


                End If


            End If


        End If



        If ComboBox4.Visible = True Then


            If ComboBox4.Text = "" Then


                MsgBox("Please select an A value")


                If TextBox6.Text = "" Then


                    MsgBox("Hey, you skipped clicking 3 buttons in front")


                    PictureBox4.Visible = False


                End If



            Else


                Dim sg As Single


                sg = TextBox6.Text * 0.41


                sg = Math.Round(sg, 1)


                TextBox4.Text = sg



                Panel6.Visible = True


                TextBox4.Visible = True


                Label106.Visible = True


                Label107.Visible = True


                Label105.Visible = True


                PictureBox12.Visible = True


                PictureBox11.Visible = True


                PictureBox10.Visible = True


                Label166.Visible = True


                Label145.Visible = True


                Label146.Visible = True


                Label147.Visible = True


                Label148.Visible = True


                Label149.Visible = True


                Label150.Visible = True


                Label151.Visible = True


                Label152.Visible = True


                Label153.Visible = True


                Label154.Visible = True


                Label155.Visible = True


                Label156.Visible = True


                Label157.Visible = True


                Label158.Visible = True


                Label159.Visible = True


                Label160.Visible = True


                Label161.Visible = True


                Label162.Visible = True


                Label163.Visible = True


                Label164.Visible = True


                Label165.Visible = True



                If TextBox11.Text = 25 Then


                    PictureBox12.Image = My.Resources._7_0


                    Label99.Text = ""


                    Label98.Text = ""


                    Label97.Text = ""


                    Label96.Text = ""


                    Label95.Text = ""


                    Label94.Text = ""


                    Label93.Text = ""


                    Label92.Text = ""


                    Label91.Text = ""


                    Label90.Text = ""


                    Label89.Text = ""


                    Label88.Text = ""


                    Label87.Text = ""


                    Label86.Text = ""


                    Label85.Text = ""


                    Label84.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((25 - 25) / 25))) - 0.88) / 1000), 2)


                    Label83.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((25 - 24) / 25))) - 0.88) / 1000), 2)


                    Label82.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((25 - 23) / 25))) - 0.88) / 1000), 2)


                    Label81.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((25 - 22) / 25))) - 0.88) / 1000), 2)


                    Label80.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((25 - 21) / 25))) - 0.88) / 1000), 2)


                    Label79.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((25 - 20) / 25))) - 0.88) / 1000), 2)


                    Label78.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((25 - 19) / 25))) - 0.88) / 1000), 2)


                    Label77.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((25 - 18) / 25))) - 0.88) / 1000), 2)


                    Label76.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((25 - 17) / 25))) - 0.88) / 1000), 2)


                    Label75.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((25 - 16) / 25))) - 0.88) / 1000), 2)


                    Label74.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((25 - 15) / 25))) - 0.88) / 1000), 2)


                    Label73.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((25 - 14) / 25))) - 0.88) / 1000), 2)


                    Label72.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((25 - 13) / 25))) - 0.88) / 1000), 2)


                    Label71.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((25 - 12) / 25))) - 0.88) / 1000), 2)


                    Label70.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((25 - 11) / 25))) - 0.88) / 1000), 2)


                    Label69.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((25 - 10) / 25))) - 0.88) / 1000), 2)


                    Label68.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((25 - 9) / 25))) - 0.88) / 1000), 2)


                    Label67.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((25 - 8) / 25))) - 0.88) / 1000), 2)


                    Label66.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((25 - 7) / 25))) - 0.88) / 1000), 2)


                    Label65.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((25 - 6) / 25))) - 0.88) / 1000), 2)


                    Label64.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((25 - 5) / 25))) - 0.88) / 1000), 2)


                    Label63.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((25 - 4) / 25))) - 0.88) / 1000), 2)


                    Label62.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((25 - 3) / 25))) - 0.88) / 1000), 2)


                    Label61.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((25 - 2) / 25))) - 0.88) / 1000), 2)


                    Label60.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((25 - 1) / 25))) - 0.88) / 1000), 2)


                    Label59.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((25 - 0) / 25))) - 0.88) / 1000), 2)


                End If



                If TextBox11.Text = 26 Then


                    PictureBox12.Image = My.Resources._7_0


                    Label99.Text = ""


                    Label98.Text = ""


                    Label97.Text = ""


                    Label96.Text = ""


                    Label95.Text = ""


                    Label94.Text = ""


                    Label93.Text = ""


                    Label92.Text = ""


                    Label91.Text = ""


                    Label90.Text = ""


                    Label89.Text = ""


                    Label88.Text = ""


                    Label87.Text = ""


                    Label86.Text = ""


                    Label85.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((26 - 26) / 26))) - 0.88) / 1000), 2)


                    Label84.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((26 - 25) / 26))) - 0.88) / 1000), 2)


                    Label83.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((26 - 24) / 26))) - 0.88) / 1000), 2)


                    Label82.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((26 - 23) / 26))) - 0.88) / 1000), 2)


                    Label81.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((26 - 22) / 26))) - 0.88) / 1000), 2)


                    Label80.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((26 - 21) / 26))) - 0.88) / 1000), 2)


                    Label79.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((26 - 20) / 26))) - 0.88) / 1000), 2)


                    Label78.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((26 - 19) / 26))) - 0.88) / 1000), 2)


                    Label77.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((26 - 18) / 26))) - 0.88) / 1000), 2)


                    Label76.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((26 - 17) / 26))) - 0.88) / 1000), 2)


                    Label75.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((26 - 16) / 26))) - 0.88) / 1000), 2)


                    Label74.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((26 - 15) / 26))) - 0.88) / 1000), 2)


                    Label73.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((26 - 14) / 26))) - 0.88) / 1000), 2)


                    Label72.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((26 - 13) / 26))) - 0.88) / 1000), 2)


                    Label71.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((26 - 12) / 26))) - 0.88) / 1000), 2)


                    Label70.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((26 - 11) / 26))) - 0.88) / 1000), 2)


                    Label69.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((26 - 10) / 26))) - 0.88) / 1000), 2)


                    Label68.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((26 - 9) / 26))) - 0.88) / 1000), 2)


                    Label67.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((26 - 8) / 26))) - 0.88) / 1000), 2)


                    Label66.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((26 - 7) / 26))) - 0.88) / 1000), 2)


                    Label65.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((26 - 6) / 26))) - 0.88) / 1000), 2)


                    Label64.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((26 - 5) / 26))) - 0.88) / 1000), 2)


                    Label63.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((26 - 4) / 26))) - 0.88) / 1000), 2)


                    Label62.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((26 - 3) / 26))) - 0.88) / 1000), 2)


                    Label61.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((26 - 2) / 26))) - 0.88) / 1000), 2)


                    Label60.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((26 - 1) / 26))) - 0.88) / 1000), 2)


                    Label59.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((26 - 0) / 26))) - 0.88) / 1000), 2)


                End If



                If TextBox11.Text = 27 Then


                    PictureBox12.Image = My.Resources._7_2


                    Label99.Text = ""


                    Label98.Text = ""


                    Label97.Text = ""


                    Label96.Text = ""


                    Label95.Text = ""


                    Label94.Text = ""


                    Label93.Text = ""


                    Label92.Text = ""


                    Label91.Text = ""


                    Label90.Text = ""


                    Label89.Text = ""


                    Label88.Text = ""


                    Label87.Text = ""


                    Label86.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 27) / 27))) - 0.88) / 1000), 2)


                    Label85.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 26) / 27))) - 0.88) / 1000), 2)


                    Label84.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 25) / 27))) - 0.88) / 1000), 2)


                    Label83.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 24) / 27))) - 0.88) / 1000), 2)


                    Label82.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 23) / 27))) - 0.88) / 1000), 2)


                    Label81.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 22) / 27))) - 0.88) / 1000), 2)


                    Label80.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 21) / 27))) - 0.88) / 1000), 2)


                    Label79.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 20) / 27))) - 0.88) / 1000), 2)


                    Label78.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 19) / 27))) - 0.88) / 1000), 2)


                    Label77.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 18) / 27))) - 0.88) / 1000), 2)


                    Label76.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 17) / 27))) - 0.88) / 1000), 2)


                    Label75.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 16) / 27))) - 0.88) / 1000), 2)


                    Label74.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 15) / 27))) - 0.88) / 1000), 2)


                    Label73.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 14) / 27))) - 0.88) / 1000), 2)


                    Label72.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 13) / 27))) - 0.88) / 1000), 2)


                    Label71.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 12) / 27))) - 0.88) / 1000), 2)


                    Label70.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 11) / 27))) - 0.88) / 1000), 2)


                    Label69.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 10) / 27))) - 0.88) / 1000), 2)


                    Label68.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 9) / 27))) - 0.88) / 1000), 2)


                    Label67.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 8) / 27))) - 0.88) / 1000), 2)


                    Label66.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 7) / 27))) - 0.88) / 1000), 2)


                    Label65.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 6) / 27))) - 0.88) / 1000), 2)


                    Label64.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 5) / 27))) - 0.88) / 1000), 2)


                    Label63.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 4) / 27))) - 0.88) / 1000), 2)


                    Label62.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 3) / 27))) - 0.88) / 1000), 2)


                    Label61.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 2) / 27))) - 0.88) / 1000), 2)


                    Label60.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 1) / 27))) - 0.88) / 1000), 2)


                    Label59.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 0) / 27))) - 0.88) / 1000), 2)


                End If



                If TextBox11.Text = 28 Then


                    PictureBox12.Image = My.Resources._7_4


                    Label99.Text = ""


                    Label98.Text = ""


                    Label97.Text = ""


                    Label96.Text = ""


                    Label95.Text = ""


                    Label94.Text = ""


                    Label93.Text = ""


                    Label92.Text = ""


                    Label91.Text = ""


                    Label90.Text = ""


                    Label89.Text = ""


                    Label88.Text = ""


                    Label87.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 28) / 28))) - 0.88) / 1000), 2)


                    Label86.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 27) / 28))) - 0.88) / 1000), 2)


                    Label85.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 26) / 28))) - 0.88) / 1000), 2)


                    Label84.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 25) / 28))) - 0.88) / 1000), 2)


                    Label83.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 24) / 28))) - 0.88) / 1000), 2)


                    Label82.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 23) / 28))) - 0.88) / 1000), 2)


                    Label81.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 22) / 28))) - 0.88) / 1000), 2)


                    Label80.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 21) / 28))) - 0.88) / 1000), 2)


                    Label79.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 20) / 28))) - 0.88) / 1000), 2)


                    Label78.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 19) / 28))) - 0.88) / 1000), 2)


                    Label77.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 18) / 28))) - 0.88) / 1000), 2)


                    Label76.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 17) / 28))) - 0.88) / 1000), 2)


                    Label75.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 16) / 28))) - 0.88) / 1000), 2)


                    Label74.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 15) / 28))) - 0.88) / 1000), 2)


                    Label73.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 14) / 28))) - 0.88) / 1000), 2)


                    Label72.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 13) / 28))) - 0.88) / 1000), 2)


                    Label71.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 12) / 28))) - 0.88) / 1000), 2)


                    Label70.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 11) / 28))) - 0.88) / 1000), 2)


                    Label69.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 10) / 28))) - 0.88) / 1000), 2)


                    Label68.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 9) / 28))) - 0.88) / 1000), 2)


                    Label67.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 8) / 28))) - 0.88) / 1000), 2)


                    Label66.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 7) / 28))) - 0.88) / 1000), 2)


                    Label65.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 6) / 28))) - 0.88) / 1000), 2)


                    Label64.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 5) / 28))) - 0.88) / 1000), 2)


                    Label63.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 4) / 28))) - 0.88) / 1000), 2)


                    Label62.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 3) / 28))) - 0.88) / 1000), 2)


                    Label61.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 2) / 28))) - 0.88) / 1000), 2)


                    Label60.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 1) / 28))) - 0.88) / 1000), 2)


                    Label59.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 0) / 28))) - 0.88) / 1000), 2)


                End If



                If TextBox11.Text = 29 Then


                    PictureBox12.Image = My.Resources._7_6


                    Label99.Text = ""


                    Label98.Text = ""


                    Label97.Text = ""


                    Label96.Text = ""


                    Label95.Text = ""


                    Label94.Text = ""


                    Label93.Text = ""


                    Label92.Text = ""


                    Label91.Text = ""


                    Label90.Text = ""


                    Label89.Text = ""


                    Label88.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 29) / 29))) - 0.88) / 1000), 2)


                    Label87.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 28) / 29))) - 0.88) / 1000), 2)


                    Label85.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 26) / 29))) - 0.88) / 1000), 2)


                    Label84.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 25) / 29))) - 0.88) / 1000), 2)


                    Label83.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 24) / 29))) - 0.88) / 1000), 2)


                    Label82.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 23) / 29))) - 0.88) / 1000), 2)


                    Label81.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 22) / 29))) - 0.88) / 1000), 2)


                    Label80.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 21) / 29))) - 0.88) / 1000), 2)


                    Label79.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 20) / 29))) - 0.88) / 1000), 2)


                    Label78.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 19) / 29))) - 0.88) / 1000), 2)


                    Label77.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 18) / 29))) - 0.88) / 1000), 2)


                    Label76.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 17) / 29))) - 0.88) / 1000), 2)


                    Label75.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 16) / 29))) - 0.88) / 1000), 2)


                    Label74.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 15) / 29))) - 0.88) / 1000), 2)


                    Label73.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 14) / 29))) - 0.88) / 1000), 2)


                    Label72.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 13) / 29))) - 0.88) / 1000), 2)


                    Label71.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 12) / 29))) - 0.88) / 1000), 2)


                    Label70.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 11) / 29))) - 0.88) / 1000), 2)


                    Label69.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 10) / 29))) - 0.88) / 1000), 2)


                    Label68.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 9) / 29))) - 0.88) / 1000), 2)


                    Label67.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 8) / 29))) - 0.88) / 1000), 2)


                    Label66.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 7) / 29))) - 0.88) / 1000), 2)


                    Label65.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 6) / 29))) - 0.88) / 1000), 2)


                    Label64.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 5) / 29))) - 0.88) / 1000), 2)


                    Label63.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 4) / 29))) - 0.88) / 1000), 2)


                    Label62.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 3) / 29))) - 0.88) / 1000), 2)


                    Label61.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 2) / 29))) - 0.88) / 1000), 2)


                    Label60.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 1) / 29))) - 0.88) / 1000), 2)


                    Label59.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 0) / 29))) - 0.88) / 1000), 2)


                End If



                If TextBox11.Text = 30 Then


                    PictureBox12.Image = My.Resources._7_8


                    Label99.Text = ""


                    Label98.Text = ""


                    Label97.Text = ""


                    Label96.Text = ""


                    Label95.Text = ""


                    Label94.Text = ""


                    Label93.Text = ""


                    Label92.Text = ""


                    Label91.Text = ""


                    Label90.Text = ""


                    Label89.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 30) / 30))) - 0.88) / 1000), 2)


                    Label88.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 29) / 30))) - 0.88) / 1000), 2)


                    Label87.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 28) / 30))) - 0.88) / 1000), 2)


                    Label86.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 27) / 30))) - 0.88) / 1000), 2)


                    Label85.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 26) / 30))) - 0.88) / 1000), 2)


                    Label84.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 25) / 30))) - 0.88) / 1000), 2)


                    Label83.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 24) / 30))) - 0.88) / 1000), 2)


                    Label82.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 23) / 30))) - 0.88) / 1000), 2)


                    Label81.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 22) / 30))) - 0.88) / 1000), 2)


                    Label80.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 21) / 30))) - 0.88) / 1000), 2)


                    Label79.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 20) / 30))) - 0.88) / 1000), 2)


                    Label78.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 19) / 30))) - 0.88) / 1000), 2)


                    Label77.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 18) / 30))) - 0.88) / 1000), 2)


                    Label76.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 17) / 30))) - 0.88) / 1000), 2)


                    Label75.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 16) / 30))) - 0.88) / 1000), 2)


                    Label74.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 15) / 30))) - 0.88) / 1000), 2)


                    Label73.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 14) / 30))) - 0.88) / 1000), 2)


                    Label72.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 13) / 30))) - 0.88) / 1000), 2)


                    Label71.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 12) / 30))) - 0.88) / 1000), 2)


                    Label70.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 11) / 30))) - 0.88) / 1000), 2)


                    Label69.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 10) / 30))) - 0.88) / 1000), 2)


                    Label68.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 9) / 30))) - 0.88) / 1000), 2)


                    Label67.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 8) / 30))) - 0.88) / 1000), 2)


                    Label66.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 7) / 30))) - 0.88) / 1000), 2)


                    Label65.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 6) / 30))) - 0.88) / 1000), 2)


                    Label64.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 5) / 30))) - 0.88) / 1000), 2)


                    Label63.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 4) / 30))) - 0.88) / 1000), 2)


                    Label62.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 3) / 30))) - 0.88) / 1000), 2)


                    Label61.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 2) / 30))) - 0.88) / 1000), 2)


                    Label60.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 1) / 30))) - 0.88) / 1000), 2)


                    Label59.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 0) / 30))) - 0.88) / 1000), 2)


                End If



                If TextBox11.Text = 31 Then


                    PictureBox12.Image = My.Resources._8_2


                    Label99.Text = ""


                    Label98.Text = ""


                    Label97.Text = ""


                    Label96.Text = ""


                    Label95.Text = ""


                    Label94.Text = ""


                    Label93.Text = ""


                    Label92.Text = ""


                    Label91.Text = ""


                    Label90.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 31) / 31))) - 0.88) / 1000), 2)


                    Label89.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 30) / 31))) - 0.88) / 1000), 2)


                    Label88.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 29) / 31))) - 0.88) / 1000), 2)


                    Label87.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 28) / 31))) - 0.88) / 1000), 2)


                    Label86.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 27) / 31))) - 0.88) / 1000), 2)


                    Label85.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 26) / 31))) - 0.88) / 1000), 2)


                    Label84.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 25) / 31))) - 0.88) / 1000), 2)


                    Label83.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 24) / 31))) - 0.88) / 1000), 2)


                    Label82.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 23) / 31))) - 0.88) / 1000), 2)


                    Label81.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 22) / 31))) - 0.88) / 1000), 2)


                    Label80.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 21) / 31))) - 0.88) / 1000), 2)


                    Label79.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 20) / 31))) - 0.88) / 1000), 2)


                    Label78.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 19) / 31))) - 0.88) / 1000), 2)


                    Label77.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 18) / 31))) - 0.88) / 1000), 2)


                    Label76.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 17) / 31))) - 0.88) / 1000), 2)


                    Label75.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 16) / 31))) - 0.88) / 1000), 2)


                    Label74.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 15) / 31))) - 0.88) / 1000), 2)


                    Label73.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 14) / 31))) - 0.88) / 1000), 2)


                    Label72.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 13) / 31))) - 0.88) / 1000), 2)


                    Label71.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 12) / 31))) - 0.88) / 1000), 2)


                    Label70.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 11) / 31))) - 0.88) / 1000), 2)


                    Label69.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 10) / 31))) - 0.88) / 1000), 2)


                    Label68.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 9) / 31))) - 0.88) / 1000), 2)


                    Label67.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 8) / 31))) - 0.88) / 1000), 2)


                    Label66.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 7) / 31))) - 0.88) / 1000), 2)


                    Label65.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 6) / 31))) - 0.88) / 1000), 2)


                    Label64.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 5) / 31))) - 0.88) / 1000), 2)


                    Label63.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 4) / 31))) - 0.88) / 1000), 2)


                    Label62.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 3) / 31))) - 0.88) / 1000), 2)


                    Label61.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 2) / 31))) - 0.88) / 1000), 2)


                    Label60.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 1) / 31))) - 0.88) / 1000), 2)


                    Label59.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 0) / 31))) - 0.88) / 1000), 2)


                End If



                If TextBox11.Text = 32 Then


                    PictureBox12.Image = My.Resources._8_6


                    Label99.Text = ""


                    Label98.Text = ""


                    Label97.Text = ""


                    Label96.Text = ""


                    Label95.Text = ""


                    Label94.Text = ""


                    Label93.Text = ""


                    Label92.Text = ""


                    Label91.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 32) / 32))) - 0.88) / 1000), 2)


                    Label90.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 31) / 32))) - 0.88) / 1000), 2)


                    Label89.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 30) / 32))) - 0.88) / 1000), 2)


                    Label88.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 29) / 32))) - 0.88) / 1000), 2)


                    Label87.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 28) / 32))) - 0.88) / 1000), 2)


                    Label86.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 27) / 32))) - 0.88) / 1000), 2)


                    Label85.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 26) / 32))) - 0.88) / 1000), 2)


                    Label84.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 25) / 32))) - 0.88) / 1000), 2)


                    Label83.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 24) / 32))) - 0.88) / 1000), 2)


                    Label82.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 23) / 32))) - 0.88) / 1000), 2)


                    Label81.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 22) / 32))) - 0.88) / 1000), 2)


                    Label80.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 21) / 32))) - 0.88) / 1000), 2)


                    Label79.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 20) / 32))) - 0.88) / 1000), 2)


                    Label78.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 19) / 32))) - 0.88) / 1000), 2)


                    Label77.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 18) / 32))) - 0.88) / 1000), 2)


                    Label76.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 17) / 32))) - 0.88) / 1000), 2)


                    Label75.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 16) / 32))) - 0.88) / 1000), 2)


                    Label74.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 15) / 32))) - 0.88) / 1000), 2)


                    Label73.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 14) / 32))) - 0.88) / 1000), 2)


                    Label72.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 13) / 32))) - 0.88) / 1000), 2)


                    Label71.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 12) / 32))) - 0.88) / 1000), 2)


                    Label70.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 11) / 32))) - 0.88) / 1000), 2)


                    Label69.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 10) / 32))) - 0.88) / 1000), 2)


                    Label68.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 9) / 32))) - 0.88) / 1000), 2)


                    Label67.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 8) / 32))) - 0.88) / 1000), 2)


                    Label66.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 7) / 32))) - 0.88) / 1000), 2)


                    Label65.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 6) / 32))) - 0.88) / 1000), 2)


                    Label64.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 5) / 32))) - 0.88) / 1000), 2)


                    Label63.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 4) / 32))) - 0.88) / 1000), 2)


                    Label62.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 3) / 32))) - 0.88) / 1000), 2)


                    Label61.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 2) / 32))) - 0.88) / 1000), 2)


                    Label60.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 1) / 32))) - 0.88) / 1000), 2)


                    Label59.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 0) / 32))) - 0.88) / 1000), 2)


                End If



                If TextBox11.Text = 33 Then


                    PictureBox12.Image = My.Resources._8_8


                    Label99.Text = ""


                    Label98.Text = ""


                    Label97.Text = ""


                    Label96.Text = ""


                    Label95.Text = ""


                    Label94.Text = ""


                    Label93.Text = ""


                    Label92.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 33) / 33))) - 0.88) / 1000), 2)


                    Label91.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 32) / 33))) - 0.88) / 1000), 2)


                    Label90.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 31) / 33))) - 0.88) / 1000), 2)


                    Label89.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 30) / 33))) - 0.88) / 1000), 2)


                    Label88.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 29) / 33))) - 0.88) / 1000), 2)


                    Label87.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 28) / 33))) - 0.88) / 1000), 2)


                    Label86.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 27) / 33))) - 0.88) / 1000), 2)


                    Label85.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 26) / 33))) - 0.88) / 1000), 2)


                    Label84.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 25) / 33))) - 0.88) / 1000), 2)


                    Label83.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 24) / 33))) - 0.88) / 1000), 2)


                    Label82.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 23) / 33))) - 0.88) / 1000), 2)


                    Label81.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 22) / 33))) - 0.88) / 1000), 2)


                    Label80.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 21) / 33))) - 0.88) / 1000), 2)


                    Label79.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 20) / 33))) - 0.88) / 1000), 2)


                    Label78.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 19) / 33))) - 0.88) / 1000), 2)


                    Label77.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 18) / 33))) - 0.88) / 1000), 2)


                    Label76.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 17) / 33))) - 0.88) / 1000), 2)


                    Label75.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 16) / 33))) - 0.88) / 1000), 2)


                    Label74.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 15) / 33))) - 0.88) / 1000), 2)


                    Label73.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 14) / 33))) - 0.88) / 1000), 2)


                    Label72.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 13) / 33))) - 0.88) / 1000), 2)


                    Label71.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 12) / 33))) - 0.88) / 1000), 2)


                    Label70.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 11) / 33))) - 0.88) / 1000), 2)


                    Label69.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 10) / 33))) - 0.88) / 1000), 2)


                    Label68.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 9) / 33))) - 0.88) / 1000), 2)


                    Label67.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 8) / 33))) - 0.88) / 1000), 2)


                    Label66.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 7) / 33))) - 0.88) / 1000), 2)


                    Label65.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 6) / 33))) - 0.88) / 1000), 2)


                    Label64.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 5) / 33))) - 0.88) / 1000), 2)


                    Label63.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 4) / 33))) - 0.88) / 1000), 2)


                    Label62.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 3) / 33))) - 0.88) / 1000), 2)


                    Label61.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 2) / 33))) - 0.88) / 1000), 2)


                    Label60.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 1) / 33))) - 0.88) / 1000), 2)


                    Label59.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 0) / 33))) - 0.88) / 1000), 2)


                End If



                If TextBox11.Text = 34 Then


                    PictureBox12.Image = My.Resources._9_0


                    Label99.Text = ""


                    Label98.Text = ""


                    Label97.Text = ""


                    Label96.Text = ""


                    Label95.Text = ""


                    Label94.Text = ""


                    Label93.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 34) / 34))) - 0.88) / 1000), 2)


                    Label92.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 33) / 34))) - 0.88) / 1000), 2)


                    Label91.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 32) / 34))) - 0.88) / 1000), 2)


                    Label90.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 31) / 34))) - 0.88) / 1000), 2)


                    Label89.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 30) / 34))) - 0.88) / 1000), 2)


                    Label88.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 29) / 34))) - 0.88) / 1000), 2)


                    Label87.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 28) / 34))) - 0.88) / 1000), 2)


                    Label86.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 27) / 34))) - 0.88) / 1000), 2)


                    Label85.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 26) / 34))) - 0.88) / 1000), 2)


                    Label84.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 25) / 34))) - 0.88) / 1000), 2)


                    Label83.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 24) / 34))) - 0.88) / 1000), 2)


                    Label82.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 23) / 34))) - 0.88) / 1000), 2)


                    Label81.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 22) / 34))) - 0.88) / 1000), 2)


                    Label80.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 21) / 34))) - 0.88) / 1000), 2)


                    Label79.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 20) / 34))) - 0.88) / 1000), 2)


                    Label78.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 19) / 34))) - 0.88) / 1000), 2)


                    Label77.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 18) / 34))) - 0.88) / 1000), 2)


                    Label76.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 17) / 34))) - 0.88) / 1000), 2)


                    Label75.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 16) / 34))) - 0.88) / 1000), 2)


                    Label74.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 15) / 34))) - 0.88) / 1000), 2)


                    Label73.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 14) / 34))) - 0.88) / 1000), 2)


                    Label72.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 13) / 34))) - 0.88) / 1000), 2)


                    Label71.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 12) / 34))) - 0.88) / 1000), 2)


                    Label70.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 11) / 34))) - 0.88) / 1000), 2)


                    Label69.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 10) / 34))) - 0.88) / 1000), 2)


                    Label68.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 9) / 34))) - 0.88) / 1000), 2)


                    Label67.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 8) / 34))) - 0.88) / 1000), 2)


                    Label66.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 7) / 34))) - 0.88) / 1000), 2)


                    Label65.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 6) / 34))) - 0.88) / 1000), 2)


                    Label64.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 5) / 34))) - 0.88) / 1000), 2)


                    Label63.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 4) / 34))) - 0.88) / 1000), 2)


                    Label62.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 3) / 34))) - 0.88) / 1000), 2)


                    Label61.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 2) / 34))) - 0.88) / 1000), 2)


                    Label60.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 1) / 34))) - 0.88) / 1000), 2)


                    Label59.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 0) / 34))) - 0.88) / 1000), 2)


                End If



                If TextBox11.Text = 35 Then


                    PictureBox12.Image = My.Resources._9_4


                    Label99.Text = ""


                    Label98.Text = ""


                    Label97.Text = ""


                    Label96.Text = ""


                    Label95.Text = ""


                    Label94.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 35) / 35))) - 0.88) / 1000), 2)


                    Label93.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 34) / 35))) - 0.88) / 1000), 2)


                    Label92.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 33) / 35))) - 0.88) / 1000), 2)


                    Label91.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 32) / 35))) - 0.88) / 1000), 2)


                    Label90.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 31) / 35))) - 0.88) / 1000), 2)


                    Label89.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 30) / 35))) - 0.88) / 1000), 2)


                    Label88.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 29) / 35))) - 0.88) / 1000), 2)


                    Label87.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 28) / 35))) - 0.88) / 1000), 2)


                    Label86.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 27) / 35))) - 0.88) / 1000), 2)


                    Label85.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 26) / 35))) - 0.88) / 1000), 2)


                    Label84.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 25) / 35))) - 0.88) / 1000), 2)


                    Label83.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 24) / 35))) - 0.88) / 1000), 2)


                    Label82.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 23) / 35))) - 0.88) / 1000), 2)


                    Label81.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 22) / 35))) - 0.88) / 1000), 2)


                    Label80.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 21) / 35))) - 0.88) / 1000), 2)


                    Label79.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 20) / 35))) - 0.88) / 1000), 2)


                    Label78.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 19) / 35))) - 0.88) / 1000), 2)


                    Label77.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 18) / 35))) - 0.88) / 1000), 2)


                    Label76.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 17) / 35))) - 0.88) / 1000), 2)


                    Label75.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 16) / 35))) - 0.88) / 1000), 2)


                    Label74.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 15) / 35))) - 0.88) / 1000), 2)


                    Label73.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 14) / 35))) - 0.88) / 1000), 2)


                    Label72.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 13) / 35))) - 0.88) / 1000), 2)


                    Label71.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 12) / 35))) - 0.88) / 1000), 2)


                    Label70.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 11) / 35))) - 0.88) / 1000), 2)


                    Label69.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 10) / 35))) - 0.88) / 1000), 2)


                    Label68.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 9) / 35))) - 0.88) / 1000), 2)


                    Label67.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 8) / 35))) - 0.88) / 1000), 2)


                    Label66.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 7) / 35))) - 0.88) / 1000), 2)


                    Label65.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 6) / 35))) - 0.88) / 1000), 2)


                    Label64.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 5) / 35))) - 0.88) / 1000), 2)


                    Label63.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 4) / 35))) - 0.88) / 1000), 2)


                    Label62.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 3) / 35))) - 0.88) / 1000), 2)


                    Label61.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 2) / 35))) - 0.88) / 1000), 2)


                    Label60.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 1) / 35))) - 0.88) / 1000), 2)


                    Label59.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 0) / 35))) - 0.88) / 1000), 2)


                End If



                If TextBox11.Text = 36 Then


                    PictureBox12.Image = My.Resources._9_7


                    Label99.Text = ""


                    Label98.Text = ""


                    Label97.Text = ""


                    Label96.Text = ""


                    Label95.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 36) / 36))) - 0.88) / 1000), 2)


                    Label94.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 35) / 36))) - 0.88) / 1000), 2)


                    Label93.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 34) / 36))) - 0.88) / 1000), 2)


                    Label92.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 33) / 36))) - 0.88) / 1000), 2)


                    Label91.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 32) / 36))) - 0.88) / 1000), 2)


                    Label90.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 31) / 36))) - 0.88) / 1000), 2)


                    Label89.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 30) / 36))) - 0.88) / 1000), 2)


                    Label88.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 29) / 36))) - 0.88) / 1000), 2)


                    Label87.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 28) / 36))) - 0.88) / 1000), 2)


                    Label86.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 27) / 36))) - 0.88) / 1000), 2)


                    Label85.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 26) / 36))) - 0.88) / 1000), 2)


                    Label84.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 25) / 36))) - 0.88) / 1000), 2)


                    Label83.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 24) / 36))) - 0.88) / 1000), 2)


                    Label82.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 23) / 36))) - 0.88) / 1000), 2)


                    Label81.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 22) / 36))) - 0.88) / 1000), 2)


                    Label80.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 21) / 36))) - 0.88) / 1000), 2)


                    Label79.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 20) / 36))) - 0.88) / 1000), 2)


                    Label78.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 19) / 36))) - 0.88) / 1000), 2)


                    Label77.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 18) / 36))) - 0.88) / 1000), 2)


                    Label76.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 17) / 36))) - 0.88) / 1000), 2)


                    Label75.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 16) / 36))) - 0.88) / 1000), 2)


                    Label74.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 15) / 36))) - 0.88) / 1000), 2)


                    Label73.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 14) / 36))) - 0.88) / 1000), 2)


                    Label72.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 13) / 36))) - 0.88) / 1000), 2)


                    Label71.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 12) / 36))) - 0.88) / 1000), 2)


                    Label70.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 11) / 36))) - 0.88) / 1000), 2)


                    Label69.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 10) / 36))) - 0.88) / 1000), 2)


                    Label68.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 9) / 36))) - 0.88) / 1000), 2)


                    Label67.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 8) / 36))) - 0.88) / 1000), 2)


                    Label66.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 7) / 36))) - 0.88) / 1000), 2)


                    Label65.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 6) / 36))) - 0.88) / 1000), 2)


                    Label64.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 5) / 36))) - 0.88) / 1000), 2)


                    Label63.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 4) / 36))) - 0.88) / 1000), 2)


                    Label62.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 3) / 36))) - 0.88) / 1000), 2)


                    Label61.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 2) / 36))) - 0.88) / 1000), 2)


                    Label60.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 1) / 36))) - 0.88) / 1000), 2)


                    Label59.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 0) / 36))) - 0.88) / 1000), 2)


                End If



                If TextBox11.Text = 37 Then


                    PictureBox12.Image = My.Resources._9_9


                    Label99.Text = ""


                    Label98.Text = ""


                    Label97.Text = ""


                    Label96.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 37) / 37))) - 0.88) / 1000), 2)


                    Label95.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 36) / 37))) - 0.88) / 1000), 2)


                    Label94.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 35) / 37))) - 0.88) / 1000), 2)


                    Label93.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 34) / 37))) - 0.88) / 1000), 2)


                    Label92.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 33) / 37))) - 0.88) / 1000), 2)


                    Label91.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 32) / 37))) - 0.88) / 1000), 2)


                    Label90.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 31) / 37))) - 0.88) / 1000), 2)


                    Label89.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 30) / 37))) - 0.88) / 1000), 2)


                    Label88.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 29) / 37))) - 0.88) / 1000), 2)


                    Label87.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 28) / 37))) - 0.88) / 1000), 2)


                    Label86.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 27) / 37))) - 0.88) / 1000), 2)


                    Label85.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 26) / 37))) - 0.88) / 1000), 2)


                    Label84.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 25) / 37))) - 0.88) / 1000), 2)


                    Label83.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 24) / 37))) - 0.88) / 1000), 2)


                    Label82.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 23) / 37))) - 0.88) / 1000), 2)


                    Label81.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 22) / 37))) - 0.88) / 1000), 2)


                    Label80.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 21) / 37))) - 0.88) / 1000), 2)


                    Label79.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 20) / 37))) - 0.88) / 1000), 2)


                    Label78.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 19) / 37))) - 0.88) / 1000), 2)


                    Label77.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 18) / 37))) - 0.88) / 1000), 2)


                    Label76.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 17) / 37))) - 0.88) / 1000), 2)


                    Label75.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 16) / 37))) - 0.88) / 1000), 2)


                    Label74.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 15) / 37))) - 0.88) / 1000), 2)


                    Label73.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 14) / 37))) - 0.88) / 1000), 2)


                    Label72.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 13) / 37))) - 0.88) / 1000), 2)


                    Label71.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 12) / 37))) - 0.88) / 1000), 2)


                    Label70.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 11) / 37))) - 0.88) / 1000), 2)


                    Label69.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 10) / 37))) - 0.88) / 1000), 2)


                    Label68.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 9) / 37))) - 0.88) / 1000), 2)


                    Label67.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 8) / 37))) - 0.88) / 1000), 2)


                    Label66.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 7) / 37))) - 0.88) / 1000), 2)


                    Label65.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 6) / 37))) - 0.88) / 1000), 2)


                    Label64.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 5) / 37))) - 0.88) / 1000), 2)


                    Label63.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 4) / 37))) - 0.88) / 1000), 2)


                    Label62.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 3) / 37))) - 0.88) / 1000), 2)


                    Label61.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 2) / 37))) - 0.88) / 1000), 2)


                    Label60.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 1) / 37))) - 0.88) / 1000), 2)


                    Label59.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 0) / 37))) - 0.88) / 1000), 2)


                End If



                If TextBox11.Text = 38 Then


                    PictureBox12.Image = My.Resources._10_1


                    Label99.Text = ""


                    Label98.Text = ""


                    Label97.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 38) / 38))) - 0.88) / 1000), 2)


                    Label96.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 37) / 38))) - 0.88) / 1000), 2)


                    Label95.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 36) / 38))) - 0.88) / 1000), 2)


                    Label94.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 35) / 38))) - 0.88) / 1000), 2)


                    Label93.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 34) / 38))) - 0.88) / 1000), 2)


                    Label92.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 33) / 38))) - 0.88) / 1000), 2)


                    Label91.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 32) / 38))) - 0.88) / 1000), 2)


                    Label90.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 31) / 38))) - 0.88) / 1000), 2)


                    Label89.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 30) / 38))) - 0.88) / 1000), 2)


                    Label88.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 29) / 38))) - 0.88) / 1000), 2)


                    Label87.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 28) / 38))) - 0.88) / 1000), 2)


                    Label86.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 27) / 38))) - 0.88) / 1000), 2)


                    Label85.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 26) / 38))) - 0.88) / 1000), 2)


                    Label84.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 25) / 38))) - 0.88) / 1000), 2)


                    Label83.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 24) / 38))) - 0.88) / 1000), 2)


                    Label82.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 23) / 38))) - 0.88) / 1000), 2)


                    Label81.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 22) / 38))) - 0.88) / 1000), 2)


                    Label80.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 21) / 38))) - 0.88) / 1000), 2)


                    Label79.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 20) / 38))) - 0.88) / 1000), 2)


                    Label78.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 19) / 38))) - 0.88) / 1000), 2)


                    Label77.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 18) / 38))) - 0.88) / 1000), 2)


                    Label76.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 17) / 38))) - 0.88) / 1000), 2)


                    Label75.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 16) / 38))) - 0.88) / 1000), 2)


                    Label74.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 15) / 38))) - 0.88) / 1000), 2)


                    Label73.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 14) / 38))) - 0.88) / 1000), 2)


                    Label72.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 13) / 38))) - 0.88) / 1000), 2)


                    Label71.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 12) / 38))) - 0.88) / 1000), 2)


                    Label70.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 11) / 38))) - 0.88) / 1000), 2)


                    Label69.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 10) / 38))) - 0.88) / 1000), 2)


                    Label68.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 9) / 38))) - 0.88) / 1000), 2)


                    Label67.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 8) / 38))) - 0.88) / 1000), 2)


                    Label66.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 7) / 38))) - 0.88) / 1000), 2)


                    Label65.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 6) / 38))) - 0.88) / 1000), 2)


                    Label64.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 5) / 38))) - 0.88) / 1000), 2)


                    Label63.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 4) / 38))) - 0.88) / 1000), 2)


                    Label62.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 3) / 38))) - 0.88) / 1000), 2)


                    Label61.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 2) / 38))) - 0.88) / 1000), 2)


                    Label60.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 1) / 38))) - 0.88) / 1000), 2)


                    Label59.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 0) / 38))) - 0.88) / 1000), 2)


                End If



                If TextBox11.Text = 39 Then


                    PictureBox12.Image = My.Resources._10_3


                    Label99.Text = ""


                    Label98.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 39) / 39))) - 0.88) / 1000), 2)


                    Label97.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 38) / 39))) - 0.88) / 1000), 2)


                    Label96.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 37) / 39))) - 0.88) / 1000), 2)


                    Label95.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 36) / 39))) - 0.88) / 1000), 2)


                    Label94.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 35) / 39))) - 0.88) / 1000), 2)


                    Label93.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 34) / 39))) - 0.88) / 1000), 2)


                    Label92.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 33) / 39))) - 0.88) / 1000), 2)


                    Label91.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 32) / 39))) - 0.88) / 1000), 2)


                    Label90.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 31) / 39))) - 0.88) / 1000), 2)


                    Label89.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 30) / 39))) - 0.88) / 1000), 2)


                    Label88.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 29) / 39))) - 0.88) / 1000), 2)


                    Label87.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 28) / 39))) - 0.88) / 1000), 2)


                    Label86.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 27) / 39))) - 0.88) / 1000), 2)


                    Label85.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 26) / 39))) - 0.88) / 1000), 2)


                    Label84.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 25) / 39))) - 0.88) / 1000), 2)


                    Label83.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 24) / 39))) - 0.88) / 1000), 2)


                    Label82.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 23) / 39))) - 0.88) / 1000), 2)


                    Label81.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 22) / 39))) - 0.88) / 1000), 2)


                    Label80.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 21) / 39))) - 0.88) / 1000), 2)


                    Label79.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 20) / 39))) - 0.88) / 1000), 2)


                    Label78.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 19) / 39))) - 0.88) / 1000), 2)


                    Label77.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 18) / 39))) - 0.88) / 1000), 2)


                    Label76.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 17) / 39))) - 0.88) / 1000), 2)


                    Label75.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 16) / 39))) - 0.88) / 1000), 2)


                    Label74.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 15) / 39))) - 0.88) / 1000), 2)


                    Label73.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 14) / 39))) - 0.88) / 1000), 2)


                    Label72.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 13) / 39))) - 0.88) / 1000), 2)


                    Label71.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 12) / 39))) - 0.88) / 1000), 2)


                    Label70.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 11) / 39))) - 0.88) / 1000), 2)


                    Label69.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 10) / 39))) - 0.88) / 1000), 2)


                    Label68.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 9) / 39))) - 0.88) / 1000), 2)


                    Label67.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 8) / 39))) - 0.88) / 1000), 2)


                    Label66.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 7) / 39))) - 0.88) / 1000), 2)


                    Label65.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 6) / 39))) - 0.88) / 1000), 2)


                    Label64.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 5) / 39))) - 0.88) / 1000), 2)


                    Label63.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 4) / 39))) - 0.88) / 1000), 2)


                    Label62.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 3) / 39))) - 0.88) / 1000), 2)


                    Label61.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 2) / 39))) - 0.88) / 1000), 2)


                    Label60.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 1) / 39))) - 0.88) / 1000), 2)


                    Label59.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 0) / 30))) - 0.88) / 1000), 2)


                End If



                If TextBox11.Text = 40 Then


                    PictureBox12.Image = My.Resources._10_5


                    Label99.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 40) / 40))) - 0.88) / 1000), 2)


                    Label98.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 39) / 40))) - 0.88) / 1000), 2)


                    Label97.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 38) / 40))) - 0.88) / 1000), 2)


                    Label96.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 37) / 40))) - 0.88) / 1000), 2)


                    Label95.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 36) / 40))) - 0.88) / 1000), 2)


                    Label94.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 35) / 40))) - 0.88) / 1000), 2)


                    Label93.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 34) / 40))) - 0.88) / 1000), 2)


                    Label92.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 33) / 40))) - 0.88) / 1000), 2)


                    Label91.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 32) / 40))) - 0.88) / 1000), 2)


                    Label90.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 31) / 40))) - 0.88) / 1000), 2)


                    Label89.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 30) / 40))) - 0.88) / 1000), 2)


                    Label88.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 29) / 40))) - 0.88) / 1000), 2)


                    Label87.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 28) / 40))) - 0.88) / 1000), 2)


                    Label86.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 27) / 40))) - 0.88) / 1000), 2)


                    Label85.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 26) / 40))) - 0.88) / 1000), 2)


                    Label84.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 25) / 40))) - 0.88) / 1000), 2)


                    Label83.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 24) / 40))) - 0.88) / 1000), 2)


                    Label82.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 23) / 40))) - 0.88) / 1000), 2)


                    Label81.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 22) / 40))) - 0.88) / 1000), 2)


                    Label80.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 21) / 40))) - 0.88) / 1000), 2)


                    Label79.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 20) / 40))) - 0.88) / 1000), 2)


                    Label78.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 19) / 40))) - 0.88) / 1000), 2)


                    Label77.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 18) / 40))) - 0.88) / 1000), 2)


                    Label76.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 17) / 40))) - 0.88) / 1000), 2)


                    Label75.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 16) / 40))) - 0.88) / 1000), 2)


                    Label74.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 15) / 40))) - 0.88) / 1000), 2)


                    Label73.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 14) / 40))) - 0.88) / 1000), 2)


                    Label72.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 13) / 40))) - 0.88) / 1000), 2)


                    Label71.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 12) / 40))) - 0.88) / 1000), 2)


                    Label70.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 11) / 40))) - 0.88) / 1000), 2)


                    Label69.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 10) / 40))) - 0.88) / 1000), 2)


                    Label68.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 9) / 40))) - 0.88) / 1000), 2)


                    Label67.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 8) / 40))) - 0.88) / 1000), 2)


                    Label66.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 7) / 40))) - 0.88) / 1000), 2)


                    Label65.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 6) / 40))) - 0.88) / 1000), 2)


                    Label64.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 5) / 40))) - 0.88) / 1000), 2)


                    Label63.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 4) / 40))) - 0.88) / 1000), 2)


                    Label62.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 3) / 40))) - 0.88) / 1000), 2)


                    Label61.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 2) / 40))) - 0.88) / 1000), 2)


                    Label60.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 1) / 40))) - 0.88) / 1000), 2)


                    Label59.Text = Math.Round((165.4 * ((10 ^ (2.1 * ((TextBox11.Text - 0) / 40))) - 0.88) / 1000), 2)


                End If


            End If


        End If



　


        Dim num3 As Decimal


        Dim num4 As Decimal


        Dim num5 As Decimal


        Dim num6 As Decimal


        Dim num7 As Decimal


        Dim num8 As Decimal


        Dim num9 As Decimal


        Dim num10 As Decimal


        Dim num11 As Decimal


        Dim num12 As Decimal


        Dim num13 As Decimal


        Dim num14 As Decimal


        Dim num15 As Decimal


        Dim num16 As Decimal


        Dim num17 As Decimal


        Dim num18 As Decimal


        Dim num19 As Decimal


        Dim num20 As Decimal


        Dim num21 As Decimal


        Dim num22 As Decimal


        Dim num23 As Decimal



        If RadioButton1.Checked = True Then


            Panel1.Visible = True


            PictureBox4.Image = My.Resources.grey_arrow



            If Label18.Text = "" Then


                Label145.Visible = False


            Else


                num3 = (Math.Exp((Label18.Text / 0.9) / (2.62 * ComboBox1.Text)) - 1) * 235


                Label145.Text = num3


            End If



            If Label20.Text = "" Then


                Label146.Visible = False


            Else


                num4 = (Math.Exp((Label20.Text / 0.9) / (2.62 * ComboBox1.Text)) - 1) * 235


                num4 = Math.Round(num4, 0)


                Label146.Text = num4


            End If



            If Label22.Text = "" Then


                Label147.Visible = False


            Else


                num5 = (Math.Exp((Label22.Text / 0.9) / (2.62 * ComboBox1.Text)) - 1) * 235


                num5 = Math.Round(num5, 0)


                Label147.Text = num5


            End If



            If Label24.Text = "" Then


                Label148.Visible = False


            Else


                num6 = (Math.Exp((Label24.Text / 0.9) / (2.62 * ComboBox1.Text)) - 1) * 235


                num6 = Math.Round(num6, 0)


                Label148.Text = num6


            End If



            If Label26.Text = "" Then


                Label149.Visible = False


            Else


                num7 = (Math.Exp((Label26.Text / 0.9) / (2.62 * ComboBox1.Text)) - 1) * 235


                num7 = Math.Round(num7, 0)


                Label149.Text = num7


            End If



            If Label28.Text = "" Then


                Label150.Visible = False


            Else


                num8 = (Math.Exp((Label28.Text / 0.9) / (2.62 * ComboBox1.Text)) - 1) * 235


                num8 = Math.Round(num8, 0)


                Label150.Text = num8


            End If


            If Label30.Text = "" Then


                Label151.Visible = False


            Else


                num9 = (Math.Exp((Label30.Text / 0.9) / (2.62 * ComboBox1.Text)) - 1) * 235


                num9 = Math.Round(num9, 0)


                Label151.Text = num9


            End If



            If Label32.Text = "" Then


                Label152.Visible = False


            Else


                num10 = (Math.Exp((Label32.Text / 0.9) / (2.62 * ComboBox1.Text)) - 1) * 235


                num10 = Math.Round(num10, 0)


                Label152.Text = num10


            End If



            If Label34.Text = "" Then


                Label153.Visible = False


            Else


                num11 = (Math.Exp((Label34.Text / 0.9) / (2.62 * ComboBox1.Text)) - 1) * 235


                num11 = Math.Round(num11, 0)


                Label153.Text = num11


            End If



            If Label36.Text = "" Then


                Label154.Visible = False


            Else


                num12 = (Math.Exp((Label36.Text / 0.9) / (2.62 * ComboBox1.Text)) - 1) * 235


                num12 = Math.Round(num12, 0)


                Label154.Text = num12


            End If



            If Label38.Text = "" Then


                Label155.Visible = False


            Else


                num13 = (Math.Exp((Label38.Text / 0.9) / (2.62 * ComboBox1.Text)) - 1) * 235


                num13 = Math.Round(num13, 0)


                Label155.Text = num13


            End If



            If Label40.Text = "" Then


                Label156.Visible = False


            Else


                num14 = (Math.Exp((Label40.Text / 0.9) / (2.62 * ComboBox1.Text)) - 1) * 235


                num14 = Math.Round(num14, 0)


                Label156.Text = num14


            End If



            If Label42.Text = "" Then


                Label157.Visible = False


            Else


                num15 = (Math.Exp((Label42.Text / 0.9) / (2.62 * ComboBox1.Text)) - 1) * 235


                num15 = Math.Round(num15, 0)


                Label157.Text = num15


            End If



            If Label44.Text = "" Then


                Label158.Visible = False


            Else


                num16 = (Math.Exp((Label44.Text / 0.9) / (2.62 * ComboBox1.Text)) - 1) * 235


                num16 = Math.Round(num16, 0)


                Label158.Text = num16


            End If



            If Label46.Text = "" Then


                Label159.Visible = False


            Else


                num17 = (Math.Exp((Label46.Text / 0.9) / (2.62 * ComboBox1.Text)) - 1) * 235


                num17 = Math.Round(num17, 0)


                Label159.Text = num17


            End If



            If Label48.Text = "" Then


                Label160.Visible = False


            Else


                num18 = (Math.Exp((Label48.Text / 0.9) / (2.62 * ComboBox1.Text)) - 1) * 235


                num18 = Math.Round(num18, 0)


                Label160.Text = num18


            End If



            If Label50.Text = "" Then


                Label161.Visible = False


            Else


                num19 = (Math.Exp((Label50.Text / 0.9) / (2.62 * ComboBox1.Text)) - 1) * 235


                num19 = Math.Round(num19, 0)


                Label161.Text = num19


            End If



            If Label52.Text = "" Then


                Label162.Visible = False


            Else


                num20 = (Math.Exp((Label52.Text / 0.9) / (2.62 * ComboBox1.Text)) - 1) * 235


                num20 = Math.Round(num20, 0)


                Label162.Text = num20


            End If



            If Label54.Text = "" Then


                Label163.Visible = False


            Else


                num21 = (Math.Exp((Label54.Text / 0.9) / (2.62 * ComboBox1.Text)) - 1) * 235


                num21 = Math.Round(num21, 0)


                Label163.Text = num21


            End If



            If Label56.Text = "" Then


                Label164.Visible = False


            Else


                num22 = (Math.Exp((Label56.Text / 0.9) / (2.62 * ComboBox1.Text)) - 1) * 235


                num22 = Math.Round(num22, 0)


                Label164.Text = num22


            End If



            If Label58.Text = "" Then


                Label165.Visible = False


            Else


                num23 = (Math.Exp((Label58.Text / 0.9) / (2.62 * ComboBox1.Text)) - 1) * 235


                num23 = Math.Round(num23, 0)


                Label165.Text = num23


            End If



        End If



        If RadioButton2.Checked = True Then


            Panel1.Visible = True


            PictureBox4.Image = My.Resources.grey_arrow



            If Label18.Text = "" Then


                Label145.Visible = False


            Else


                num3 = (Math.Exp((Label18.Text / 0.9) / (2.62 * ComboBox4.Text)) - 1) * 235


                Label145.Text = num3


            End If



            If Label20.Text = "" Then


                Label146.Visible = False


            Else


                num4 = (Math.Exp((Label20.Text / 0.9) / (2.62 * ComboBox4.Text)) - 1) * 235


                num4 = Math.Round(num4, 0)


                Label146.Text = num4


            End If



            If Label22.Text = "" Then


                Label147.Visible = False


            Else


                num5 = (Math.Exp((Label22.Text / 0.9) / (2.62 * ComboBox4.Text)) - 1) * 235


                num5 = Math.Round(num5, 0)


                Label147.Text = num5


            End If



            If Label24.Text = "" Then


                Label148.Visible = False


            Else


                num6 = (Math.Exp((Label24.Text / 0.9) / (2.62 * ComboBox4.Text)) - 1) * 235


                num6 = Math.Round(num6, 0)


                Label148.Text = num6


            End If



            If Label26.Text = "" Then


                Label149.Visible = False


            Else


                num7 = (Math.Exp((Label26.Text / 0.9) / (2.62 * ComboBox4.Text)) - 1) * 235


                num7 = Math.Round(num7, 0)


                Label149.Text = num7


            End If



            If Label28.Text = "" Then


                Label150.Visible = False


            Else


                num8 = (Math.Exp((Label28.Text / 0.9) / (2.62 * ComboBox4.Text)) - 1) * 235


                num8 = Math.Round(num8, 0)


                Label150.Text = num8


            End If


            If Label30.Text = "" Then


                Label151.Visible = False


            Else


                num9 = (Math.Exp((Label30.Text / 0.9) / (2.62 * ComboBox4.Text)) - 1) * 235


                num9 = Math.Round(num9, 0)


                Label151.Text = num9


            End If



            If Label32.Text = "" Then


                Label152.Visible = False


            Else


                num10 = (Math.Exp((Label32.Text / 0.9) / (2.62 * ComboBox4.Text)) - 1) * 235


                num10 = Math.Round(num10, 0)


                Label152.Text = num10


            End If



            If Label34.Text = "" Then


                Label153.Visible = False


            Else


                num11 = (Math.Exp((Label34.Text / 0.9) / (2.62 * ComboBox4.Text)) - 1) * 235


                num11 = Math.Round(num11, 0)


                Label153.Text = num11


            End If



            If Label36.Text = "" Then


                Label154.Visible = False


            Else


                num12 = (Math.Exp((Label36.Text / 0.9) / (2.62 * ComboBox4.Text)) - 1) * 235


                num12 = Math.Round(num12, 0)


                Label154.Text = num12


            End If



            If Label38.Text = "" Then


                Label155.Visible = False


            Else


                num13 = (Math.Exp((Label38.Text / 0.9) / (2.62 * ComboBox4.Text)) - 1) * 235


                num13 = Math.Round(num13, 0)


                Label155.Text = num13


            End If



            If Label40.Text = "" Then


                Label156.Visible = False


            Else


                num14 = (Math.Exp((Label40.Text / 0.9) / (2.62 * ComboBox4.Text)) - 1) * 235


                num14 = Math.Round(num14, 0)


                Label156.Text = num14


            End If



            If Label42.Text = "" Then


                Label157.Visible = False


            Else


                num15 = (Math.Exp((Label42.Text / 0.9) / (2.62 * ComboBox4.Text)) - 1) * 235


                num15 = Math.Round(num15, 0)


                Label157.Text = num15


            End If



            If Label44.Text = "" Then


                Label158.Visible = False


            Else


                num16 = (Math.Exp((Label44.Text / 0.9) / (2.62 * ComboBox4.Text)) - 1) * 235


                num16 = Math.Round(num16, 0)


                Label158.Text = num16


            End If



            If Label46.Text = "" Then


                Label159.Visible = False


            Else


                num17 = (Math.Exp((Label46.Text / 0.9) / (2.62 * ComboBox4.Text)) - 1) * 235


                num17 = Math.Round(num17, 0)


                Label159.Text = num17


            End If



            If Label48.Text = "" Then


                Label160.Visible = False


            Else


                num18 = (Math.Exp((Label48.Text / 0.9) / (2.62 * ComboBox4.Text)) - 1) * 235


                num18 = Math.Round(num18, 0)


                Label160.Text = num18


            End If



            If Label50.Text = "" Then


                Label161.Visible = False


            Else


                num19 = (Math.Exp((Label50.Text / 0.9) / (2.62 * ComboBox4.Text)) - 1) * 235


                num19 = Math.Round(num19, 0)


                Label161.Text = num19


            End If



            If Label52.Text = "" Then


                Label162.Visible = False


            Else


                num20 = (Math.Exp((Label52.Text / 0.9) / (2.62 * ComboBox4.Text)) - 1) * 235


                num20 = Math.Round(num20, 0)


                Label162.Text = num20


            End If



            If Label54.Text = "" Then


                Label163.Visible = False


            Else


                num21 = (Math.Exp((Label54.Text / 0.9) / (2.62 * ComboBox4.Text)) - 1) * 235


                num21 = Math.Round(num21, 0)


                Label163.Text = num21


            End If



            If Label56.Text = "" Then


                Label164.Visible = False


            Else


                num22 = (Math.Exp((Label56.Text / 0.9) / (2.62 * ComboBox4.Text)) - 1) * 235


                num22 = Math.Round(num22, 0)


                Label164.Text = num22


            End If



            If Label58.Text = "" Then


                Label165.Visible = False


            Else


                num23 = (Math.Exp((Label58.Text / 0.9) / (2.62 * ComboBox4.Text)) - 1) * 235


                num23 = Math.Round(num23, 0)


                Label165.Text = num23


            End If



        End If



　


    End Sub


    'Electrode selection button


    Private Sub Button1_Click(sender As Object, e As EventArgs) Handles Button1.Click


        PictureBox1.Visible = True


        Button7.Enabled = True


        Button9.Enabled = True


        If ComboBox2.SelectedIndex = 0 Then


            PictureBox1.Image = My.Resources.FLEX20


        End If



        If ComboBox2.SelectedIndex = 1 Then


            PictureBox1.Image = My.Resources.FLEX24


        End If



        If ComboBox2.SelectedIndex = 2 Then


            PictureBox1.Image = My.Resources.FLEX26


        End If


        If ComboBox2.SelectedIndex = 3 Then


            PictureBox1.Image = My.Resources.FLEX28


        End If


        If ComboBox2.SelectedIndex = 4 Then


            PictureBox1.Image = My.Resources.FLEXSOFT


        End If


        If ComboBox2.SelectedIndex = 5 Then


            PictureBox1.Image = My.Resources.FLEX34


        End If


        If ComboBox2.SelectedIndex = 6 Then


            PictureBox1.Image = My.Resources.Medium


        End If


        If ComboBox2.SelectedIndex = 7 Then


            PictureBox1.Image = My.Resources.Compressed


        End If


        If ComboBox2.SelectedIndex = 8 Then


            PictureBox1.Image = My.Resources.Cork1_3


        End If


        If ComboBox2.SelectedIndex = 9 Then


            PictureBox1.Image = My.Resources.Cork1_7


        End If



    End Sub



    Private Sub PictureBox1_MouseMove(ByVal sender As Object, ByVal e As System.Windows.Forms.MouseEventArgs) Handles PictureBox1.MouseMove



        Static mousePosX As Single



        If e.Button = 0 Then


            mousePosX = e.X


        Else


            PictureBox1.Left = PictureBox1.Left + (e.X - mousePosX)


        End If



        If PictureBox1.Left >= 200 Then


            mousePosX = e.X


            PictureBox1.Left = 200


        End If



        If PictureBox1.Left <= -40 Then


            mousePosX = e.X


            PictureBox1.Left = -40


        End If



    End Sub



    Private Sub PictureBox10_MouseMove(ByVal sender As Object, ByVal e As System.Windows.Forms.MouseEventArgs) Handles PictureBox10.MouseMove



        Static mousePosX As Single


        If e.Button = 0 Then


            mousePosX = e.X


        Else


            PictureBox10.Left = PictureBox10.Left + (e.X - mousePosX)


        End If


        If PictureBox10.Left >= 886 Then


            mousePosX = e.X


            PictureBox10.Left = 886


        End If


        If PictureBox10.Left <= 130 Then


            mousePosX = e.X


            PictureBox10.Left = 130


        End If



    End Sub



    Private Sub PictureBox11_MouseMove(ByVal sender As Object, ByVal e As System.Windows.Forms.MouseEventArgs) Handles PictureBox11.MouseMove



        Static mousePosX As Single


        If e.Button = 0 Then


            mousePosX = e.X


        Else


            PictureBox11.Left = PictureBox11.Left + (e.X - mousePosX)


        End If


        If PictureBox11.Left >= 908 Then


            mousePosX = e.X


            PictureBox11.Left = 908


        End If


        If PictureBox11.Left <= 130 Then


            mousePosX = e.X


            PictureBox11.Left = 130


        End If



    End Sub



    Private Sub Button6_Click(sender As Object, e As EventArgs) Handles Button6.Click


        RadioButton1.Checked = False


        RadioButton2.Checked = False



        Label110.Visible = False


        Label111.Visible = False


        Label73.BackColor = Color.White


        Label74.BackColor = Color.White


        Label75.BackColor = Color.White


        Label76.BackColor = Color.White


        Label77.BackColor = Color.White


        Label78.BackColor = Color.White


        Label79.BackColor = Color.White


        Label80.BackColor = Color.White


        Label81.BackColor = Color.White


        Label82.BackColor = Color.White


        Label83.BackColor = Color.White


        Label84.BackColor = Color.White


        Label85.BackColor = Color.White


        Label86.BackColor = Color.White


        Label87.BackColor = Color.White


        Label88.BackColor = Color.White


        Label89.BackColor = Color.White


        Label90.BackColor = Color.White


        Label91.BackColor = Color.White


        Label92.BackColor = Color.White


        Label93.BackColor = Color.White


        Label94.BackColor = Color.White


        Label95.BackColor = Color.White


        Label96.BackColor = Color.White


        Label97.BackColor = Color.White


        Label98.BackColor = Color.White


        Label99.BackColor = Color.White


        Panel6.Visible = False


        TextBox4.Visible = False


        Label106.Visible = False


        Label107.Visible = False


        Label105.Visible = False


        PictureBox12.Visible = False


        PictureBox11.Visible = False


        PictureBox10.Visible = False


        Label166.Visible = False


        Label145.Visible = False


        Label146.Visible = False


        Label147.Visible = False


        Label148.Visible = False


        Label149.Visible = False


        Label150.Visible = False


        Label151.Visible = False


        Label152.Visible = False


        Label153.Visible = False


        Label154.Visible = False


        Label155.Visible = False


        Label156.Visible = False


        Label157.Visible = False


        Label158.Visible = False


        Label159.Visible = False


        Label160.Visible = False


        Label161.Visible = False


        Label162.Visible = False


        Label163.Visible = False


        Label164.Visible = False


        Label165.Visible = False



        Label103.Visible = False


        TextBox1.Text = ""


        TextBox2.Text = ""


        PictureBox1.Visible = False


        PictureBox3.Visible = False


        PictureBox4.Visible = False


        PictureBox5.Visible = False


        PictureBox6.Visible = False


        PictureBox7.Visible = False


        Label3.Visible = False


        Label4.Visible = False


        Label99.Text = ""


        Label98.Text = ""


        Label97.Text = ""


        Label96.Text = ""


        Label95.Text = ""


        Label94.Text = ""


        Label93.Text = ""


        Label92.Text = ""


        Label91.Text = ""


        Label90.Text = ""


        Label89.Text = ""


        Label88.Text = ""


        Label87.Text = ""


        Label86.Text = ""


        Label85.Text = ""


        Label84.Text = ""


        Label83.Text = ""


        Label82.Text = ""


        Label81.Text = ""


        Label80.Text = ""


        Label79.Text = ""


        Label78.Text = ""


        Label77.Text = ""


        Label76.Text = ""


        Label75.Text = ""


        Label74.Text = ""


        Label73.Text = ""


        Label72.Text = ""


        Label71.Text = ""


        Label70.Text = ""


        Label69.Text = ""


        Label68.Text = ""


        Label67.Text = ""


        Label66.Text = ""


        Label65.Text = ""


        Label64.Text = ""


        Label63.Text = ""


        Label62.Text = ""


        Label61.Text = ""


        Label60.Text = ""


        Label59.Text = ""


        TextBox5.Text = ""


        TextBox6.Text = ""


        TextBox7.Text = ""


        TextBox8.Text = ""


        TextBox9.Text = ""


        TextBox10.Text = ""


        ComboBox1.Text = ""


        Label18.Text = ""


        Label19.Text = ""


        Label20.Text = ""


        Label21.Text = ""


        Label22.Text = ""


        Label23.Text = ""


        Label24.Text = ""


        Label25.Text = ""


        Label26.Text = ""


        Label27.Text = ""


        Label28.Text = ""


        Label29.Text = ""


        Label30.Text = ""


        Label31.Text = ""


        Label32.Text = ""


        Label33.Text = ""


        Label34.Text = ""


        Label35.Text = ""


        Label36.Text = ""


        Label37.Text = ""


        Label38.Text = ""


        Label39.Text = ""


        Label40.Text = ""


        Label41.Text = ""


        Label42.Text = ""


        Label43.Text = ""


        Label44.Text = ""


        Label45.Text = ""


        Label46.Text = ""


        Label47.Text = ""


        Label48.Text = ""


        Label49.Text = ""


        Label50.Text = ""


        Label51.Text = ""


        Label52.Text = ""


        Label53.Text = ""


        Label54.Text = ""


        Label55.Text = ""


        Label56.Text = ""


        Label57.Text = ""


        Label58.Text = ""


        ComboBox4.Text = ""


        ComboBox5.Text = ""


        Panel1.Visible = False


        Label1.Visible = False


        ComboBox2.Text = "Electrode array"


        Button1.Enabled = False


        Button2.Enabled = False


        Button3.Enabled = False


        Button4.Enabled = False


        Button5.Enabled = False


        Button7.Enabled = False


        Button9.Enabled = False


    End Sub



    Private Sub Button7_Click(sender As Object, e As EventArgs) Handles Button7.Click


        Button9.Enabled = True


        If TextBox6.Text = "" Then


            MsgBox(" Please select an A value ")


        Else



            Dim s As Integer


            Dim t As Decimal



　


            If TextBox1.Text = "" Then


                MsgBox("Please enter the insertion depth")


            Else


                s = TextBox1.Text


                t = Math.Round((TextBox1.Text / TextBox6.Text) * 100, 2)


                TextBox2.Text = t


            End If


        End If



    End Sub



    Private Sub PictureBox7_Click(sender As Object, e As EventArgs) Handles PictureBox7.Click


        PictureBox3.Visible = True


    End Sub



    Private Sub PictureBox6_Click(sender As Object, e As EventArgs) Handles PictureBox6.Click


        Form7.Show()


    End Sub


    Private Sub PictureBox4_Click(sender As Object, e As EventArgs) Handles PictureBox4.Click


        Form8.Show()


    End Sub



    Private Sub Timer1_Tick(sender As Object, e As EventArgs) Handles Timer1.Tick


        If Label101.BackColor = Color.Red Then


            Label101.BackColor = Color.DimGray


        ElseIf Label101.BackColor = Color.DimGray Then


            Label101.BackColor = Color.Red


        End If


    End Sub



    Private Sub Form1_Load(sender As Object, e As EventArgs) Handles MyBase.Load


        Timer1.Enabled = True


    End Sub



    Private Sub textbox7_MouseEnter(ByVal sender As Object, ByVal e As System.EventArgs) Handles TextBox7.MouseEnter


        PictureBox7.Image = My.Resources.CDL_OC_360


    End Sub


    Private Sub textbox7_MouseLeave(ByVal sender As Object, ByVal e As System.EventArgs) Handles TextBox7.MouseLeave


        PictureBox7.Image = My.Resources.CDL_OC


    End Sub


    Private Sub textbox8_MouseEnter(ByVal sender As Object, ByVal e As System.EventArgs) Handles TextBox8.MouseEnter


        PictureBox7.Image = My.Resources.CDL_OC_540


    End Sub


    Private Sub textbox8_MouseLeave(ByVal sender As Object, ByVal e As System.EventArgs) Handles TextBox8.MouseLeave


        PictureBox7.Image = My.Resources.CDL_OC


    End Sub


    Private Sub textbox9_MouseEnter(ByVal sender As Object, ByVal e As System.EventArgs) Handles TextBox9.MouseEnter


        PictureBox7.Image = My.Resources.CDL_OC_720


    End Sub


    Private Sub textbox9_MouseLeave(ByVal sender As Object, ByVal e As System.EventArgs) Handles TextBox9.MouseLeave


        PictureBox7.Image = My.Resources.CDL_OC


    End Sub


    Private Sub Button8_Click(sender As Object, e As EventArgs) Handles Button8.Click


        If ComboBox3.SelectedIndex = 0 Then


            Form2.Show()


        End If


        If ComboBox3.SelectedIndex = 1 Then


            Form3.Show()


        End If


        If ComboBox3.SelectedIndex = 2 Then


            System.Diagnostics.Process.Start("https://www.ncbi.nlm.nih.gov/pubmed/25299827")


        End If



    End Sub



    Private Sub RadioButton1_CheckedChanged(sender As Object, e As EventArgs) Handles RadioButton1.CheckedChanged


        If RadioButton1.Checked = True Then


            RadioButton2.Checked = False


            Label1.Visible = True


            ComboBox1.Visible = True


            ComboBox4.Visible = False


            Button2.Enabled = True


        End If


    End Sub



    Private Sub RadioButton2_CheckedChanged(sender As Object, e As EventArgs) Handles RadioButton2.CheckedChanged


        If RadioButton2.Checked = True Then


            RadioButton1.Checked = False


            ComboBox4.Visible = True


            ComboBox1.Visible = False


            Label1.Visible = True


            Button2.Enabled = True


        End If


    End Sub



    Private Sub Label101_Click(sender As Object, e As EventArgs) Handles Label101.Click


        Form9.Show()


    End Sub



    Private Sub Button9_Click(sender As Object, e As EventArgs) Handles Button9.Click



        If TextBox11.Text = 26 Then


            If ComboBox5.SelectedIndex = 0 Then


                Label73.BackColor = Color.Yellow


                Label74.BackColor = Color.Yellow


                Label75.BackColor = Color.Yellow


                Label76.BackColor = Color.Yellow


                Label77.BackColor = Color.Yellow


                Label78.BackColor = Color.Yellow


                Label79.BackColor = Color.Yellow


                Label80.BackColor = Color.Yellow


                Label81.BackColor = Color.Yellow


                Label82.BackColor = Color.Yellow


                Label83.BackColor = Color.Yellow


                Label84.BackColor = Color.Yellow


                Label85.BackColor = Color.Yellow


                Label86.BackColor = Color.Yellow


                Label87.BackColor = Color.Yellow


                Label88.BackColor = Color.Yellow


                Label89.BackColor = Color.Yellow


                Label90.BackColor = Color.Yellow


                Label91.BackColor = Color.Yellow


                Label92.BackColor = Color.Yellow


                Label93.BackColor = Color.Yellow


                Label94.BackColor = Color.Yellow


                Label95.BackColor = Color.Yellow


                Label96.BackColor = Color.Yellow


                Label97.BackColor = Color.Yellow


                Label98.BackColor = Color.Yellow


                Label99.BackColor = Color.Yellow


            End If



            If ComboBox5.SelectedIndex = 1 Then


                Label73.BackColor = Color.White


                Label74.BackColor = Color.Yellow


                Label75.BackColor = Color.Yellow


                Label76.BackColor = Color.Yellow


                Label77.BackColor = Color.Yellow


                Label78.BackColor = Color.Yellow


                Label79.BackColor = Color.Yellow


                Label80.BackColor = Color.Yellow


                Label81.BackColor = Color.Yellow


                Label82.BackColor = Color.Yellow


                Label83.BackColor = Color.Yellow


                Label84.BackColor = Color.Yellow


                Label85.BackColor = Color.Yellow


                Label86.BackColor = Color.Yellow


                Label87.BackColor = Color.Yellow


                Label88.BackColor = Color.Yellow


                Label89.BackColor = Color.Yellow


                Label90.BackColor = Color.Yellow


                Label91.BackColor = Color.Yellow


                Label92.BackColor = Color.Yellow


                Label93.BackColor = Color.Yellow


                Label94.BackColor = Color.Yellow


                Label95.BackColor = Color.Yellow


                Label96.BackColor = Color.Yellow


                Label97.BackColor = Color.Yellow


                Label98.BackColor = Color.Yellow


                Label99.BackColor = Color.Yellow


            End If



            If ComboBox5.SelectedIndex = 2 Then


                Label73.BackColor = Color.White


                Label74.BackColor = Color.White


                Label75.BackColor = Color.Yellow


                Label76.BackColor = Color.Yellow


                Label77.BackColor = Color.Yellow


                Label78.BackColor = Color.Yellow


                Label79.BackColor = Color.Yellow


                Label80.BackColor = Color.Yellow


                Label81.BackColor = Color.Yellow


                Label82.BackColor = Color.Yellow


                Label83.BackColor = Color.Yellow


                Label84.BackColor = Color.Yellow


                Label85.BackColor = Color.Yellow


                Label86.BackColor = Color.Yellow


                Label87.BackColor = Color.Yellow


                Label88.BackColor = Color.Yellow


                Label89.BackColor = Color.Yellow


                Label90.BackColor = Color.Yellow


                Label91.BackColor = Color.Yellow


                Label92.BackColor = Color.Yellow


                Label93.BackColor = Color.Yellow


                Label94.BackColor = Color.Yellow


                Label95.BackColor = Color.Yellow


                Label96.BackColor = Color.Yellow


                Label97.BackColor = Color.Yellow


                Label98.BackColor = Color.Yellow


                Label99.BackColor = Color.Yellow


            End If



            If ComboBox5.SelectedIndex = 3 Then


                Label73.BackColor = Color.White


                Label74.BackColor = Color.White


                Label75.BackColor = Color.White


                Label76.BackColor = Color.Yellow


                Label77.BackColor = Color.Yellow


                Label78.BackColor = Color.Yellow


                Label79.BackColor = Color.Yellow


                Label80.BackColor = Color.Yellow


                Label81.BackColor = Color.Yellow


                Label82.BackColor = Color.Yellow


                Label83.BackColor = Color.Yellow


                Label84.BackColor = Color.Yellow


                Label85.BackColor = Color.Yellow


                Label86.BackColor = Color.Yellow


                Label87.BackColor = Color.Yellow


                Label88.BackColor = Color.Yellow


                Label89.BackColor = Color.Yellow


                Label90.BackColor = Color.Yellow


                Label91.BackColor = Color.Yellow


                Label92.BackColor = Color.Yellow


                Label93.BackColor = Color.Yellow


                Label94.BackColor = Color.Yellow


                Label95.BackColor = Color.Yellow


                Label96.BackColor = Color.Yellow


                Label97.BackColor = Color.Yellow


                Label98.BackColor = Color.Yellow


                Label99.BackColor = Color.Yellow


            End If



            If ComboBox5.SelectedIndex = 4 Then


                Label73.BackColor = Color.White


                Label74.BackColor = Color.White


                Label75.BackColor = Color.White


                Label76.BackColor = Color.White


                Label77.BackColor = Color.White


                Label78.BackColor = Color.Yellow


                Label79.BackColor = Color.Yellow


                Label80.BackColor = Color.Yellow


                Label81.BackColor = Color.Yellow


                Label82.BackColor = Color.Yellow


                Label83.BackColor = Color.Yellow


                Label84.BackColor = Color.Yellow


                Label85.BackColor = Color.Yellow


                Label86.BackColor = Color.Yellow


                Label87.BackColor = Color.Yellow


                Label88.BackColor = Color.Yellow


                Label89.BackColor = Color.Yellow


                Label90.BackColor = Color.Yellow


                Label91.BackColor = Color.Yellow


                Label92.BackColor = Color.Yellow


                Label93.BackColor = Color.Yellow


                Label94.BackColor = Color.Yellow


                Label95.BackColor = Color.Yellow


                Label96.BackColor = Color.Yellow


                Label97.BackColor = Color.Yellow


                Label98.BackColor = Color.Yellow


                Label99.BackColor = Color.Yellow


            End If



            If ComboBox5.SelectedIndex = 5 Then


                Label73.BackColor = Color.White


                Label74.BackColor = Color.White


                Label75.BackColor = Color.White


                Label76.BackColor = Color.White


                Label77.BackColor = Color.White


                Label78.BackColor = Color.White


                Label79.BackColor = Color.White


                Label80.BackColor = Color.White


                Label81.BackColor = Color.Yellow


                Label82.BackColor = Color.Yellow


                Label83.BackColor = Color.Yellow


                Label84.BackColor = Color.Yellow


                Label85.BackColor = Color.Yellow


                Label86.BackColor = Color.Yellow


                Label87.BackColor = Color.Yellow


                Label88.BackColor = Color.Yellow


                Label89.BackColor = Color.Yellow


                Label90.BackColor = Color.Yellow


                Label91.BackColor = Color.Yellow


                Label92.BackColor = Color.Yellow


                Label93.BackColor = Color.Yellow


                Label94.BackColor = Color.Yellow


                Label95.BackColor = Color.Yellow


                Label96.BackColor = Color.Yellow


                Label97.BackColor = Color.Yellow


                Label98.BackColor = Color.Yellow


                Label99.BackColor = Color.Yellow


            End If


        End If



        If TextBox11.Text = 27 Then


            If ComboBox5.SelectedIndex = 0 Then


                Label73.BackColor = Color.Yellow


                Label74.BackColor = Color.Yellow


                Label75.BackColor = Color.Yellow


                Label76.BackColor = Color.Yellow


                Label77.BackColor = Color.Yellow


                Label78.BackColor = Color.Yellow


                Label79.BackColor = Color.Yellow


                Label80.BackColor = Color.Yellow


                Label81.BackColor = Color.Yellow


                Label82.BackColor = Color.Yellow


                Label83.BackColor = Color.Yellow


                Label84.BackColor = Color.Yellow


                Label85.BackColor = Color.Yellow


                Label86.BackColor = Color.Yellow


                Label87.BackColor = Color.Yellow


                Label88.BackColor = Color.Yellow


                Label89.BackColor = Color.Yellow


                Label90.BackColor = Color.Yellow


                Label91.BackColor = Color.Yellow


                Label92.BackColor = Color.Yellow


                Label93.BackColor = Color.Yellow


                Label94.BackColor = Color.Yellow


                Label95.BackColor = Color.Yellow


                Label96.BackColor = Color.Yellow


                Label97.BackColor = Color.Yellow


                Label98.BackColor = Color.Yellow


                Label99.BackColor = Color.Yellow


            End If



            If ComboBox5.SelectedIndex = 1 Then


                Label73.BackColor = Color.White


                Label74.BackColor = Color.Yellow


                Label75.BackColor = Color.Yellow


                Label76.BackColor = Color.Yellow


                Label77.BackColor = Color.Yellow


                Label78.BackColor = Color.Yellow


                Label79.BackColor = Color.Yellow


                Label80.BackColor = Color.Yellow


                Label81.BackColor = Color.Yellow


                Label82.BackColor = Color.Yellow


                Label83.BackColor = Color.Yellow


                Label84.BackColor = Color.Yellow


                Label85.BackColor = Color.Yellow


                Label86.BackColor = Color.Yellow


                Label87.BackColor = Color.Yellow


                Label88.BackColor = Color.Yellow


                Label89.BackColor = Color.Yellow


                Label90.BackColor = Color.Yellow


                Label91.BackColor = Color.Yellow


                Label92.BackColor = Color.Yellow


                Label93.BackColor = Color.Yellow


                Label94.BackColor = Color.Yellow


                Label95.BackColor = Color.Yellow


                Label96.BackColor = Color.Yellow


                Label97.BackColor = Color.Yellow


                Label98.BackColor = Color.Yellow


                Label99.BackColor = Color.Yellow


            End If



            If ComboBox5.SelectedIndex = 2 Then


                Label73.BackColor = Color.White


                Label74.BackColor = Color.White


                Label75.BackColor = Color.White


                Label76.BackColor = Color.Yellow


                Label77.BackColor = Color.Yellow


                Label78.BackColor = Color.Yellow


                Label79.BackColor = Color.Yellow


                Label80.BackColor = Color.Yellow


                Label81.BackColor = Color.Yellow


                Label82.BackColor = Color.Yellow


                Label83.BackColor = Color.Yellow


                Label84.BackColor = Color.Yellow


                Label85.BackColor = Color.Yellow


                Label86.BackColor = Color.Yellow


                Label87.BackColor = Color.Yellow


                Label88.BackColor = Color.Yellow


                Label89.BackColor = Color.Yellow


                Label90.BackColor = Color.Yellow


                Label91.BackColor = Color.Yellow


                Label92.BackColor = Color.Yellow


                Label93.BackColor = Color.Yellow


                Label94.BackColor = Color.Yellow


                Label95.BackColor = Color.Yellow


                Label96.BackColor = Color.Yellow


                Label97.BackColor = Color.Yellow


                Label98.BackColor = Color.Yellow


                Label99.BackColor = Color.Yellow


            End If



            If ComboBox5.SelectedIndex = 3 Then


                Label73.BackColor = Color.White


                Label74.BackColor = Color.White


                Label75.BackColor = Color.White


                Label76.BackColor = Color.White


                Label77.BackColor = Color.Yellow


                Label78.BackColor = Color.Yellow


                Label79.BackColor = Color.Yellow


                Label80.BackColor = Color.Yellow


                Label81.BackColor = Color.Yellow


                Label82.BackColor = Color.Yellow


                Label83.BackColor = Color.Yellow


                Label84.BackColor = Color.Yellow


                Label85.BackColor = Color.Yellow


                Label86.BackColor = Color.Yellow


                Label87.BackColor = Color.Yellow


                Label88.BackColor = Color.Yellow


                Label89.BackColor = Color.Yellow


                Label90.BackColor = Color.Yellow


                Label91.BackColor = Color.Yellow


                Label92.BackColor = Color.Yellow


                Label93.BackColor = Color.Yellow


                Label94.BackColor = Color.Yellow


                Label95.BackColor = Color.Yellow


                Label96.BackColor = Color.Yellow


                Label97.BackColor = Color.Yellow


                Label98.BackColor = Color.Yellow


                Label99.BackColor = Color.Yellow


            End If



            If ComboBox5.SelectedIndex = 4 Then


                Label73.BackColor = Color.White


                Label74.BackColor = Color.White


                Label75.BackColor = Color.White


                Label76.BackColor = Color.White


                Label77.BackColor = Color.White


                Label78.BackColor = Color.Yellow


                Label79.BackColor = Color.Yellow


                Label80.BackColor = Color.Yellow


                Label81.BackColor = Color.Yellow


                Label82.BackColor = Color.Yellow


                Label83.BackColor = Color.Yellow


                Label84.BackColor = Color.Yellow


                Label85.BackColor = Color.Yellow


                Label86.BackColor = Color.Yellow


                Label87.BackColor = Color.Yellow


                Label88.BackColor = Color.Yellow


                Label89.BackColor = Color.Yellow


                Label90.BackColor = Color.Yellow


                Label91.BackColor = Color.Yellow


                Label92.BackColor = Color.Yellow


                Label93.BackColor = Color.Yellow


                Label94.BackColor = Color.Yellow


                Label95.BackColor = Color.Yellow


                Label96.BackColor = Color.Yellow


                Label97.BackColor = Color.Yellow


                Label98.BackColor = Color.Yellow


                Label99.BackColor = Color.Yellow


            End If



            If ComboBox5.SelectedIndex = 5 Then


                Label73.BackColor = Color.White


                Label74.BackColor = Color.White


                Label75.BackColor = Color.White


                Label76.BackColor = Color.White


                Label77.BackColor = Color.White


                Label78.BackColor = Color.White


                Label79.BackColor = Color.White


                Label80.BackColor = Color.White


                Label81.BackColor = Color.Yellow


                Label82.BackColor = Color.Yellow


                Label83.BackColor = Color.Yellow


                Label84.BackColor = Color.Yellow


                Label85.BackColor = Color.Yellow


                Label86.BackColor = Color.Yellow


                Label87.BackColor = Color.Yellow


                Label88.BackColor = Color.Yellow


                Label89.BackColor = Color.Yellow


                Label90.BackColor = Color.Yellow


                Label91.BackColor = Color.Yellow


                Label92.BackColor = Color.Yellow


                Label93.BackColor = Color.Yellow


                Label94.BackColor = Color.Yellow


                Label95.BackColor = Color.Yellow


                Label96.BackColor = Color.Yellow


                Label97.BackColor = Color.Yellow


                Label98.BackColor = Color.Yellow


                Label99.BackColor = Color.Yellow


            End If


        End If



        If TextBox11.Text = 28 Then


            If ComboBox5.SelectedIndex = 0 Then


                Label73.BackColor = Color.White


                Label74.BackColor = Color.Yellow


                Label75.BackColor = Color.Yellow


                Label76.BackColor = Color.Yellow


                Label77.BackColor = Color.Yellow


                Label78.BackColor = Color.Yellow


                Label79.BackColor = Color.Yellow


                Label80.BackColor = Color.Yellow


                Label81.BackColor = Color.Yellow


                Label82.BackColor = Color.Yellow


                Label83.BackColor = Color.Yellow


                Label84.BackColor = Color.Yellow


                Label85.BackColor = Color.Yellow


                Label86.BackColor = Color.Yellow


                Label87.BackColor = Color.Yellow


                Label88.BackColor = Color.Yellow


                Label89.BackColor = Color.Yellow


                Label90.BackColor = Color.Yellow


                Label91.BackColor = Color.Yellow


                Label92.BackColor = Color.Yellow


                Label93.BackColor = Color.Yellow


                Label94.BackColor = Color.Yellow


                Label95.BackColor = Color.Yellow


                Label96.BackColor = Color.Yellow


                Label97.BackColor = Color.Yellow


                Label98.BackColor = Color.Yellow


                Label99.BackColor = Color.Yellow


            End If



            If ComboBox5.SelectedIndex = 1 Then


                Label73.BackColor = Color.White


                Label74.BackColor = Color.White


                Label75.BackColor = Color.Yellow


                Label76.BackColor = Color.Yellow


                Label77.BackColor = Color.Yellow


                Label78.BackColor = Color.Yellow


                Label79.BackColor = Color.Yellow


                Label80.BackColor = Color.Yellow


                Label81.BackColor = Color.Yellow


                Label82.BackColor = Color.Yellow


                Label83.BackColor = Color.Yellow


                Label84.BackColor = Color.Yellow


                Label85.BackColor = Color.Yellow


                Label86.BackColor = Color.Yellow


                Label87.BackColor = Color.Yellow


                Label88.BackColor = Color.Yellow


                Label89.BackColor = Color.Yellow


                Label90.BackColor = Color.Yellow


                Label91.BackColor = Color.Yellow


                Label92.BackColor = Color.Yellow


                Label93.BackColor = Color.Yellow


                Label94.BackColor = Color.Yellow


                Label95.BackColor = Color.Yellow


                Label96.BackColor = Color.Yellow


                Label97.BackColor = Color.Yellow


                Label98.BackColor = Color.Yellow


                Label99.BackColor = Color.Yellow


            End If



            If ComboBox5.SelectedIndex = 2 Then


                Label73.BackColor = Color.White


                Label74.BackColor = Color.White


                Label75.BackColor = Color.White


                Label76.BackColor = Color.Yellow


                Label77.BackColor = Color.Yellow


                Label78.BackColor = Color.Yellow


                Label79.BackColor = Color.Yellow


                Label80.BackColor = Color.Yellow


                Label81.BackColor = Color.Yellow


                Label82.BackColor = Color.Yellow


                Label83.BackColor = Color.Yellow


                Label84.BackColor = Color.Yellow


                Label85.BackColor = Color.Yellow


                Label86.BackColor = Color.Yellow


                Label87.BackColor = Color.Yellow


                Label88.BackColor = Color.Yellow


                Label89.BackColor = Color.Yellow


                Label90.BackColor = Color.Yellow


                Label91.BackColor = Color.Yellow


                Label92.BackColor = Color.Yellow


                Label93.BackColor = Color.Yellow


                Label94.BackColor = Color.Yellow


                Label95.BackColor = Color.Yellow


                Label96.BackColor = Color.Yellow


                Label97.BackColor = Color.Yellow


                Label98.BackColor = Color.Yellow


                Label99.BackColor = Color.Yellow


            End If



            If ComboBox5.SelectedIndex = 3 Then


                Label73.BackColor = Color.White


                Label74.BackColor = Color.White


                Label75.BackColor = Color.White


                Label76.BackColor = Color.White


                Label77.BackColor = Color.Yellow


                Label78.BackColor = Color.Yellow


                Label79.BackColor = Color.Yellow


                Label80.BackColor = Color.Yellow


                Label81.BackColor = Color.Yellow


                Label82.BackColor = Color.Yellow


                Label83.BackColor = Color.Yellow


                Label84.BackColor = Color.Yellow


                Label85.BackColor = Color.Yellow


                Label86.BackColor = Color.Yellow


                Label87.BackColor = Color.Yellow


                Label88.BackColor = Color.Yellow


                Label89.BackColor = Color.Yellow


                Label90.BackColor = Color.Yellow


                Label91.BackColor = Color.Yellow


                Label92.BackColor = Color.Yellow


                Label93.BackColor = Color.Yellow


                Label94.BackColor = Color.Yellow


                Label95.BackColor = Color.Yellow


                Label96.BackColor = Color.Yellow


                Label97.BackColor = Color.Yellow


                Label98.BackColor = Color.Yellow


                Label99.BackColor = Color.Yellow


            End If



            If ComboBox5.SelectedIndex = 4 Then


                Label73.BackColor = Color.White


                Label74.BackColor = Color.White


                Label75.BackColor = Color.White


                Label76.BackColor = Color.White


                Label77.BackColor = Color.White


                Label78.BackColor = Color.White


                Label79.BackColor = Color.Yellow


                Label80.BackColor = Color.Yellow


                Label81.BackColor = Color.Yellow


                Label82.BackColor = Color.Yellow


                Label83.BackColor = Color.Yellow


                Label84.BackColor = Color.Yellow


                Label85.BackColor = Color.Yellow


                Label86.BackColor = Color.Yellow


                Label87.BackColor = Color.Yellow


                Label88.BackColor = Color.Yellow


                Label89.BackColor = Color.Yellow


                Label90.BackColor = Color.Yellow


                Label91.BackColor = Color.Yellow


                Label92.BackColor = Color.Yellow


                Label93.BackColor = Color.Yellow


                Label94.BackColor = Color.Yellow


                Label95.BackColor = Color.Yellow


                Label96.BackColor = Color.Yellow


                Label97.BackColor = Color.Yellow


                Label98.BackColor = Color.Yellow


                Label99.BackColor = Color.Yellow


            End If



            If ComboBox5.SelectedIndex = 5 Then


                Label73.BackColor = Color.White


                Label74.BackColor = Color.White


                Label75.BackColor = Color.White


                Label76.BackColor = Color.White


                Label77.BackColor = Color.White


                Label78.BackColor = Color.White


                Label79.BackColor = Color.White


                Label80.BackColor = Color.White


                Label81.BackColor = Color.White


                Label82.BackColor = Color.Yellow


                Label83.BackColor = Color.Yellow


                Label84.BackColor = Color.Yellow


                Label85.BackColor = Color.Yellow


                Label86.BackColor = Color.Yellow


                Label87.BackColor = Color.Yellow


                Label88.BackColor = Color.Yellow


                Label89.BackColor = Color.Yellow


                Label90.BackColor = Color.Yellow


                Label91.BackColor = Color.Yellow


                Label92.BackColor = Color.Yellow


                Label93.BackColor = Color.Yellow


                Label94.BackColor = Color.Yellow


                Label95.BackColor = Color.Yellow


                Label96.BackColor = Color.Yellow


                Label97.BackColor = Color.Yellow


                Label98.BackColor = Color.Yellow


                Label99.BackColor = Color.Yellow


            End If


        End If



        If TextBox11.Text = 29 Then


            If ComboBox5.SelectedIndex = 0 Then


                Label73.BackColor = Color.White


                Label74.BackColor = Color.Yellow


                Label75.BackColor = Color.Yellow


                Label76.BackColor = Color.Yellow


                Label77.BackColor = Color.Yellow


                Label78.BackColor = Color.Yellow


                Label79.BackColor = Color.Yellow


                Label80.BackColor = Color.Yellow


                Label81.BackColor = Color.Yellow


                Label82.BackColor = Color.Yellow


                Label83.BackColor = Color.Yellow


                Label84.BackColor = Color.Yellow


                Label85.BackColor = Color.Yellow


                Label86.BackColor = Color.Yellow


                Label87.BackColor = Color.Yellow


                Label88.BackColor = Color.Yellow


                Label89.BackColor = Color.Yellow


                Label90.BackColor = Color.Yellow


                Label91.BackColor = Color.Yellow


                Label92.BackColor = Color.Yellow


                Label93.BackColor = Color.Yellow


                Label94.BackColor = Color.Yellow


                Label95.BackColor = Color.Yellow


                Label96.BackColor = Color.Yellow


                Label97.BackColor = Color.Yellow


                Label98.BackColor = Color.Yellow


                Label99.BackColor = Color.Yellow


            End If



            If ComboBox5.SelectedIndex = 1 Then


                Label73.BackColor = Color.White


                Label74.BackColor = Color.White


                Label75.BackColor = Color.Yellow


                Label76.BackColor = Color.Yellow


                Label77.BackColor = Color.Yellow


                Label78.BackColor = Color.Yellow


                Label79.BackColor = Color.Yellow


                Label80.BackColor = Color.Yellow


                Label81.BackColor = Color.Yellow


                Label82.BackColor = Color.Yellow


                Label83.BackColor = Color.Yellow


                Label84.BackColor = Color.Yellow


                Label85.BackColor = Color.Yellow


                Label86.BackColor = Color.Yellow


                Label87.BackColor = Color.Yellow


                Label88.BackColor = Color.Yellow


                Label89.BackColor = Color.Yellow


                Label90.BackColor = Color.Yellow


                Label91.BackColor = Color.Yellow


                Label92.BackColor = Color.Yellow


                Label93.BackColor = Color.Yellow


                Label94.BackColor = Color.Yellow


                Label95.BackColor = Color.Yellow


                Label96.BackColor = Color.Yellow


                Label97.BackColor = Color.Yellow


                Label98.BackColor = Color.Yellow


                Label99.BackColor = Color.Yellow


            End If



            If ComboBox5.SelectedIndex = 2 Then


                Label73.BackColor = Color.White


                Label74.BackColor = Color.White


                Label75.BackColor = Color.White


                Label76.BackColor = Color.Yellow


                Label77.BackColor = Color.Yellow


                Label78.BackColor = Color.Yellow


                Label79.BackColor = Color.Yellow


                Label80.BackColor = Color.Yellow


                Label81.BackColor = Color.Yellow


                Label82.BackColor = Color.Yellow


                Label83.BackColor = Color.Yellow


                Label84.BackColor = Color.Yellow


                Label85.BackColor = Color.Yellow


                Label86.BackColor = Color.Yellow


                Label87.BackColor = Color.Yellow


                Label88.BackColor = Color.Yellow


                Label89.BackColor = Color.Yellow


                Label90.BackColor = Color.Yellow


                Label91.BackColor = Color.Yellow


                Label92.BackColor = Color.Yellow


                Label93.BackColor = Color.Yellow


                Label94.BackColor = Color.Yellow


                Label95.BackColor = Color.Yellow


                Label96.BackColor = Color.Yellow


                Label97.BackColor = Color.Yellow


                Label98.BackColor = Color.Yellow


                Label99.BackColor = Color.Yellow


            End If



            If ComboBox5.SelectedIndex = 3 Then


                Label73.BackColor = Color.White


                Label74.BackColor = Color.White


                Label75.BackColor = Color.White


                Label76.BackColor = Color.White


                Label77.BackColor = Color.White


                Label78.BackColor = Color.Yellow


                Label79.BackColor = Color.Yellow


                Label80.BackColor = Color.Yellow


                Label81.BackColor = Color.Yellow


                Label82.BackColor = Color.Yellow


                Label83.BackColor = Color.Yellow


                Label84.BackColor = Color.Yellow


                Label85.BackColor = Color.Yellow


                Label86.BackColor = Color.Yellow


                Label87.BackColor = Color.Yellow


                Label88.BackColor = Color.Yellow


                Label89.BackColor = Color.Yellow


                Label90.BackColor = Color.Yellow


                Label91.BackColor = Color.Yellow


                Label92.BackColor = Color.Yellow


                Label93.BackColor = Color.Yellow


                Label94.BackColor = Color.Yellow


                Label95.BackColor = Color.Yellow


                Label96.BackColor = Color.Yellow


                Label97.BackColor = Color.Yellow


                Label98.BackColor = Color.Yellow


                Label99.BackColor = Color.Yellow


            End If



            If ComboBox5.SelectedIndex = 4 Then


                Label73.BackColor = Color.White


                Label74.BackColor = Color.White


                Label75.BackColor = Color.White


                Label76.BackColor = Color.White


                Label77.BackColor = Color.White


                Label78.BackColor = Color.White


                Label79.BackColor = Color.White


                Label80.BackColor = Color.Yellow


                Label81.BackColor = Color.Yellow


                Label82.BackColor = Color.Yellow


                Label83.BackColor = Color.Yellow


                Label84.BackColor = Color.Yellow


                Label85.BackColor = Color.Yellow


                Label86.BackColor = Color.Yellow


                Label87.BackColor = Color.Yellow


                Label88.BackColor = Color.Yellow


                Label89.BackColor = Color.Yellow


                Label90.BackColor = Color.Yellow


                Label91.BackColor = Color.Yellow


                Label92.BackColor = Color.Yellow


                Label93.BackColor = Color.Yellow


                Label94.BackColor = Color.Yellow


                Label95.BackColor = Color.Yellow


                Label96.BackColor = Color.Yellow


                Label97.BackColor = Color.Yellow


                Label98.BackColor = Color.Yellow


                Label99.BackColor = Color.Yellow


            End If



            If ComboBox5.SelectedIndex = 5 Then


                Label73.BackColor = Color.White


                Label74.BackColor = Color.White


                Label75.BackColor = Color.White


                Label76.BackColor = Color.White


                Label77.BackColor = Color.White


                Label78.BackColor = Color.White


                Label79.BackColor = Color.White


                Label80.BackColor = Color.White


                Label81.BackColor = Color.White


                Label82.BackColor = Color.White


                Label83.BackColor = Color.Yellow


                Label84.BackColor = Color.Yellow


                Label85.BackColor = Color.Yellow


                Label86.BackColor = Color.Yellow


                Label87.BackColor = Color.Yellow


                Label88.BackColor = Color.Yellow


                Label89.BackColor = Color.Yellow


                Label90.BackColor = Color.Yellow


                Label91.BackColor = Color.Yellow


                Label92.BackColor = Color.Yellow


                Label93.BackColor = Color.Yellow


                Label94.BackColor = Color.Yellow


                Label95.BackColor = Color.Yellow


                Label96.BackColor = Color.Yellow


                Label97.BackColor = Color.Yellow


                Label98.BackColor = Color.Yellow


                Label99.BackColor = Color.Yellow


            End If


        End If



        If TextBox11.Text = 30 Then


            If ComboBox5.SelectedIndex = 0 Then


                Label73.BackColor = Color.White


                Label74.BackColor = Color.White


                Label75.BackColor = Color.Yellow


                Label76.BackColor = Color.Yellow


                Label77.BackColor = Color.Yellow


                Label78.BackColor = Color.Yellow


                Label79.BackColor = Color.Yellow


                Label80.BackColor = Color.Yellow


                Label81.BackColor = Color.Yellow


                Label82.BackColor = Color.Yellow


                Label83.BackColor = Color.Yellow


                Label84.BackColor = Color.Yellow


                Label85.BackColor = Color.Yellow


                Label86.BackColor = Color.Yellow


                Label87.BackColor = Color.Yellow


                Label88.BackColor = Color.Yellow


                Label89.BackColor = Color.Yellow


                Label90.BackColor = Color.Yellow


                Label91.BackColor = Color.Yellow


                Label92.BackColor = Color.Yellow


                Label93.BackColor = Color.Yellow


                Label94.BackColor = Color.Yellow


                Label95.BackColor = Color.Yellow


                Label96.BackColor = Color.Yellow


                Label97.BackColor = Color.Yellow


                Label98.BackColor = Color.Yellow


                Label99.BackColor = Color.Yellow


            End If



            If ComboBox5.SelectedIndex = 1 Then


                Label73.BackColor = Color.White


                Label74.BackColor = Color.White


                Label75.BackColor = Color.White


                Label76.BackColor = Color.Yellow


                Label77.BackColor = Color.Yellow


                Label78.BackColor = Color.Yellow


                Label79.BackColor = Color.Yellow


                Label80.BackColor = Color.Yellow


                Label81.BackColor = Color.Yellow


                Label82.BackColor = Color.Yellow


                Label83.BackColor = Color.Yellow


                Label84.BackColor = Color.Yellow


                Label85.BackColor = Color.Yellow


                Label86.BackColor = Color.Yellow


                Label87.BackColor = Color.Yellow


                Label88.BackColor = Color.Yellow


                Label89.BackColor = Color.Yellow


                Label90.BackColor = Color.Yellow


                Label91.BackColor = Color.Yellow


                Label92.BackColor = Color.Yellow


                Label93.BackColor = Color.Yellow


                Label94.BackColor = Color.Yellow


                Label95.BackColor = Color.Yellow


                Label96.BackColor = Color.Yellow


                Label97.BackColor = Color.Yellow


                Label98.BackColor = Color.Yellow


                Label99.BackColor = Color.Yellow


            End If



            If ComboBox5.SelectedIndex = 2 Then


                Label73.BackColor = Color.White


                Label74.BackColor = Color.White


                Label75.BackColor = Color.White


                Label76.BackColor = Color.White


                Label77.BackColor = Color.Yellow


                Label78.BackColor = Color.Yellow


                Label79.BackColor = Color.Yellow


                Label80.BackColor = Color.Yellow


                Label81.BackColor = Color.Yellow


                Label82.BackColor = Color.Yellow


                Label83.BackColor = Color.Yellow


                Label84.BackColor = Color.Yellow


                Label85.BackColor = Color.Yellow


                Label86.BackColor = Color.Yellow


                Label87.BackColor = Color.Yellow


                Label88.BackColor = Color.Yellow


                Label89.BackColor = Color.Yellow


                Label90.BackColor = Color.Yellow


                Label91.BackColor = Color.Yellow


                Label92.BackColor = Color.Yellow


                Label93.BackColor = Color.Yellow


                Label94.BackColor = Color.Yellow


                Label95.BackColor = Color.Yellow


                Label96.BackColor = Color.Yellow


                Label97.BackColor = Color.Yellow


                Label98.BackColor = Color.Yellow


                Label99.BackColor = Color.Yellow


            End If



            If ComboBox5.SelectedIndex = 3 Then


                Label73.BackColor = Color.White


                Label74.BackColor = Color.White


                Label75.BackColor = Color.White


                Label76.BackColor = Color.White


                Label77.BackColor = Color.White


                Label78.BackColor = Color.White


                Label79.BackColor = Color.Yellow


                Label80.BackColor = Color.Yellow


                Label81.BackColor = Color.Yellow


                Label82.BackColor = Color.Yellow


                Label83.BackColor = Color.Yellow


                Label84.BackColor = Color.Yellow


                Label85.BackColor = Color.Yellow


                Label86.BackColor = Color.Yellow


                Label87.BackColor = Color.Yellow


                Label88.BackColor = Color.Yellow


                Label89.BackColor = Color.Yellow


                Label90.BackColor = Color.Yellow


                Label91.BackColor = Color.Yellow


                Label92.BackColor = Color.Yellow


                Label93.BackColor = Color.Yellow


                Label94.BackColor = Color.Yellow


                Label95.BackColor = Color.Yellow


                Label96.BackColor = Color.Yellow


                Label97.BackColor = Color.Yellow


                Label98.BackColor = Color.Yellow


                Label99.BackColor = Color.Yellow


            End If



            If ComboBox5.SelectedIndex = 4 Then


                Label73.BackColor = Color.White


                Label74.BackColor = Color.White


                Label75.BackColor = Color.White


                Label76.BackColor = Color.White


                Label77.BackColor = Color.White


                Label78.BackColor = Color.White


                Label79.BackColor = Color.White


                Label80.BackColor = Color.White


                Label81.BackColor = Color.Yellow


                Label82.BackColor = Color.Yellow


                Label83.BackColor = Color.Yellow


                Label84.BackColor = Color.Yellow


                Label85.BackColor = Color.Yellow


                Label86.BackColor = Color.Yellow


                Label87.BackColor = Color.Yellow


                Label88.BackColor = Color.Yellow


                Label89.BackColor = Color.Yellow


                Label90.BackColor = Color.Yellow


                Label91.BackColor = Color.Yellow


                Label92.BackColor = Color.Yellow


                Label93.BackColor = Color.Yellow


                Label94.BackColor = Color.Yellow


                Label95.BackColor = Color.Yellow


                Label96.BackColor = Color.Yellow


                Label97.BackColor = Color.Yellow


                Label98.BackColor = Color.Yellow


                Label99.BackColor = Color.Yellow


            End If



            If ComboBox5.SelectedIndex = 5 Then


                Label73.BackColor = Color.White


                Label74.BackColor = Color.White


                Label75.BackColor = Color.White


                Label76.BackColor = Color.White


                Label77.BackColor = Color.White


                Label78.BackColor = Color.White


                Label79.BackColor = Color.White


                Label80.BackColor = Color.White


                Label81.BackColor = Color.White


                Label82.BackColor = Color.White


                Label83.BackColor = Color.White


                Label84.BackColor = Color.Yellow


                Label85.BackColor = Color.Yellow


                Label86.BackColor = Color.Yellow


                Label87.BackColor = Color.Yellow


                Label88.BackColor = Color.Yellow


                Label89.BackColor = Color.Yellow


                Label90.BackColor = Color.Yellow


                Label91.BackColor = Color.Yellow


                Label92.BackColor = Color.Yellow


                Label93.BackColor = Color.Yellow


                Label94.BackColor = Color.Yellow


                Label95.BackColor = Color.Yellow


                Label96.BackColor = Color.Yellow


                Label97.BackColor = Color.Yellow


                Label98.BackColor = Color.Yellow


                Label99.BackColor = Color.Yellow


            End If


        End If



        If TextBox11.Text = 31 Then


            If ComboBox5.SelectedIndex = 0 Then


                Label73.BackColor = Color.White


                Label74.BackColor = Color.White


                Label75.BackColor = Color.Yellow


                Label76.BackColor = Color.Yellow


                Label77.BackColor = Color.Yellow


                Label78.BackColor = Color.Yellow


                Label79.BackColor = Color.Yellow


                Label80.BackColor = Color.Yellow


                Label81.BackColor = Color.Yellow


                Label82.BackColor = Color.Yellow


                Label83.BackColor = Color.Yellow


                Label84.BackColor = Color.Yellow


                Label85.BackColor = Color.Yellow


                Label86.BackColor = Color.Yellow


                Label87.BackColor = Color.Yellow


                Label88.BackColor = Color.Yellow


                Label89.BackColor = Color.Yellow


                Label90.BackColor = Color.Yellow


                Label91.BackColor = Color.Yellow


                Label92.BackColor = Color.Yellow


                Label93.BackColor = Color.Yellow


                Label94.BackColor = Color.Yellow


                Label95.BackColor = Color.Yellow


                Label96.BackColor = Color.Yellow


                Label97.BackColor = Color.Yellow


                Label98.BackColor = Color.Yellow


                Label99.BackColor = Color.Yellow


            End If



            If ComboBox5.SelectedIndex = 1 Then


                Label73.BackColor = Color.White


                Label74.BackColor = Color.White


                Label75.BackColor = Color.White


                Label76.BackColor = Color.Yellow


                Label77.BackColor = Color.Yellow


                Label78.BackColor = Color.Yellow


                Label79.BackColor = Color.Yellow


                Label80.BackColor = Color.Yellow


                Label81.BackColor = Color.Yellow


                Label82.BackColor = Color.Yellow


                Label83.BackColor = Color.Yellow


                Label84.BackColor = Color.Yellow


                Label85.BackColor = Color.Yellow


                Label86.BackColor = Color.Yellow


                Label87.BackColor = Color.Yellow


                Label88.BackColor = Color.Yellow


                Label89.BackColor = Color.Yellow


                Label90.BackColor = Color.Yellow


                Label91.BackColor = Color.Yellow


                Label92.BackColor = Color.Yellow


                Label93.BackColor = Color.Yellow


                Label94.BackColor = Color.Yellow


                Label95.BackColor = Color.Yellow


                Label96.BackColor = Color.Yellow


                Label97.BackColor = Color.Yellow


                Label98.BackColor = Color.Yellow


                Label99.BackColor = Color.Yellow


            End If



            If ComboBox5.SelectedIndex = 2 Then


                Label73.BackColor = Color.White


                Label74.BackColor = Color.White


                Label75.BackColor = Color.White


                Label76.BackColor = Color.White


                Label77.BackColor = Color.White


                Label78.BackColor = Color.Yellow


                Label79.BackColor = Color.Yellow


                Label80.BackColor = Color.Yellow


                Label81.BackColor = Color.Yellow


                Label82.BackColor = Color.Yellow


                Label83.BackColor = Color.Yellow


                Label84.BackColor = Color.Yellow


                Label85.BackColor = Color.Yellow


                Label86.BackColor = Color.Yellow


                Label87.BackColor = Color.Yellow


                Label88.BackColor = Color.Yellow


                Label89.BackColor = Color.Yellow


                Label90.BackColor = Color.Yellow


                Label91.BackColor = Color.Yellow


                Label92.BackColor = Color.Yellow


                Label93.BackColor = Color.Yellow


                Label94.BackColor = Color.Yellow


                Label95.BackColor = Color.Yellow


                Label96.BackColor = Color.Yellow


                Label97.BackColor = Color.Yellow


                Label98.BackColor = Color.Yellow


                Label99.BackColor = Color.Yellow


            End If



            If ComboBox5.SelectedIndex = 3 Then


                Label73.BackColor = Color.White


                Label74.BackColor = Color.White


                Label75.BackColor = Color.White


                Label76.BackColor = Color.White


                Label77.BackColor = Color.White


                Label78.BackColor = Color.White


                Label79.BackColor = Color.Yellow


                Label80.BackColor = Color.Yellow


                Label81.BackColor = Color.Yellow


                Label82.BackColor = Color.Yellow


                Label83.BackColor = Color.Yellow


                Label84.BackColor = Color.Yellow


                Label85.BackColor = Color.Yellow


                Label86.BackColor = Color.Yellow


                Label87.BackColor = Color.Yellow


                Label88.BackColor = Color.Yellow


                Label89.BackColor = Color.Yellow


                Label90.BackColor = Color.Yellow


                Label91.BackColor = Color.Yellow


                Label92.BackColor = Color.Yellow


                Label93.BackColor = Color.Yellow


                Label94.BackColor = Color.Yellow


                Label95.BackColor = Color.Yellow


                Label96.BackColor = Color.Yellow


                Label97.BackColor = Color.Yellow


                Label98.BackColor = Color.Yellow


                Label99.BackColor = Color.Yellow


            End If



            If ComboBox5.SelectedIndex = 4 Then


                Label73.BackColor = Color.White


                Label74.BackColor = Color.White


                Label75.BackColor = Color.White


                Label76.BackColor = Color.White


                Label77.BackColor = Color.White


                Label78.BackColor = Color.White


                Label79.BackColor = Color.White


                Label80.BackColor = Color.White


                Label81.BackColor = Color.White


                Label82.BackColor = Color.Yellow


                Label83.BackColor = Color.Yellow


                Label84.BackColor = Color.Yellow


                Label85.BackColor = Color.Yellow


                Label86.BackColor = Color.Yellow


                Label87.BackColor = Color.Yellow


                Label88.BackColor = Color.Yellow


                Label89.BackColor = Color.Yellow


                Label90.BackColor = Color.Yellow


                Label91.BackColor = Color.Yellow


                Label92.BackColor = Color.Yellow


                Label93.BackColor = Color.Yellow


                Label94.BackColor = Color.Yellow


                Label95.BackColor = Color.Yellow


                Label96.BackColor = Color.Yellow


                Label97.BackColor = Color.Yellow


                Label98.BackColor = Color.Yellow


                Label99.BackColor = Color.Yellow


            End If



            If ComboBox5.SelectedIndex = 5 Then


                Label73.BackColor = Color.White


                Label74.BackColor = Color.White


                Label75.BackColor = Color.White


                Label76.BackColor = Color.White


                Label77.BackColor = Color.White


                Label78.BackColor = Color.White


                Label79.BackColor = Color.White


                Label80.BackColor = Color.White


                Label81.BackColor = Color.White


                Label82.BackColor = Color.White


                Label83.BackColor = Color.White


                Label84.BackColor = Color.White


                Label85.BackColor = Color.Yellow


                Label86.BackColor = Color.Yellow


                Label87.BackColor = Color.Yellow


                Label88.BackColor = Color.Yellow


                Label89.BackColor = Color.Yellow


                Label90.BackColor = Color.Yellow


                Label91.BackColor = Color.Yellow


                Label92.BackColor = Color.Yellow


                Label93.BackColor = Color.Yellow


                Label94.BackColor = Color.Yellow


                Label95.BackColor = Color.Yellow


                Label96.BackColor = Color.Yellow


                Label97.BackColor = Color.Yellow


                Label98.BackColor = Color.Yellow


                Label99.BackColor = Color.Yellow


            End If


        End If



        If TextBox11.Text = 32 Then


            If ComboBox5.SelectedIndex = 0 Then


                Label73.BackColor = Color.White


                Label74.BackColor = Color.White


                Label75.BackColor = Color.White


                Label76.BackColor = Color.Yellow


                Label77.BackColor = Color.Yellow


                Label78.BackColor = Color.Yellow


                Label79.BackColor = Color.Yellow


                Label80.BackColor = Color.Yellow


                Label81.BackColor = Color.Yellow


                Label82.BackColor = Color.Yellow


                Label83.BackColor = Color.Yellow


                Label84.BackColor = Color.Yellow


                Label85.BackColor = Color.Yellow


                Label86.BackColor = Color.Yellow


                Label87.BackColor = Color.Yellow


                Label88.BackColor = Color.Yellow


                Label89.BackColor = Color.Yellow


                Label90.BackColor = Color.Yellow


                Label91.BackColor = Color.Yellow


                Label92.BackColor = Color.Yellow


                Label93.BackColor = Color.Yellow


                Label94.BackColor = Color.Yellow


                Label95.BackColor = Color.Yellow


                Label96.BackColor = Color.Yellow


                Label97.BackColor = Color.Yellow


                Label98.BackColor = Color.Yellow


                Label99.BackColor = Color.Yellow


            End If



            If ComboBox5.SelectedIndex = 1 Then


                Label73.BackColor = Color.White


                Label74.BackColor = Color.White


                Label75.BackColor = Color.White


                Label76.BackColor = Color.White


                Label77.BackColor = Color.Yellow


                Label78.BackColor = Color.Yellow


                Label79.BackColor = Color.Yellow


                Label80.BackColor = Color.Yellow


                Label81.BackColor = Color.Yellow


                Label82.BackColor = Color.Yellow


                Label83.BackColor = Color.Yellow


                Label84.BackColor = Color.Yellow


                Label85.BackColor = Color.Yellow


                Label86.BackColor = Color.Yellow


                Label87.BackColor = Color.Yellow


                Label88.BackColor = Color.Yellow


                Label89.BackColor = Color.Yellow


                Label90.BackColor = Color.Yellow


                Label91.BackColor = Color.Yellow


                Label92.BackColor = Color.Yellow


                Label93.BackColor = Color.Yellow


                Label94.BackColor = Color.Yellow


                Label95.BackColor = Color.Yellow


                Label96.BackColor = Color.Yellow


                Label97.BackColor = Color.Yellow


                Label98.BackColor = Color.Yellow


                Label99.BackColor = Color.Yellow


            End If



            If ComboBox5.SelectedIndex = 2 Then


                Label73.BackColor = Color.White


                Label74.BackColor = Color.White


                Label75.BackColor = Color.White


                Label76.BackColor = Color.White


                Label77.BackColor = Color.White


                Label78.BackColor = Color.Yellow


                Label79.BackColor = Color.Yellow


                Label80.BackColor = Color.Yellow


                Label81.BackColor = Color.Yellow


                Label82.BackColor = Color.Yellow


                Label83.BackColor = Color.Yellow


                Label84.BackColor = Color.Yellow


                Label85.BackColor = Color.Yellow


                Label86.BackColor = Color.Yellow


                Label87.BackColor = Color.Yellow


                Label88.BackColor = Color.Yellow


                Label89.BackColor = Color.Yellow


                Label90.BackColor = Color.Yellow


                Label91.BackColor = Color.Yellow


                Label92.BackColor = Color.Yellow


                Label93.BackColor = Color.Yellow


                Label94.BackColor = Color.Yellow


                Label95.BackColor = Color.Yellow


                Label96.BackColor = Color.Yellow


                Label97.BackColor = Color.Yellow


                Label98.BackColor = Color.Yellow


                Label99.BackColor = Color.Yellow


            End If



            If ComboBox5.SelectedIndex = 3 Then


                Label73.BackColor = Color.White


                Label74.BackColor = Color.White


                Label75.BackColor = Color.White


                Label76.BackColor = Color.White


                Label77.BackColor = Color.White


                Label78.BackColor = Color.White


                Label79.BackColor = Color.White


                Label80.BackColor = Color.Yellow


                Label81.BackColor = Color.Yellow


                Label82.BackColor = Color.Yellow


                Label83.BackColor = Color.Yellow


                Label84.BackColor = Color.Yellow


                Label85.BackColor = Color.Yellow


                Label86.BackColor = Color.Yellow


                Label87.BackColor = Color.Yellow


                Label88.BackColor = Color.Yellow


                Label89.BackColor = Color.Yellow


                Label90.BackColor = Color.Yellow


                Label91.BackColor = Color.Yellow


                Label92.BackColor = Color.Yellow


                Label93.BackColor = Color.Yellow


                Label94.BackColor = Color.Yellow


                Label95.BackColor = Color.Yellow


                Label96.BackColor = Color.Yellow


                Label97.BackColor = Color.Yellow


                Label98.BackColor = Color.Yellow


                Label99.BackColor = Color.Yellow


            End If



            If ComboBox5.SelectedIndex = 4 Then


                Label73.BackColor = Color.White


                Label74.BackColor = Color.White


                Label75.BackColor = Color.White


                Label76.BackColor = Color.White


                Label77.BackColor = Color.White


                Label78.BackColor = Color.White


                Label79.BackColor = Color.White


                Label80.BackColor = Color.White


                Label81.BackColor = Color.White


                Label82.BackColor = Color.Yellow


                Label83.BackColor = Color.Yellow


                Label84.BackColor = Color.Yellow


                Label85.BackColor = Color.Yellow


                Label86.BackColor = Color.Yellow


                Label87.BackColor = Color.Yellow


                Label88.BackColor = Color.Yellow


                Label89.BackColor = Color.Yellow


                Label90.BackColor = Color.Yellow


                Label91.BackColor = Color.Yellow


                Label92.BackColor = Color.Yellow


                Label93.BackColor = Color.Yellow


                Label94.BackColor = Color.Yellow


                Label95.BackColor = Color.Yellow


                Label96.BackColor = Color.Yellow


                Label97.BackColor = Color.Yellow


                Label98.BackColor = Color.Yellow


                Label99.BackColor = Color.Yellow


            End If



            If ComboBox5.SelectedIndex = 5 Then


                Label73.BackColor = Color.White


                Label74.BackColor = Color.White


                Label75.BackColor = Color.White


                Label76.BackColor = Color.White


                Label77.BackColor = Color.White


                Label78.BackColor = Color.White


                Label79.BackColor = Color.White


                Label80.BackColor = Color.White


                Label81.BackColor = Color.White


                Label82.BackColor = Color.White


                Label83.BackColor = Color.White


                Label84.BackColor = Color.White


                Label85.BackColor = Color.Yellow


                Label86.BackColor = Color.Yellow


                Label87.BackColor = Color.Yellow


                Label88.BackColor = Color.Yellow


                Label89.BackColor = Color.Yellow


                Label90.BackColor = Color.Yellow


                Label91.BackColor = Color.Yellow


                Label92.BackColor = Color.Yellow


                Label93.BackColor = Color.Yellow


                Label94.BackColor = Color.Yellow


                Label95.BackColor = Color.Yellow


                Label96.BackColor = Color.Yellow


                Label97.BackColor = Color.Yellow


                Label98.BackColor = Color.Yellow


                Label99.BackColor = Color.Yellow


            End If


        End If



        If TextBox11.Text = 33 Then


            If ComboBox5.SelectedIndex = 0 Then


                Label73.BackColor = Color.White


                Label74.BackColor = Color.White


                Label75.BackColor = Color.White


                Label76.BackColor = Color.Yellow


                Label77.BackColor = Color.Yellow


                Label78.BackColor = Color.Yellow


                Label79.BackColor = Color.Yellow


                Label80.BackColor = Color.Yellow


                Label81.BackColor = Color.Yellow


                Label82.BackColor = Color.Yellow


                Label83.BackColor = Color.Yellow


                Label84.BackColor = Color.Yellow


                Label85.BackColor = Color.Yellow


                Label86.BackColor = Color.Yellow


                Label87.BackColor = Color.Yellow


                Label88.BackColor = Color.Yellow


                Label89.BackColor = Color.Yellow


                Label90.BackColor = Color.Yellow


                Label91.BackColor = Color.Yellow


                Label92.BackColor = Color.Yellow


                Label93.BackColor = Color.Yellow


                Label94.BackColor = Color.Yellow


                Label95.BackColor = Color.Yellow


                Label96.BackColor = Color.Yellow


                Label97.BackColor = Color.Yellow


                Label98.BackColor = Color.Yellow


                Label99.BackColor = Color.Yellow


            End If



            If ComboBox5.SelectedIndex = 1 Then


                Label73.BackColor = Color.White


                Label74.BackColor = Color.White


                Label75.BackColor = Color.White


                Label76.BackColor = Color.White


                Label77.BackColor = Color.White


                Label78.BackColor = Color.Yellow


                Label79.BackColor = Color.Yellow


                Label80.BackColor = Color.Yellow


                Label81.BackColor = Color.Yellow


                Label82.BackColor = Color.Yellow


                Label83.BackColor = Color.Yellow


                Label84.BackColor = Color.Yellow


                Label85.BackColor = Color.Yellow


                Label86.BackColor = Color.Yellow


                Label87.BackColor = Color.Yellow


                Label88.BackColor = Color.Yellow


                Label89.BackColor = Color.Yellow


                Label90.BackColor = Color.Yellow


                Label91.BackColor = Color.Yellow


                Label92.BackColor = Color.Yellow


                Label93.BackColor = Color.Yellow


                Label94.BackColor = Color.Yellow


                Label95.BackColor = Color.Yellow


                Label96.BackColor = Color.Yellow


                Label97.BackColor = Color.Yellow


                Label98.BackColor = Color.Yellow


                Label99.BackColor = Color.Yellow


            End If



            If ComboBox5.SelectedIndex = 2 Then


                Label73.BackColor = Color.White


                Label74.BackColor = Color.White


                Label75.BackColor = Color.White


                Label76.BackColor = Color.White


                Label77.BackColor = Color.White


                Label78.BackColor = Color.White


                Label79.BackColor = Color.Yellow


                Label80.BackColor = Color.Yellow


                Label81.BackColor = Color.Yellow


                Label82.BackColor = Color.Yellow


                Label83.BackColor = Color.Yellow


                Label84.BackColor = Color.Yellow


                Label85.BackColor = Color.Yellow


                Label86.BackColor = Color.Yellow


                Label87.BackColor = Color.Yellow


                Label88.BackColor = Color.Yellow


                Label89.BackColor = Color.Yellow


                Label90.BackColor = Color.Yellow


                Label91.BackColor = Color.Yellow


                Label92.BackColor = Color.Yellow


                Label93.BackColor = Color.Yellow


                Label94.BackColor = Color.Yellow


                Label95.BackColor = Color.Yellow


                Label96.BackColor = Color.Yellow


                Label97.BackColor = Color.Yellow


                Label98.BackColor = Color.Yellow


                Label99.BackColor = Color.Yellow


            End If



            If ComboBox5.SelectedIndex = 3 Then


                Label73.BackColor = Color.White


                Label74.BackColor = Color.White


                Label75.BackColor = Color.White


                Label76.BackColor = Color.White


                Label77.BackColor = Color.White


                Label78.BackColor = Color.White


                Label79.BackColor = Color.White


                Label80.BackColor = Color.White


                Label81.BackColor = Color.Yellow


                Label82.BackColor = Color.Yellow


                Label83.BackColor = Color.Yellow


                Label84.BackColor = Color.Yellow


                Label85.BackColor = Color.Yellow


                Label86.BackColor = Color.Yellow


                Label87.BackColor = Color.Yellow


                Label88.BackColor = Color.Yellow


                Label89.BackColor = Color.Yellow


                Label90.BackColor = Color.Yellow


                Label91.BackColor = Color.Yellow


                Label92.BackColor = Color.Yellow


                Label93.BackColor = Color.Yellow


                Label94.BackColor = Color.Yellow


                Label95.BackColor = Color.Yellow


                Label96.BackColor = Color.Yellow


                Label97.BackColor = Color.Yellow


                Label98.BackColor = Color.Yellow


                Label99.BackColor = Color.Yellow


            End If



            If ComboBox5.SelectedIndex = 4 Then


                Label73.BackColor = Color.White


                Label74.BackColor = Color.White


                Label75.BackColor = Color.White


                Label76.BackColor = Color.White


                Label77.BackColor = Color.White


                Label78.BackColor = Color.White


                Label79.BackColor = Color.White


                Label80.BackColor = Color.White


                Label81.BackColor = Color.White


                Label82.BackColor = Color.White


                Label83.BackColor = Color.Yellow


                Label84.BackColor = Color.Yellow


                Label85.BackColor = Color.Yellow


                Label86.BackColor = Color.Yellow


                Label87.BackColor = Color.Yellow


                Label88.BackColor = Color.Yellow


                Label89.BackColor = Color.Yellow


                Label90.BackColor = Color.Yellow


                Label91.BackColor = Color.Yellow


                Label92.BackColor = Color.Yellow


                Label93.BackColor = Color.Yellow


                Label94.BackColor = Color.Yellow


                Label95.BackColor = Color.Yellow


                Label96.BackColor = Color.Yellow


                Label97.BackColor = Color.Yellow


                Label98.BackColor = Color.Yellow


                Label99.BackColor = Color.Yellow


            End If



            If ComboBox5.SelectedIndex = 5 Then


                Label73.BackColor = Color.White


                Label74.BackColor = Color.White


                Label75.BackColor = Color.White


                Label76.BackColor = Color.White


                Label77.BackColor = Color.White


                Label78.BackColor = Color.White


                Label79.BackColor = Color.White


                Label80.BackColor = Color.White


                Label81.BackColor = Color.White


                Label82.BackColor = Color.White


                Label83.BackColor = Color.White


                Label84.BackColor = Color.White


                Label85.BackColor = Color.White


                Label86.BackColor = Color.Yellow


                Label87.BackColor = Color.Yellow


                Label88.BackColor = Color.Yellow


                Label89.BackColor = Color.Yellow


                Label90.BackColor = Color.Yellow


                Label91.BackColor = Color.Yellow


                Label92.BackColor = Color.Yellow


                Label93.BackColor = Color.Yellow


                Label94.BackColor = Color.Yellow


                Label95.BackColor = Color.Yellow


                Label96.BackColor = Color.Yellow


                Label97.BackColor = Color.Yellow


                Label98.BackColor = Color.Yellow


                Label99.BackColor = Color.Yellow


            End If


        End If



        If TextBox11.Text = 34 Then


            If ComboBox5.SelectedIndex = 0 Then


                Label73.BackColor = Color.White


                Label74.BackColor = Color.White


                Label75.BackColor = Color.White


                Label76.BackColor = Color.White


                Label77.BackColor = Color.Yellow


                Label78.BackColor = Color.Yellow


                Label79.BackColor = Color.Yellow


                Label80.BackColor = Color.Yellow


                Label81.BackColor = Color.Yellow


                Label82.BackColor = Color.Yellow


                Label83.BackColor = Color.Yellow


                Label84.BackColor = Color.Yellow


                Label85.BackColor = Color.Yellow


                Label86.BackColor = Color.Yellow


                Label87.BackColor = Color.Yellow


                Label88.BackColor = Color.Yellow


                Label89.BackColor = Color.Yellow


                Label90.BackColor = Color.Yellow


                Label91.BackColor = Color.Yellow


                Label92.BackColor = Color.Yellow


                Label93.BackColor = Color.Yellow


                Label94.BackColor = Color.Yellow


                Label95.BackColor = Color.Yellow


                Label96.BackColor = Color.Yellow


                Label97.BackColor = Color.Yellow


                Label98.BackColor = Color.Yellow


                Label99.BackColor = Color.Yellow


            End If



            If ComboBox5.SelectedIndex = 1 Then


                Label73.BackColor = Color.White


                Label74.BackColor = Color.White


                Label75.BackColor = Color.White


                Label76.BackColor = Color.White


                Label77.BackColor = Color.White


                Label78.BackColor = Color.Yellow


                Label79.BackColor = Color.Yellow


                Label80.BackColor = Color.Yellow


                Label81.BackColor = Color.Yellow


                Label82.BackColor = Color.Yellow


                Label83.BackColor = Color.Yellow


                Label84.BackColor = Color.Yellow


                Label85.BackColor = Color.Yellow


                Label86.BackColor = Color.Yellow


                Label87.BackColor = Color.Yellow


                Label88.BackColor = Color.Yellow


                Label89.BackColor = Color.Yellow


                Label90.BackColor = Color.Yellow


                Label91.BackColor = Color.Yellow


                Label92.BackColor = Color.Yellow


                Label93.BackColor = Color.Yellow


                Label94.BackColor = Color.Yellow


                Label95.BackColor = Color.Yellow


                Label96.BackColor = Color.Yellow


                Label97.BackColor = Color.Yellow


                Label98.BackColor = Color.Yellow


                Label99.BackColor = Color.Yellow


            End If



            If ComboBox5.SelectedIndex = 2 Then


                Label73.BackColor = Color.White


                Label74.BackColor = Color.White


                Label75.BackColor = Color.White


                Label76.BackColor = Color.White


                Label77.BackColor = Color.White


                Label78.BackColor = Color.White


                Label79.BackColor = Color.White


                Label80.BackColor = Color.Yellow


                Label81.BackColor = Color.Yellow


                Label82.BackColor = Color.Yellow


                Label83.BackColor = Color.Yellow


                Label84.BackColor = Color.Yellow


                Label85.BackColor = Color.Yellow


                Label86.BackColor = Color.Yellow


                Label87.BackColor = Color.Yellow


                Label88.BackColor = Color.Yellow


                Label89.BackColor = Color.Yellow


                Label90.BackColor = Color.Yellow


                Label91.BackColor = Color.Yellow


                Label92.BackColor = Color.Yellow


                Label93.BackColor = Color.Yellow


                Label94.BackColor = Color.Yellow


                Label95.BackColor = Color.Yellow


                Label96.BackColor = Color.Yellow


                Label97.BackColor = Color.Yellow


                Label98.BackColor = Color.Yellow


                Label99.BackColor = Color.Yellow


            End If



            If ComboBox5.SelectedIndex = 3 Then


                Label73.BackColor = Color.White


                Label74.BackColor = Color.White


                Label75.BackColor = Color.White


                Label76.BackColor = Color.White


                Label77.BackColor = Color.White


                Label78.BackColor = Color.White


                Label79.BackColor = Color.White


                Label80.BackColor = Color.White


                Label81.BackColor = Color.Yellow


                Label82.BackColor = Color.Yellow


                Label83.BackColor = Color.Yellow


                Label84.BackColor = Color.Yellow


                Label85.BackColor = Color.Yellow


                Label86.BackColor = Color.Yellow


                Label87.BackColor = Color.Yellow


                Label88.BackColor = Color.Yellow


                Label89.BackColor = Color.Yellow


                Label90.BackColor = Color.Yellow


                Label91.BackColor = Color.Yellow


                Label92.BackColor = Color.Yellow


                Label93.BackColor = Color.Yellow


                Label94.BackColor = Color.Yellow


                Label95.BackColor = Color.Yellow


                Label96.BackColor = Color.Yellow


                Label97.BackColor = Color.Yellow


                Label98.BackColor = Color.Yellow


                Label99.BackColor = Color.Yellow


            End If



            If ComboBox5.SelectedIndex = 4 Then


                Label73.BackColor = Color.White


                Label74.BackColor = Color.White


                Label75.BackColor = Color.White


                Label76.BackColor = Color.White


                Label77.BackColor = Color.White


                Label78.BackColor = Color.White


                Label79.BackColor = Color.White


                Label80.BackColor = Color.White


                Label81.BackColor = Color.White


                Label82.BackColor = Color.White


                Label83.BackColor = Color.Yellow


                Label84.BackColor = Color.Yellow


                Label85.BackColor = Color.Yellow


                Label86.BackColor = Color.Yellow


                Label87.BackColor = Color.Yellow


                Label88.BackColor = Color.Yellow


                Label89.BackColor = Color.Yellow


                Label90.BackColor = Color.Yellow


                Label91.BackColor = Color.Yellow


                Label92.BackColor = Color.Yellow


                Label93.BackColor = Color.Yellow


                Label94.BackColor = Color.Yellow


                Label95.BackColor = Color.Yellow


                Label96.BackColor = Color.Yellow


                Label97.BackColor = Color.Yellow


                Label98.BackColor = Color.Yellow


                Label99.BackColor = Color.Yellow


            End If



            If ComboBox5.SelectedIndex = 5 Then


                Label73.BackColor = Color.White


                Label74.BackColor = Color.White


                Label75.BackColor = Color.White


                Label76.BackColor = Color.White


                Label77.BackColor = Color.White


                Label78.BackColor = Color.White


                Label79.BackColor = Color.White


                Label80.BackColor = Color.White


                Label81.BackColor = Color.White


                Label82.BackColor = Color.White


                Label83.BackColor = Color.White


                Label84.BackColor = Color.White


                Label85.BackColor = Color.White


                Label86.BackColor = Color.White


                Label87.BackColor = Color.Yellow


                Label88.BackColor = Color.Yellow


                Label89.BackColor = Color.Yellow


                Label90.BackColor = Color.Yellow


                Label91.BackColor = Color.Yellow


                Label92.BackColor = Color.Yellow


                Label93.BackColor = Color.Yellow


                Label94.BackColor = Color.Yellow


                Label95.BackColor = Color.Yellow


                Label96.BackColor = Color.Yellow


                Label97.BackColor = Color.Yellow


                Label98.BackColor = Color.Yellow


                Label99.BackColor = Color.Yellow


            End If


        End If



        If TextBox11.Text = 35 Then


            If ComboBox5.SelectedIndex = 0 Then


                Label73.BackColor = Color.White


                Label74.BackColor = Color.White


                Label75.BackColor = Color.White


                Label76.BackColor = Color.White


                Label77.BackColor = Color.Yellow


                Label78.BackColor = Color.Yellow


                Label79.BackColor = Color.Yellow


                Label80.BackColor = Color.Yellow


                Label81.BackColor = Color.Yellow


                Label82.BackColor = Color.Yellow


                Label83.BackColor = Color.Yellow


                Label84.BackColor = Color.Yellow


                Label85.BackColor = Color.Yellow


                Label86.BackColor = Color.Yellow


                Label87.BackColor = Color.Yellow


                Label88.BackColor = Color.Yellow


                Label89.BackColor = Color.Yellow


                Label90.BackColor = Color.Yellow


                Label91.BackColor = Color.Yellow


                Label92.BackColor = Color.Yellow


                Label93.BackColor = Color.Yellow


                Label94.BackColor = Color.Yellow


                Label95.BackColor = Color.Yellow


                Label96.BackColor = Color.Yellow


                Label97.BackColor = Color.Yellow


                Label98.BackColor = Color.Yellow


                Label99.BackColor = Color.Yellow


            End If



            If ComboBox5.SelectedIndex = 1 Then


                Label73.BackColor = Color.White


                Label74.BackColor = Color.White


                Label75.BackColor = Color.White


                Label76.BackColor = Color.White


                Label77.BackColor = Color.White


                Label78.BackColor = Color.White


                Label79.BackColor = Color.Yellow


                Label80.BackColor = Color.Yellow


                Label81.BackColor = Color.Yellow


                Label82.BackColor = Color.Yellow


                Label83.BackColor = Color.Yellow


                Label84.BackColor = Color.Yellow


                Label85.BackColor = Color.Yellow


                Label86.BackColor = Color.Yellow


                Label87.BackColor = Color.Yellow


                Label88.BackColor = Color.Yellow


                Label89.BackColor = Color.Yellow


                Label90.BackColor = Color.Yellow


                Label91.BackColor = Color.Yellow


                Label92.BackColor = Color.Yellow


                Label93.BackColor = Color.Yellow


                Label94.BackColor = Color.Yellow


                Label95.BackColor = Color.Yellow


                Label96.BackColor = Color.Yellow


                Label97.BackColor = Color.Yellow


                Label98.BackColor = Color.Yellow


                Label99.BackColor = Color.Yellow


            End If



            If ComboBox5.SelectedIndex = 2 Then


                Label73.BackColor = Color.White


                Label74.BackColor = Color.White


                Label75.BackColor = Color.White


                Label76.BackColor = Color.White


                Label77.BackColor = Color.White


                Label78.BackColor = Color.White


                Label79.BackColor = Color.White


                Label80.BackColor = Color.Yellow


                Label81.BackColor = Color.Yellow


                Label82.BackColor = Color.Yellow


                Label83.BackColor = Color.Yellow


                Label84.BackColor = Color.Yellow


                Label85.BackColor = Color.Yellow


                Label86.BackColor = Color.Yellow


                Label87.BackColor = Color.Yellow


                Label88.BackColor = Color.Yellow


                Label89.BackColor = Color.Yellow


                Label90.BackColor = Color.Yellow


                Label91.BackColor = Color.Yellow


                Label92.BackColor = Color.Yellow


                Label93.BackColor = Color.Yellow


                Label94.BackColor = Color.Yellow


                Label95.BackColor = Color.Yellow


                Label96.BackColor = Color.Yellow


                Label97.BackColor = Color.Yellow


                Label98.BackColor = Color.Yellow


                Label99.BackColor = Color.Yellow


            End If



            If ComboBox5.SelectedIndex = 3 Then


                Label73.BackColor = Color.White


                Label74.BackColor = Color.White


                Label75.BackColor = Color.White


                Label76.BackColor = Color.White


                Label77.BackColor = Color.White


                Label78.BackColor = Color.White


                Label79.BackColor = Color.White


                Label80.BackColor = Color.White


                Label81.BackColor = Color.White


                Label82.BackColor = Color.Yellow


                Label83.BackColor = Color.Yellow


                Label84.BackColor = Color.Yellow


                Label85.BackColor = Color.Yellow


                Label86.BackColor = Color.Yellow


                Label87.BackColor = Color.Yellow


                Label88.BackColor = Color.Yellow


                Label89.BackColor = Color.Yellow


                Label90.BackColor = Color.Yellow


                Label91.BackColor = Color.Yellow


                Label92.BackColor = Color.Yellow


                Label93.BackColor = Color.Yellow


                Label94.BackColor = Color.Yellow


                Label95.BackColor = Color.Yellow


                Label96.BackColor = Color.Yellow


                Label97.BackColor = Color.Yellow


                Label98.BackColor = Color.Yellow


                Label99.BackColor = Color.Yellow


            End If



            If ComboBox5.SelectedIndex = 4 Then


                Label73.BackColor = Color.White


                Label74.BackColor = Color.White


                Label75.BackColor = Color.White


                Label76.BackColor = Color.White


                Label77.BackColor = Color.White


                Label78.BackColor = Color.White


                Label79.BackColor = Color.White


                Label80.BackColor = Color.White


                Label81.BackColor = Color.White


                Label82.BackColor = Color.White


                Label83.BackColor = Color.White


                Label84.BackColor = Color.Yellow


                Label85.BackColor = Color.Yellow


                Label86.BackColor = Color.Yellow


                Label87.BackColor = Color.Yellow


                Label88.BackColor = Color.Yellow


                Label89.BackColor = Color.Yellow


                Label90.BackColor = Color.Yellow


                Label91.BackColor = Color.Yellow


                Label92.BackColor = Color.Yellow


                Label93.BackColor = Color.Yellow


                Label94.BackColor = Color.Yellow


                Label95.BackColor = Color.Yellow


                Label96.BackColor = Color.Yellow


                Label97.BackColor = Color.Yellow


                Label98.BackColor = Color.Yellow


                Label99.BackColor = Color.Yellow


            End If



            If ComboBox5.SelectedIndex = 5 Then


                Label73.BackColor = Color.White


                Label74.BackColor = Color.White


                Label75.BackColor = Color.White


                Label76.BackColor = Color.White


                Label77.BackColor = Color.White


                Label78.BackColor = Color.White


                Label79.BackColor = Color.White


                Label80.BackColor = Color.White


                Label81.BackColor = Color.White


                Label82.BackColor = Color.White


                Label83.BackColor = Color.White


                Label84.BackColor = Color.White


                Label85.BackColor = Color.White


                Label86.BackColor = Color.White


                Label87.BackColor = Color.White


                Label88.BackColor = Color.Yellow


                Label89.BackColor = Color.Yellow


                Label90.BackColor = Color.Yellow


                Label91.BackColor = Color.Yellow


                Label92.BackColor = Color.Yellow


                Label93.BackColor = Color.Yellow


                Label94.BackColor = Color.Yellow


                Label95.BackColor = Color.Yellow


                Label96.BackColor = Color.Yellow


                Label97.BackColor = Color.Yellow


                Label98.BackColor = Color.Yellow


                Label99.BackColor = Color.Yellow


            End If


        End If



        If TextBox11.Text = 36 Then


            If ComboBox5.SelectedIndex = 0 Then


                Label73.BackColor = Color.White


                Label74.BackColor = Color.White


                Label75.BackColor = Color.White


                Label76.BackColor = Color.White


                Label77.BackColor = Color.White


                Label78.BackColor = Color.Yellow


                Label79.BackColor = Color.Yellow


                Label80.BackColor = Color.Yellow


                Label81.BackColor = Color.Yellow


                Label82.BackColor = Color.Yellow


                Label83.BackColor = Color.Yellow


                Label84.BackColor = Color.Yellow


                Label85.BackColor = Color.Yellow


                Label86.BackColor = Color.Yellow


                Label87.BackColor = Color.Yellow


                Label88.BackColor = Color.Yellow


                Label89.BackColor = Color.Yellow


                Label90.BackColor = Color.Yellow


                Label91.BackColor = Color.Yellow


                Label92.BackColor = Color.Yellow


                Label93.BackColor = Color.Yellow


                Label94.BackColor = Color.Yellow


                Label95.BackColor = Color.Yellow


                Label96.BackColor = Color.Yellow


                Label97.BackColor = Color.Yellow


                Label98.BackColor = Color.Yellow


                Label99.BackColor = Color.Yellow


            End If



            If ComboBox5.SelectedIndex = 1 Then


                Label73.BackColor = Color.White


                Label74.BackColor = Color.White


                Label75.BackColor = Color.White


                Label76.BackColor = Color.White


                Label77.BackColor = Color.White


                Label78.BackColor = Color.White


                Label79.BackColor = Color.Yellow


                Label80.BackColor = Color.Yellow


                Label81.BackColor = Color.Yellow


                Label82.BackColor = Color.Yellow


                Label83.BackColor = Color.Yellow


                Label84.BackColor = Color.Yellow


                Label85.BackColor = Color.Yellow


                Label86.BackColor = Color.Yellow


                Label87.BackColor = Color.Yellow


                Label88.BackColor = Color.Yellow


                Label89.BackColor = Color.Yellow


                Label90.BackColor = Color.Yellow


                Label91.BackColor = Color.Yellow


                Label92.BackColor = Color.Yellow


                Label93.BackColor = Color.Yellow


                Label94.BackColor = Color.Yellow


                Label95.BackColor = Color.Yellow


                Label96.BackColor = Color.Yellow


                Label97.BackColor = Color.Yellow


                Label98.BackColor = Color.Yellow


                Label99.BackColor = Color.Yellow


            End If



            If ComboBox5.SelectedIndex = 2 Then


                Label73.BackColor = Color.White


                Label74.BackColor = Color.White


                Label75.BackColor = Color.White


                Label76.BackColor = Color.White


                Label77.BackColor = Color.White


                Label78.BackColor = Color.White


                Label79.BackColor = Color.White


                Label80.BackColor = Color.White


                Label81.BackColor = Color.Yellow


                Label82.BackColor = Color.Yellow


                Label83.BackColor = Color.Yellow


                Label84.BackColor = Color.Yellow


                Label85.BackColor = Color.Yellow


                Label86.BackColor = Color.Yellow


                Label87.BackColor = Color.Yellow


                Label88.BackColor = Color.Yellow


                Label89.BackColor = Color.Yellow


                Label90.BackColor = Color.Yellow


                Label91.BackColor = Color.Yellow


                Label92.BackColor = Color.Yellow


                Label93.BackColor = Color.Yellow


                Label94.BackColor = Color.Yellow


                Label95.BackColor = Color.Yellow


                Label96.BackColor = Color.Yellow


                Label97.BackColor = Color.Yellow


                Label98.BackColor = Color.Yellow


                Label99.BackColor = Color.Yellow


            End If



            If ComboBox5.SelectedIndex = 3 Then


                Label73.BackColor = Color.White


                Label74.BackColor = Color.White


                Label75.BackColor = Color.White


                Label76.BackColor = Color.White


                Label77.BackColor = Color.White


                Label78.BackColor = Color.White


                Label79.BackColor = Color.White


                Label80.BackColor = Color.White


                Label81.BackColor = Color.White


                Label82.BackColor = Color.White


                Label83.BackColor = Color.Yellow


                Label84.BackColor = Color.Yellow


                Label85.BackColor = Color.Yellow


                Label86.BackColor = Color.Yellow


                Label87.BackColor = Color.Yellow


                Label88.BackColor = Color.Yellow


                Label89.BackColor = Color.Yellow


                Label90.BackColor = Color.Yellow


                Label91.BackColor = Color.Yellow


                Label92.BackColor = Color.Yellow


                Label93.BackColor = Color.Yellow


                Label94.BackColor = Color.Yellow


                Label95.BackColor = Color.Yellow


                Label96.BackColor = Color.Yellow


                Label97.BackColor = Color.Yellow


                Label98.BackColor = Color.Yellow


                Label99.BackColor = Color.Yellow


            End If



            If ComboBox5.SelectedIndex = 4 Then


                Label73.BackColor = Color.White


                Label74.BackColor = Color.White


                Label75.BackColor = Color.White


                Label76.BackColor = Color.White


                Label77.BackColor = Color.White


                Label78.BackColor = Color.White


                Label79.BackColor = Color.White


                Label80.BackColor = Color.White


                Label81.BackColor = Color.White


                Label82.BackColor = Color.White


                Label83.BackColor = Color.White


                Label84.BackColor = Color.White


                Label85.BackColor = Color.Yellow


                Label86.BackColor = Color.Yellow


                Label87.BackColor = Color.Yellow


                Label88.BackColor = Color.Yellow


                Label89.BackColor = Color.Yellow


                Label90.BackColor = Color.Yellow


                Label91.BackColor = Color.Yellow


                Label92.BackColor = Color.Yellow


                Label93.BackColor = Color.Yellow


                Label94.BackColor = Color.Yellow


                Label95.BackColor = Color.Yellow


                Label96.BackColor = Color.Yellow


                Label97.BackColor = Color.Yellow


                Label98.BackColor = Color.Yellow


                Label99.BackColor = Color.Yellow


            End If



            If ComboBox5.SelectedIndex = 5 Then


                Label73.BackColor = Color.White


                Label74.BackColor = Color.White


                Label75.BackColor = Color.White


                Label76.BackColor = Color.White


                Label77.BackColor = Color.White


                Label78.BackColor = Color.White


                Label79.BackColor = Color.White


                Label80.BackColor = Color.White


                Label81.BackColor = Color.White


                Label82.BackColor = Color.White


                Label83.BackColor = Color.White


                Label84.BackColor = Color.White


                Label85.BackColor = Color.White


                Label86.BackColor = Color.White


                Label87.BackColor = Color.White


                Label88.BackColor = Color.White


                Label89.BackColor = Color.Yellow


                Label90.BackColor = Color.Yellow


                Label91.BackColor = Color.Yellow


                Label92.BackColor = Color.Yellow


                Label93.BackColor = Color.Yellow


                Label94.BackColor = Color.Yellow


                Label95.BackColor = Color.Yellow


                Label96.BackColor = Color.Yellow


                Label97.BackColor = Color.Yellow


                Label98.BackColor = Color.Yellow


                Label99.BackColor = Color.Yellow


            End If


        End If



        If TextBox11.Text = 37 Then


            If ComboBox5.SelectedIndex = 0 Then


                Label73.BackColor = Color.White


                Label74.BackColor = Color.White


                Label75.BackColor = Color.White


                Label76.BackColor = Color.White


                Label77.BackColor = Color.White


                Label78.BackColor = Color.Yellow


                Label79.BackColor = Color.Yellow


                Label80.BackColor = Color.Yellow


                Label81.BackColor = Color.Yellow


                Label82.BackColor = Color.Yellow


                Label83.BackColor = Color.Yellow


                Label84.BackColor = Color.Yellow


                Label85.BackColor = Color.Yellow


                Label86.BackColor = Color.Yellow


                Label87.BackColor = Color.Yellow


                Label88.BackColor = Color.Yellow


                Label89.BackColor = Color.Yellow


                Label90.BackColor = Color.Yellow


                Label91.BackColor = Color.Yellow


                Label92.BackColor = Color.Yellow


                Label93.BackColor = Color.Yellow


                Label94.BackColor = Color.Yellow


                Label95.BackColor = Color.Yellow


                Label96.BackColor = Color.Yellow


                Label97.BackColor = Color.Yellow


                Label98.BackColor = Color.Yellow


                Label99.BackColor = Color.Yellow


            End If



            If ComboBox5.SelectedIndex = 1 Then


                Label73.BackColor = Color.White


                Label74.BackColor = Color.White


                Label75.BackColor = Color.White


                Label76.BackColor = Color.White


                Label77.BackColor = Color.White


                Label78.BackColor = Color.White


                Label79.BackColor = Color.White


                Label80.BackColor = Color.Yellow


                Label81.BackColor = Color.Yellow


                Label82.BackColor = Color.Yellow


                Label83.BackColor = Color.Yellow


                Label84.BackColor = Color.Yellow


                Label85.BackColor = Color.Yellow


                Label86.BackColor = Color.Yellow


                Label87.BackColor = Color.Yellow


                Label88.BackColor = Color.Yellow


                Label89.BackColor = Color.Yellow


                Label90.BackColor = Color.Yellow


                Label91.BackColor = Color.Yellow


                Label92.BackColor = Color.Yellow


                Label93.BackColor = Color.Yellow


                Label94.BackColor = Color.Yellow


                Label95.BackColor = Color.Yellow


                Label96.BackColor = Color.Yellow


                Label97.BackColor = Color.Yellow


                Label98.BackColor = Color.Yellow


                Label99.BackColor = Color.Yellow


            End If



            If ComboBox5.SelectedIndex = 2 Then


                Label73.BackColor = Color.White


                Label74.BackColor = Color.White


                Label75.BackColor = Color.White


                Label76.BackColor = Color.White


                Label77.BackColor = Color.White


                Label78.BackColor = Color.White


                Label79.BackColor = Color.White


                Label80.BackColor = Color.White


                Label81.BackColor = Color.Yellow


                Label82.BackColor = Color.Yellow


                Label83.BackColor = Color.Yellow


                Label84.BackColor = Color.Yellow


                Label85.BackColor = Color.Yellow


                Label86.BackColor = Color.Yellow


                Label87.BackColor = Color.Yellow


                Label88.BackColor = Color.Yellow


                Label89.BackColor = Color.Yellow


                Label90.BackColor = Color.Yellow


                Label91.BackColor = Color.Yellow


                Label92.BackColor = Color.Yellow


                Label93.BackColor = Color.Yellow


                Label94.BackColor = Color.Yellow


                Label95.BackColor = Color.Yellow


                Label96.BackColor = Color.Yellow


                Label97.BackColor = Color.Yellow


                Label98.BackColor = Color.Yellow


                Label99.BackColor = Color.Yellow


            End If



            If ComboBox5.SelectedIndex = 3 Then


                Label73.BackColor = Color.White


                Label74.BackColor = Color.White


                Label75.BackColor = Color.White


                Label76.BackColor = Color.White


                Label77.BackColor = Color.White


                Label78.BackColor = Color.White


                Label79.BackColor = Color.White


                Label80.BackColor = Color.White


                Label81.BackColor = Color.White


                Label82.BackColor = Color.White


                Label83.BackColor = Color.Yellow


                Label84.BackColor = Color.Yellow


                Label85.BackColor = Color.Yellow


                Label86.BackColor = Color.Yellow


                Label87.BackColor = Color.Yellow


                Label88.BackColor = Color.Yellow


                Label89.BackColor = Color.Yellow


                Label90.BackColor = Color.Yellow


                Label91.BackColor = Color.Yellow


                Label92.BackColor = Color.Yellow


                Label93.BackColor = Color.Yellow


                Label94.BackColor = Color.Yellow


                Label95.BackColor = Color.Yellow


                Label96.BackColor = Color.Yellow


                Label97.BackColor = Color.Yellow


                Label98.BackColor = Color.Yellow


                Label99.BackColor = Color.Yellow


            End If



            If ComboBox5.SelectedIndex = 4 Then


                Label73.BackColor = Color.White


                Label74.BackColor = Color.White


                Label75.BackColor = Color.White


                Label76.BackColor = Color.White


                Label77.BackColor = Color.White


                Label78.BackColor = Color.White


                Label79.BackColor = Color.White


                Label80.BackColor = Color.White


                Label81.BackColor = Color.White


                Label82.BackColor = Color.White


                Label83.BackColor = Color.White


                Label84.BackColor = Color.White


                Label85.BackColor = Color.White


                Label86.BackColor = Color.Yellow


                Label87.BackColor = Color.Yellow


                Label88.BackColor = Color.Yellow


                Label89.BackColor = Color.Yellow


                Label90.BackColor = Color.Yellow


                Label91.BackColor = Color.Yellow


                Label92.BackColor = Color.Yellow


                Label93.BackColor = Color.Yellow


                Label94.BackColor = Color.Yellow


                Label95.BackColor = Color.Yellow


                Label96.BackColor = Color.Yellow


                Label97.BackColor = Color.Yellow


                Label98.BackColor = Color.Yellow


                Label99.BackColor = Color.Yellow


            End If



            If ComboBox5.SelectedIndex = 5 Then


                Label73.BackColor = Color.White


                Label74.BackColor = Color.White


                Label75.BackColor = Color.White


                Label76.BackColor = Color.White


                Label77.BackColor = Color.White


                Label78.BackColor = Color.White


                Label79.BackColor = Color.White


                Label80.BackColor = Color.White


                Label81.BackColor = Color.White


                Label82.BackColor = Color.White


                Label83.BackColor = Color.White


                Label84.BackColor = Color.White


                Label85.BackColor = Color.White


                Label86.BackColor = Color.White


                Label87.BackColor = Color.White


                Label88.BackColor = Color.White


                Label89.BackColor = Color.White


                Label90.BackColor = Color.Yellow


                Label91.BackColor = Color.Yellow


                Label92.BackColor = Color.Yellow


                Label93.BackColor = Color.Yellow


                Label94.BackColor = Color.Yellow


                Label95.BackColor = Color.Yellow


                Label96.BackColor = Color.Yellow


                Label97.BackColor = Color.Yellow


                Label98.BackColor = Color.Yellow


                Label99.BackColor = Color.Yellow


            End If


        End If



        If TextBox11.Text = 38 Then


            If ComboBox5.SelectedIndex = 0 Then


                Label73.BackColor = Color.White


                Label74.BackColor = Color.White


                Label75.BackColor = Color.White


                Label76.BackColor = Color.White


                Label77.BackColor = Color.White


                Label78.BackColor = Color.White


                Label79.BackColor = Color.Yellow


                Label80.BackColor = Color.Yellow


                Label81.BackColor = Color.Yellow


                Label82.BackColor = Color.Yellow


                Label83.BackColor = Color.Yellow


                Label84.BackColor = Color.Yellow


                Label85.BackColor = Color.Yellow


                Label86.BackColor = Color.Yellow


                Label87.BackColor = Color.Yellow


                Label88.BackColor = Color.Yellow


                Label89.BackColor = Color.Yellow


                Label90.BackColor = Color.Yellow


                Label91.BackColor = Color.Yellow


                Label92.BackColor = Color.Yellow


                Label93.BackColor = Color.Yellow


                Label94.BackColor = Color.Yellow


                Label95.BackColor = Color.Yellow


                Label96.BackColor = Color.Yellow


                Label97.BackColor = Color.Yellow


                Label98.BackColor = Color.Yellow


                Label99.BackColor = Color.Yellow


            End If



            If ComboBox5.SelectedIndex = 1 Then


                Label73.BackColor = Color.White


                Label74.BackColor = Color.White


                Label75.BackColor = Color.White


                Label76.BackColor = Color.White


                Label77.BackColor = Color.White


                Label78.BackColor = Color.White


                Label79.BackColor = Color.White


                Label80.BackColor = Color.Yellow


                Label81.BackColor = Color.Yellow


                Label82.BackColor = Color.Yellow


                Label83.BackColor = Color.Yellow


                Label84.BackColor = Color.Yellow


                Label85.BackColor = Color.Yellow


                Label86.BackColor = Color.Yellow


                Label87.BackColor = Color.Yellow


                Label88.BackColor = Color.Yellow


                Label89.BackColor = Color.Yellow


                Label90.BackColor = Color.Yellow


                Label91.BackColor = Color.Yellow


                Label92.BackColor = Color.Yellow


                Label93.BackColor = Color.Yellow


                Label94.BackColor = Color.Yellow


                Label95.BackColor = Color.Yellow


                Label96.BackColor = Color.Yellow


                Label97.BackColor = Color.Yellow


                Label98.BackColor = Color.Yellow


                Label99.BackColor = Color.Yellow


            End If



            If ComboBox5.SelectedIndex = 2 Then


                Label73.BackColor = Color.White


                Label74.BackColor = Color.White


                Label75.BackColor = Color.White


                Label76.BackColor = Color.White


                Label77.BackColor = Color.White


                Label78.BackColor = Color.White


                Label79.BackColor = Color.White


                Label80.BackColor = Color.White


                Label81.BackColor = Color.White


                Label82.BackColor = Color.Yellow


                Label83.BackColor = Color.Yellow


                Label84.BackColor = Color.Yellow


                Label85.BackColor = Color.Yellow


                Label86.BackColor = Color.Yellow


                Label87.BackColor = Color.Yellow


                Label88.BackColor = Color.Yellow


                Label89.BackColor = Color.Yellow


                Label90.BackColor = Color.Yellow


                Label91.BackColor = Color.Yellow


                Label92.BackColor = Color.Yellow


                Label93.BackColor = Color.Yellow


                Label94.BackColor = Color.Yellow


                Label95.BackColor = Color.Yellow


                Label96.BackColor = Color.Yellow


                Label97.BackColor = Color.Yellow


                Label98.BackColor = Color.Yellow


                Label99.BackColor = Color.Yellow


            End If



            If ComboBox5.SelectedIndex = 3 Then


                Label73.BackColor = Color.White


                Label74.BackColor = Color.White


                Label75.BackColor = Color.White


                Label76.BackColor = Color.White


                Label77.BackColor = Color.White


                Label78.BackColor = Color.White


                Label79.BackColor = Color.White


                Label80.BackColor = Color.White


                Label81.BackColor = Color.White


                Label82.BackColor = Color.White


                Label83.BackColor = Color.White


                Label84.BackColor = Color.Yellow


                Label85.BackColor = Color.Yellow


                Label86.BackColor = Color.Yellow


                Label87.BackColor = Color.Yellow


                Label88.BackColor = Color.Yellow


                Label89.BackColor = Color.Yellow


                Label90.BackColor = Color.Yellow


                Label91.BackColor = Color.Yellow


                Label92.BackColor = Color.Yellow


                Label93.BackColor = Color.Yellow


                Label94.BackColor = Color.Yellow


                Label95.BackColor = Color.Yellow


                Label96.BackColor = Color.Yellow


                Label97.BackColor = Color.Yellow


                Label98.BackColor = Color.Yellow


                Label99.BackColor = Color.Yellow


            End If



            If ComboBox5.SelectedIndex = 4 Then


                Label73.BackColor = Color.White


                Label74.BackColor = Color.White


                Label75.BackColor = Color.White


                Label76.BackColor = Color.White


                Label77.BackColor = Color.White


                Label78.BackColor = Color.White


                Label79.BackColor = Color.White


                Label80.BackColor = Color.White


                Label81.BackColor = Color.White


                Label82.BackColor = Color.White


                Label83.BackColor = Color.White


                Label84.BackColor = Color.White


                Label85.BackColor = Color.White


                Label86.BackColor = Color.Yellow


                Label87.BackColor = Color.Yellow


                Label88.BackColor = Color.Yellow


                Label89.BackColor = Color.Yellow


                Label90.BackColor = Color.Yellow


                Label91.BackColor = Color.Yellow


                Label92.BackColor = Color.Yellow


                Label93.BackColor = Color.Yellow


                Label94.BackColor = Color.Yellow


                Label95.BackColor = Color.Yellow


                Label96.BackColor = Color.Yellow


                Label97.BackColor = Color.Yellow


                Label98.BackColor = Color.Yellow


                Label99.BackColor = Color.Yellow


            End If



            If ComboBox5.SelectedIndex = 5 Then


                Label73.BackColor = Color.White


                Label74.BackColor = Color.White


                Label75.BackColor = Color.White


                Label76.BackColor = Color.White


                Label77.BackColor = Color.White


                Label78.BackColor = Color.White


                Label79.BackColor = Color.White


                Label80.BackColor = Color.White


                Label81.BackColor = Color.White


                Label82.BackColor = Color.White


                Label83.BackColor = Color.White


                Label84.BackColor = Color.White


                Label85.BackColor = Color.White


                Label86.BackColor = Color.White


                Label87.BackColor = Color.White


                Label88.BackColor = Color.White


                Label89.BackColor = Color.White


                Label90.BackColor = Color.Yellow


                Label91.BackColor = Color.Yellow


                Label92.BackColor = Color.Yellow


                Label93.BackColor = Color.Yellow


                Label94.BackColor = Color.Yellow


                Label95.BackColor = Color.Yellow


                Label96.BackColor = Color.Yellow


                Label97.BackColor = Color.Yellow


                Label98.BackColor = Color.Yellow


                Label99.BackColor = Color.Yellow


            End If


        End If



        If TextBox11.Text = 39 Then


            If ComboBox5.SelectedIndex = 0 Then


                Label73.BackColor = Color.White


                Label74.BackColor = Color.White


                Label75.BackColor = Color.White


                Label76.BackColor = Color.White


                Label77.BackColor = Color.White


                Label78.BackColor = Color.White


                Label79.BackColor = Color.White


                Label80.BackColor = Color.Yellow


                Label81.BackColor = Color.Yellow


                Label82.BackColor = Color.Yellow


                Label83.BackColor = Color.Yellow


                Label84.BackColor = Color.Yellow


                Label85.BackColor = Color.Yellow


                Label86.BackColor = Color.Yellow


                Label87.BackColor = Color.Yellow


                Label88.BackColor = Color.Yellow


                Label89.BackColor = Color.Yellow


                Label90.BackColor = Color.Yellow


                Label91.BackColor = Color.Yellow


                Label92.BackColor = Color.Yellow


                Label93.BackColor = Color.Yellow


                Label94.BackColor = Color.Yellow


                Label95.BackColor = Color.Yellow


                Label96.BackColor = Color.Yellow


                Label97.BackColor = Color.Yellow


                Label98.BackColor = Color.Yellow


                Label99.BackColor = Color.Yellow


            End If



            If ComboBox5.SelectedIndex = 1 Then


                Label73.BackColor = Color.White


                Label74.BackColor = Color.White


                Label75.BackColor = Color.White


                Label76.BackColor = Color.White


                Label77.BackColor = Color.White


                Label78.BackColor = Color.White


                Label79.BackColor = Color.White


                Label80.BackColor = Color.White


                Label81.BackColor = Color.Yellow


                Label82.BackColor = Color.Yellow


                Label83.BackColor = Color.Yellow


                Label84.BackColor = Color.Yellow


                Label85.BackColor = Color.Yellow


                Label86.BackColor = Color.Yellow


                Label87.BackColor = Color.Yellow


                Label88.BackColor = Color.Yellow


                Label89.BackColor = Color.Yellow


                Label90.BackColor = Color.Yellow


                Label91.BackColor = Color.Yellow


                Label92.BackColor = Color.Yellow


                Label93.BackColor = Color.Yellow


                Label94.BackColor = Color.Yellow


                Label95.BackColor = Color.Yellow


                Label96.BackColor = Color.Yellow


                Label97.BackColor = Color.Yellow


                Label98.BackColor = Color.Yellow


                Label99.BackColor = Color.Yellow


            End If



            If ComboBox5.SelectedIndex = 2 Then


                Label73.BackColor = Color.White


                Label74.BackColor = Color.White


                Label75.BackColor = Color.White


                Label76.BackColor = Color.White


                Label77.BackColor = Color.White


                Label78.BackColor = Color.White


                Label79.BackColor = Color.White


                Label80.BackColor = Color.White


                Label81.BackColor = Color.White


                Label82.BackColor = Color.White


                Label83.BackColor = Color.Yellow


                Label84.BackColor = Color.Yellow


                Label85.BackColor = Color.Yellow


                Label86.BackColor = Color.Yellow


                Label87.BackColor = Color.Yellow


                Label88.BackColor = Color.Yellow


                Label89.BackColor = Color.Yellow


                Label90.BackColor = Color.Yellow


                Label91.BackColor = Color.Yellow


                Label92.BackColor = Color.Yellow


                Label93.BackColor = Color.Yellow


                Label94.BackColor = Color.Yellow


                Label95.BackColor = Color.Yellow


                Label96.BackColor = Color.Yellow


                Label97.BackColor = Color.Yellow


                Label98.BackColor = Color.Yellow


                Label99.BackColor = Color.Yellow


            End If



            If ComboBox5.SelectedIndex = 3 Then


                Label73.BackColor = Color.White


                Label74.BackColor = Color.White


                Label75.BackColor = Color.White


                Label76.BackColor = Color.White


                Label77.BackColor = Color.White


                Label78.BackColor = Color.White


                Label79.BackColor = Color.White


                Label80.BackColor = Color.White


                Label81.BackColor = Color.White


                Label82.BackColor = Color.White


                Label83.BackColor = Color.White


                Label84.BackColor = Color.White


                Label85.BackColor = Color.Yellow


                Label86.BackColor = Color.Yellow


                Label87.BackColor = Color.Yellow


                Label88.BackColor = Color.Yellow


                Label89.BackColor = Color.Yellow


                Label90.BackColor = Color.Yellow


                Label91.BackColor = Color.Yellow


                Label92.BackColor = Color.Yellow


                Label93.BackColor = Color.Yellow


                Label94.BackColor = Color.Yellow


                Label95.BackColor = Color.Yellow


                Label96.BackColor = Color.Yellow


                Label97.BackColor = Color.Yellow


                Label98.BackColor = Color.Yellow


                Label99.BackColor = Color.Yellow


            End If



            If ComboBox5.SelectedIndex = 4 Then


                Label73.BackColor = Color.White


                Label74.BackColor = Color.White


                Label75.BackColor = Color.White


                Label76.BackColor = Color.White


                Label77.BackColor = Color.White


                Label78.BackColor = Color.White


                Label79.BackColor = Color.White


                Label80.BackColor = Color.White


                Label81.BackColor = Color.White


                Label82.BackColor = Color.White


                Label83.BackColor = Color.White


                Label84.BackColor = Color.White


                Label85.BackColor = Color.White


                Label86.BackColor = Color.White


                Label87.BackColor = Color.Yellow


                Label88.BackColor = Color.Yellow


                Label89.BackColor = Color.Yellow


                Label90.BackColor = Color.Yellow


                Label91.BackColor = Color.Yellow


                Label92.BackColor = Color.Yellow


                Label93.BackColor = Color.Yellow


                Label94.BackColor = Color.Yellow


                Label95.BackColor = Color.Yellow


                Label96.BackColor = Color.Yellow


                Label97.BackColor = Color.Yellow


                Label98.BackColor = Color.Yellow


                Label99.BackColor = Color.Yellow


            End If



            If ComboBox5.SelectedIndex = 5 Then


                Label73.BackColor = Color.White


                Label74.BackColor = Color.White


                Label75.BackColor = Color.White


                Label76.BackColor = Color.White


                Label77.BackColor = Color.White


                Label78.BackColor = Color.White


                Label79.BackColor = Color.White


                Label80.BackColor = Color.White


                Label81.BackColor = Color.White


                Label82.BackColor = Color.White


                Label83.BackColor = Color.White


                Label84.BackColor = Color.White


                Label85.BackColor = Color.White


                Label86.BackColor = Color.White


                Label87.BackColor = Color.White


                Label88.BackColor = Color.White


                Label89.BackColor = Color.White


                Label90.BackColor = Color.White


                Label91.BackColor = Color.Red


                Label92.BackColor = Color.Red


                Label93.BackColor = Color.Red


                Label94.BackColor = Color.Red


                Label95.BackColor = Color.Red


                Label96.BackColor = Color.Red


                Label97.BackColor = Color.Red


                Label98.BackColor = Color.Red


                Label99.BackColor = Color.Red


            End If


        End If


    End Sub



    Private Sub LinkLabel1_LinkClicked(sender As Object, e As LinkLabelLinkClickedEventArgs)


        Dim Outl As Object



        Outl = CreateObject("Outlook.Application")


        If Outl IsNot Nothing Then


            Dim omsg As Object



            omsg = Outl.CreateItem(0)


            omsg.Display(True)



        End If


    End Sub



    Private Sub LinkLabel2_LinkClicked(sender As Object, e As LinkLabelLinkClickedEventArgs)


        Dim Outl As Object



        Outl = CreateObject("Outlook.Application")


        If Outl IsNot Nothing Then


            Dim omsg As Object



            omsg = Outl.CreateItem(0)


            omsg.Display(True)



        End If


    End Sub



End Class
