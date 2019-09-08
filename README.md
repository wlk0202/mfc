# mfc
#계산기 
void CCalculatorDlg :: OnBnClickedButton1 ()
{
   CString title;
   GetDlgItemText(IDC_EDIT1, title);
   SetWindowText(title);
}


void CCalculatorDlg::OnBnClickedButton2()
{
   int a = GetDlgItemInt(IDC_EDIT2);
   int b = GetDlgItemInt(IDC_EDIT3);
   int c = a + b;
   SetDlgItemInt(IDC_EDIT4, c);
}


void CCalculatorDlg::OnBnClickedButton3()
{
   int a = GetDlgItemInt(IDC_EDIT2);
   int b = GetDlgItemInt(IDC_EDIT3);
   int c = a - b;
   SetDlgItemInt(IDC_EDIT4, c);
}   

void CCalculatorDlg::OnBnClickedButton4()
{
   int a = GetDlgItemInt(IDC_EDIT2);
   int b = GetDlgItemInt(IDC_EDIT3);
   int c = a * b;
   SetDlgItemInt(IDC_EDIT4, c);
}


void CCalculatorDlg::OnBnClickedButton5()
{
   int a = GetDlgItemInt(IDC_EDIT2);
   int b = GetDlgItemInt(IDC_EDIT3);
   int c = a / b;
   SetDlgItemInt(IDC_EDIT4, c);
}
