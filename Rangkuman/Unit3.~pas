unit Unit3;

interface

uses
  Windows, Messages, SysUtils, Variants, Classes, Graphics, Controls, Forms,
  Dialogs, StdCtrls, ExtCtrls, jpeg;

type
  TForm3 = class(TForm)
    Image1: TImage;
    Image2: TImage;
    Image3: TImage;
    Image4: TImage;
    Image5: TImage;
    Image6: TImage;
    Shape1: TShape;
    Panel1: TPanel;
    Panel2: TPanel;
    Panel3: TPanel;
    Panel4: TPanel;
    Panel5: TPanel;
    Panel6: TPanel;
    Panel7: TPanel;
    Memo1: TMemo;
    Panel8: TPanel;
    Edit1: TEdit;
    Button1: TButton;
    Edit2: TEdit;
    Label1: TLabel;
    Label2: TLabel;
    Button2: TButton;
    Shape2: TShape;
    procedure Button1Click(Sender: TObject);
    procedure Button2Click(Sender: TObject);
    procedure Panel7Click(Sender: TObject);
    procedure Panel1Click(Sender: TObject);
    procedure Panel4Click(Sender: TObject);
    procedure Panel3Click(Sender: TObject);
    procedure Panel6Click(Sender: TObject);
    procedure Panel2Click(Sender: TObject);
    procedure Panel5Click(Sender: TObject);
    procedure Edit1KeyPress(Sender: TObject; var Key: Char);
    procedure Edit2KeyPress(Sender: TObject; var Key: Char);
    procedure Panel1MouseMove(Sender: TObject; Shift: TShiftState; X,
      Y: Integer);
    procedure Panel2MouseMove(Sender: TObject; Shift: TShiftState; X,
      Y: Integer);
    procedure Panel3MouseMove(Sender: TObject; Shift: TShiftState; X,
      Y: Integer);
    procedure Panel4MouseMove(Sender: TObject; Shift: TShiftState; X,
      Y: Integer);
    procedure Panel5MouseMove(Sender: TObject; Shift: TShiftState; X,
      Y: Integer);
    procedure Panel6MouseMove(Sender: TObject; Shift: TShiftState; X,
      Y: Integer);
    procedure Image4MouseMove(Sender: TObject; Shift: TShiftState; X,
      Y: Integer);
    procedure Image5MouseMove(Sender: TObject; Shift: TShiftState; X,
      Y: Integer);
    procedure Image6MouseMove(Sender: TObject; Shift: TShiftState; X,
      Y: Integer);
    procedure Panel7MouseMove(Sender: TObject; Shift: TShiftState; X,
      Y: Integer);
    procedure Image1MouseMove(Sender: TObject; Shift: TShiftState; X,
      Y: Integer);
    procedure Shape1MouseMove(Sender: TObject; Shift: TShiftState; X,
      Y: Integer);
  private
    { Private declarations }
  public
    { Public declarations }
  end;

var
  Form3: TForm3;

implementation

uses Unit2;

{$R *.dfm}

procedure TForm3.Button1Click(Sender: TObject);
begin
      if edit1.Text=('') then showmessage('Harap periksa kembali!')
      else begin
        if (strtoint(edit1.Text)<=30) then showmessage('Skor D')
        else if (strtoint(edit1.text)<=50) then showmessage('Skor C')
        else if (strtoint(edit1.text)<=70) then showmessage('Skor B')
        else if (strtoint(edit1.text)<=100) then showmessage('Skor A')
        else showmessage('Input Error!');
      end;
end;

procedure TForm3.Button2Click(Sender: TObject);
begin
      if edit1.Text=('') then showmessage('Harap periksa kembali!')
      else begin
        case (strtoint(edit2.Text)) of
        1 : showmessage('Angka Satu');
        2 : showmessage('Angka Dua');
        3 : showmessage('Angka Tiga');
        else showmessage('Input Error!');
        end;
      end;
end;

procedure TForm3.Panel7Click(Sender: TObject);
begin
      form3.hide;
      form2.show;
end;

procedure TForm3.Panel1Click(Sender: TObject);
begin
      shape2.Visible := false;
      image2.visible := false;
      image3.Visible := false;
      panel8.Visible := false;
      memo1.clear; memo1.Visible := true; memo1.Height := 433;
      memo1.text := ('Percabangan adalah suatu perintah yang akan mengambil keputusan dari beberapa kondisi.'+sLineBreak+sLineBreak+'Dalam bahasa pemrograman Delphi terdapat dua percabangan, yaitu percabangan if dan percabangan case'+sLineBreak+sLineBreak+'Percabangan IF'+sLineBreak+'Percabangan untuk kondisi pilihan tunggal'+sLineBreak+'Percabangan yang digunakan untuk menentukan sebuah pilihan dengan kondisi tunggal'+sLineBreak+sLineBreak+'Bentuk Umum'+sLineBreak+'If Syarat then hasil;'+sLineBreak+'Contoh'+sLineBreak+'If Nilai < 40 then keterangan = ‘Tidak Lulus‘;'+sLineBreak+sLineBreak+'Percabangan untuk kondisi majemuk'+sLineBreak+'Percabangan yang digunakan untuk menentukan pilihan dengan kondisi yang harus dipenuhi lebih dari satu.'+sLineBreak+sLineBreak+'Bentuk Umum'+sLineBreak+'if Syarat1 then Hasil1'+sLineBreak+'else if Syarat2 then Hasil2'+sLineBreak+'Else .....'+sLineBreak+'end;');
end;

procedure TForm3.Panel4Click(Sender: TObject);
begin
      shape2.Visible := false;
      image2.visible := false;
      image3.Visible := false;
      panel8.Visible := false;
      memo1.clear; memo1.Visible := true; memo1.Height := 433;
      memo1.Text := ('Case of merupakan metode lain dari sebuah percabangan, yang berfungsi sama seperti fungsi if untuk melakukan seleksi atas beberapa pilihan dengan kondisi sebagai syarat yang harus terpenuhi.'+sLineBreak+sLineBreak+'Tidak terdapat perbedaan terhadap Fungsi case dan if tetapi untuk penulisan fungsi case lebih mudah diterapkn untuk pilihan atau kondisi lebih dari satu.'+sLineBreak+sLineBreak+'Bentuk Umum'+sLineBreak+'Case <Variabel> of'+sLineBreak+'<Pilihan1> : <Hasil1>;'+sLineBreak+'<Pilihan2> : <Hasil2>;'+sLineBreak+'<PilihanN> : <HasilN>;'+sLineBreak+'Else HasilX'+sLineBreak+'End;');
end;

procedure TForm3.Panel3Click(Sender: TObject);
begin
      shape2.Visible := false;
      image2.visible := false;
      image3.Visible := false;
      memo1.Visible := true; memo1.Clear; memo1.Height := 177;
      memo1.Text := ('Script'+sLineBreak+'if (strtoint(edit1.Text)<=30) then showmessage('+QuotedStr('Skor D')+')'+sLineBreak+'else if (strtoint(edit1.text)<=50) then showmessage('+QuotedStr('Skor C')+')'+sLineBreak+'else if (strtoint(edit1.text)<=70) then showmessage('+QuotedStr('Skor B')+')'+sLineBreak+'else if (strtoint(edit1.text)<=100) then showmessage('+QuotedStr('Skor B')+')'+sLineBreak+'else showmessage('+QuotedStr('Input Error')+');');

      panel8.visible := true;

      edit1.Visible := true;
      edit2.visible := false;
      label1.visible := true;
      label2.visible := false;
      button1.Visible := true; button1.Top := 216;
      button2.Visible := false;
end;

procedure TForm3.Panel6Click(Sender: TObject);
begin
      shape2.Visible := false;
      image2.visible := false;
      image3.Visible := false;
      memo1.Visible := true; memo1.Clear; memo1.Height := 177;
      memo1.text := ('Script'+sLineBreak+'case (strtoint(edit2.text)) of'+sLineBreak+'1 : showmessage('+QuotedStr('Angka Satu')+');'+sLineBreak+'2 : Showmessage('+QuotedStr('Angka Dua')+');'+sLineBreak+'3 : Showmessage('+QuotedStr('Angka Tiga')+');'+sLineBreak+'else showmessage('+QuotedStr('Input Error!')+');'+sLineBreak+'end;');

      panel8.visible := true;

      edit2.Visible := true; edit2.Top := 24;
      edit1.visible := false;
      label2.visible := true; label2.Top := 8;
      label1.visible := false;
      button2.Visible := true;
      button1.Visible := false;
end;

procedure TForm3.Panel2Click(Sender: TObject);
begin
      memo1.Visible := false;
      panel8.visible := false;
      shape2.Visible := true;
      image2.Visible := true;

      shape2.Height := 433;
      shape2.Left := 424;
      shape2.top := 8;
      shape2.Width := 489;

      image2.Height := 417;
      image2.Left := 432;
      image2.top := 16;
      image2.Width := 473;

      image3.Visible := false;
end;

procedure TForm3.Panel5Click(Sender: TObject);
begin
      memo1.Visible := false;
      panel8.visible := false;
      shape2.Visible := true;
      image3.Visible := true;

      shape2.Height := 433;
      shape2.Left := 424;
      shape2.top := 8;
      shape2.Width := 489;
      
      image3.Height := 417;
      image3.Left := 432;
      image3.top := 16;
      image3.Width := 473;

      image2.Visible := false;
end;

procedure TForm3.Edit1KeyPress(Sender: TObject; var Key: Char);
begin
      if not(key in['0'..'9', #8]) then key := #0;
end;

procedure TForm3.Edit2KeyPress(Sender: TObject; var Key: Char);
begin
      if not(key in['0'..'9', #8]) then key := #0;
end;

procedure TForm3.Panel1MouseMove(Sender: TObject; Shift: TShiftState; X,
  Y: Integer);
begin
      panel1.Left := 0;
      panel2.Left := 104;
      panel3.left := 208;

      image4.Left := 312;
      image5.Left := 0;
      image6.Left := 0;

      panel4.Left := -110;
      panel5.Left := -110;
      panel6.Left := -110;

      panel7.Left := -315;

      panel1.Color := clactivecaption;
      panel2.color := clinactivecaption;
      panel3.color := clinactivecaption;
      panel4.Color := clinactivecaption;
      panel5.Color := clinactivecaption;
      panel6.color := clinactivecaption;
end;

procedure TForm3.Panel2MouseMove(Sender: TObject; Shift: TShiftState; X,
  Y: Integer);
begin
      panel1.Left := 0;
      panel2.Left := 104;
      panel3.left := 208;

      image4.Left := 312;
      image5.Left := 0;
      image6.Left := 0;

      panel4.Left := -110;
      panel5.Left := -110;
      panel6.Left := -110;

      panel7.Left := -315;
      
      panel1.Color := clinactivecaption;
      panel2.color := clactivecaption;
      panel3.color := clinactivecaption;
      panel4.Color := clinactivecaption;
      panel5.Color := clinactivecaption;
      panel6.color := clinactivecaption;
end;

procedure TForm3.Panel3MouseMove(Sender: TObject; Shift: TShiftState; X,
  Y: Integer);
begin
      panel1.Left := 0;
      panel2.Left := 104;
      panel3.left := 208;

      image4.Left := 312;
      image5.Left := 0;
      image6.Left := 0;

      panel4.Left := -110;
      panel5.Left := -110;
      panel6.Left := -110;

      panel7.Left := -315;
      
      panel1.Color := clinactivecaption;
      panel2.color := clinactivecaption;
      panel3.color := clactivecaption;
      panel4.Color := clinactivecaption;
      panel5.Color := clinactivecaption;
      panel6.color := clinactivecaption;
end;

procedure TForm3.Panel4MouseMove(Sender: TObject; Shift: TShiftState; X,
  Y: Integer);
begin
      panel4.Left := 0;
      panel5.Left := 104;
      panel6.left := 208;

      image4.Left := 0;
      image5.Left := 312;
      image6.Left := 0;

      panel1.Left := -110;
      panel2.Left := -110;
      panel3.Left := -110;

      panel7.Left := -315;

      panel1.Color := clinactivecaption;
      panel2.color := clinactivecaption;
      panel3.color := clinactivecaption;
      panel4.Color := clactivecaption;
      panel5.Color := clinactivecaption;
      panel6.color := clinactivecaption;
end;

procedure TForm3.Panel5MouseMove(Sender: TObject; Shift: TShiftState; X,
  Y: Integer);
begin
      panel4.Left := 0;
      panel5.Left := 104;
      panel6.left := 208;

      image4.Left := 0;
      image5.Left := 312;
      image6.Left := 0;

      panel1.Left := -110;
      panel2.Left := -110;
      panel3.Left := -110;

      panel7.Left := -315;

      panel1.Color := clinactivecaption;
      panel2.color := clinactivecaption;
      panel3.color := clinactivecaption;
      panel4.Color := clinactivecaption;
      panel5.Color := clactivecaption;
      panel6.color := clinactivecaption;
end;

procedure TForm3.Panel6MouseMove(Sender: TObject; Shift: TShiftState; X,
  Y: Integer);
begin
      panel4.Left := 0;
      panel5.Left := 104;
      panel6.left := 208;

      image4.Left := 0;
      image5.Left := 312;
      image6.Left := 0;

      panel1.Left := -110;
      panel2.Left := -110;
      panel3.Left := -110;

      panel7.Left := -315;
      
      panel1.Color := clinactivecaption;
      panel2.color := clinactivecaption;
      panel3.color := clinactivecaption;
      panel4.Color := clinactivecaption;
      panel5.Color := clinactivecaption;
      panel6.color := clactivecaption;
end;

procedure TForm3.Image4MouseMove(Sender: TObject; Shift: TShiftState; X,
  Y: Integer);
begin
      panel1.Left := 0;
      panel2.Left := 104;
      panel3.left := 208;

      image4.Left := 312;
      image5.Left := 0;
      image6.Left := 0;

      panel4.Left := -110;
      panel5.Left := -110;
      panel6.Left := -110;

      panel7.Left := -315;
end;

procedure TForm3.Image5MouseMove(Sender: TObject; Shift: TShiftState; X,
  Y: Integer);
begin
      panel4.Left := 0;
      panel5.Left := 104;
      panel6.left := 208;

      image4.Left := 0;
      image5.Left := 312;
      image6.Left := 0;

      panel1.Left := -110;
      panel2.Left := -110;
      panel3.Left := -110;

      panel7.Left := -315;
end;

procedure TForm3.Image6MouseMove(Sender: TObject; Shift: TShiftState; X,
  Y: Integer);
begin
      panel1.Left := -110;
      panel2.Left := -110;
      panel3.Left := -110;
      panel4.Left := -110;
      panel5.Left := -110;
      panel6.left := -110;

      image4.Left := 0;
      image5.Left := 0;
      image6.Left := 312;

      panel7.Left := 0;
end;

procedure TForm3.Panel7MouseMove(Sender: TObject; Shift: TShiftState; X,
  Y: Integer);
begin
      panel1.Left := -110;
      panel2.Left := -110;
      panel3.Left := -110;
      panel4.Left := -110;
      panel5.Left := -110;
      panel6.left := -110;

      image4.Left := 0;
      image5.Left := 0;
      image6.Left := 312;

      panel7.Left := 0;
end;

procedure TForm3.Image1MouseMove(Sender: TObject; Shift: TShiftState; X,
  Y: Integer);
begin
      panel1.Left := -110;
      panel2.Left := -110;
      panel3.Left := -110;
      panel4.Left := -110;
      panel5.Left := -110;
      panel6.left := -110;

      image4.Left := 0;
      image5.Left := 0;
      image6.Left := 0;

      panel7.Left := -315;
end;

procedure TForm3.Shape1MouseMove(Sender: TObject; Shift: TShiftState; X,
  Y: Integer);
begin
      panel1.Left := -110;
      panel2.Left := -110;
      panel3.Left := -110;
      panel4.Left := -110;
      panel5.Left := -110;
      panel6.left := -110;

      image4.Left := 0;
      image5.Left := 0;
      image6.Left := 0;

      panel7.Left := -315;
end;

end.
