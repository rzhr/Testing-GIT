unit Unit4;

interface

uses
  Windows, Messages, SysUtils, Variants, Classes, Graphics, Controls, Forms,
  Dialogs, StdCtrls, ExtCtrls, jpeg;

type
  TForm4 = class(TForm)
    Image1: TImage;
    Image2: TImage;
    Image3: TImage;
    Image4: TImage;
    Image5: TImage;
    Image6: TImage;
    Shape1: TShape;
    Panel1: TPanel;
    Memo1: TMemo;
    Button1: TButton;
    Memo2: TMemo;
    Image7: TImage;
    Image8: TImage;
    Image9: TImage;
    Image10: TImage;
    Shape2: TShape;
    Panel2: TPanel;
    Panel4: TPanel;
    Panel3: TPanel;
    Panel5: TPanel;
    Panel6: TPanel;
    Panel7: TPanel;
    Panel8: TPanel;
    Panel9: TPanel;
    Panel10: TPanel;
    Panel11: TPanel;
    Panel12: TPanel;
    Panel13: TPanel;
    Panel14: TPanel;
    Button2: TButton;
    procedure Panel14Click(Sender: TObject);
    procedure Button1Click(Sender: TObject);
    procedure Panel7Click(Sender: TObject);
    procedure Panel11Click(Sender: TObject);
    procedure Panel13Click(Sender: TObject);
    procedure Button2Click(Sender: TObject);
    procedure Panel9Click(Sender: TObject);
    procedure Panel2Click(Sender: TObject);
    procedure Panel4Click(Sender: TObject);
    procedure Panel3Click(Sender: TObject);
    procedure Panel5Click(Sender: TObject);
    procedure Panel6Click(Sender: TObject);
    procedure Panel8Click(Sender: TObject);
    procedure Panel10Click(Sender: TObject);
    procedure Panel12Click(Sender: TObject);
    procedure Panel2MouseMove(Sender: TObject; Shift: TShiftState; X,
      Y: Integer);
    procedure Panel6MouseMove(Sender: TObject; Shift: TShiftState; X,
      Y: Integer);
    procedure Panel7MouseMove(Sender: TObject; Shift: TShiftState; X,
      Y: Integer);
    procedure Panel4MouseMove(Sender: TObject; Shift: TShiftState; X,
      Y: Integer);
    procedure Panel8MouseMove(Sender: TObject; Shift: TShiftState; X,
      Y: Integer);
    procedure Panel9MouseMove(Sender: TObject; Shift: TShiftState; X,
      Y: Integer);
    procedure Panel3MouseMove(Sender: TObject; Shift: TShiftState; X,
      Y: Integer);
    procedure Panel10MouseMove(Sender: TObject; Shift: TShiftState; X,
      Y: Integer);
    procedure Panel11MouseMove(Sender: TObject; Shift: TShiftState; X,
      Y: Integer);
    procedure Panel5MouseMove(Sender: TObject; Shift: TShiftState; X,
      Y: Integer);
    procedure Panel12MouseMove(Sender: TObject; Shift: TShiftState; X,
      Y: Integer);
    procedure Panel13MouseMove(Sender: TObject; Shift: TShiftState; X,
      Y: Integer);
    procedure Image2MouseMove(Sender: TObject; Shift: TShiftState; X,
      Y: Integer);
    procedure Image3MouseMove(Sender: TObject; Shift: TShiftState; X,
      Y: Integer);
    procedure Image4MouseMove(Sender: TObject; Shift: TShiftState; X,
      Y: Integer);
    procedure Image5MouseMove(Sender: TObject; Shift: TShiftState; X,
      Y: Integer);
    procedure Image6MouseMove(Sender: TObject; Shift: TShiftState; X,
      Y: Integer);
    procedure Panel14MouseMove(Sender: TObject; Shift: TShiftState; X,
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
  Form4: TForm4;

implementation

uses Unit2;

{$R *.dfm}

procedure TForm4.Panel14Click(Sender: TObject);
begin
      form4.hide;
      form2.show;
end;

procedure TForm4.Button1Click(Sender: TObject);
var i : integer;
begin
      for i := 1 to 10 do
        memo2.Lines.add('Ini tulisan ke-'+inttostr(i));
end;

procedure TForm4.Panel7Click(Sender: TObject);
begin
      shape2.visible := false;
      image7.Visible := false;
      image8.Visible := false;
      image9.visible := false;
      image10.visible := false;
      
      panel1.Visible := true;
      button1.Visible := true;
      button2.Visible := false;

      memo1.Visible := true; memo1.Height := 177;
      memo2.visible := true; memo2.clear;
      memo1.clear;
      memo1.Text := ('Script'+sLineBreak+'var i : integer;'+sLineBreak+sLineBreak+'for i := 1 to 10 do'+sLineBreak+'memo2.lines.add('+QuotedStr('Ini tulisan ke-')+'+inttostr(i));)');
end;

procedure TForm4.Panel11Click(Sender: TObject);
begin
      shape2.visible := false;
      image7.Visible := false;
      image8.Visible := false;
      image9.visible := false;
      image10.visible := false;
      
      panel1.Visible := true;
      button1.Visible := true;
      button2.Visible := false;

      memo1.Visible := true; memo1.Height := 177;
      memo2.visible := true; memo2.clear;
      memo1.clear;
      memo1.Text := ('Script'+sLineBreak+'var i : integer;'+sLineBreak+sLineBreak+'i := 1'+sLineBreak+'while i <= 10 do begin'+sLineBreak+'memo2.lines.add('+QuotedStr('Ini tulisan ke-')+'+inttostr(i));)'+sLineBreak+'inc(i)'+sLineBreak+'end;');
end;

procedure TForm4.Panel13Click(Sender: TObject);
begin
      shape2.visible := false;
      image7.Visible := false;
      image8.Visible := false;
      image9.visible := false;
      image10.visible := false;
      
      panel1.Visible := true;
      button1.Visible := true;
      button2.Visible := false;

      memo1.Visible := true; memo1.Height := 177;
      memo2.visible := true; memo2.clear;
      memo1.clear;
      memo1.Text := ('Script'+sLineBreak+'var i : integer;'+sLineBreak+sLineBreak+'i := 1'+sLineBreak+'repeat'+sLineBreak+'memo2.lines.add('+QuotedStr('Ini tulisan ke-')+'+inttostr(i));)'+sLineBreak+'inc(i)'+sLineBreak+'until i>10;');
end;

procedure TForm4.Button2Click(Sender: TObject);
var i : integer;
begin
       for i := 10 downto 1 do
        memo2.Lines.add('Ini tulisan ke-'+inttostr(i));
end;

procedure TForm4.Panel9Click(Sender: TObject);
begin
      shape2.visible := false;
      image7.Visible := false;
      image8.Visible := false;
      image9.visible := false;
      image10.visible := false;
      
      panel1.Visible := true;
      button2.Visible := true;
      button1.Visible := false;

      memo1.Visible := true; memo1.Height := 177;
      memo2.visible := true; memo2.clear;
      button2.top := 8;
      memo1.clear;
      memo1.Text := ('Script'+sLineBreak+'var i : integer;'+sLineBreak+sLineBreak+'for i := 10 downto 1 do'+sLineBreak+'memo2.lines.add('+QuotedStr('Ini tulisan ke-')+'+inttostr(i));)');
end;

procedure TForm4.Panel2Click(Sender: TObject);
begin
      shape2.visible := false;
      image7.Visible := false;
      image8.Visible := false;
      image9.visible := false;
      image10.visible := false;

      memo1.Visible := true; memo1.Height := 433;
      panel1.visible := false;

      memo1.Text := ('Perulangan dengan statement for adalah perulangan yang digunakan untuk melakukan suatu proses dalam sebuah blok program.'+sLineBreak+'Proses perulangan For–To–Do dimulai dengan nilai terkecil ke besar.'+sLineBreak+sLineBreak+'Bentuk Umum'+sLineBreak+'for <Variabel> := <Nilai awal> to <Nilai akhir> do <Statement>');
end;

procedure TForm4.Panel4Click(Sender: TObject);
begin
      shape2.visible := false;
      image7.Visible := false;
      image8.Visible := false;
      image9.visible := false;
      image10.visible := false;
      
      memo1.Visible := true; memo1.Height := 433;
      panel1.visible := false;

      memo1.Text := ('Perulangan For-Downto-Do adalah perulangan yang mengihutng suatu proses dengan nilai awal besar dan nilai akhinya lebih kecil, maka variabel sebagai control program yang diperoleh adalah dari besar ke kecil.'+sLineBreak+sLineBreak+'Bentuk Umum'+sLineBreak+'for <Variabel> := <Nilai awal> downto <Nilai akhir> do <Statement>');
end;

procedure TForm4.Panel3Click(Sender: TObject);
begin
      shape2.visible := false;
      image7.Visible := false;
      image8.Visible := false;
      image9.visible := false;
      image10.visible := false;

      memo1.Visible := true; memo1.Height := 433;
      panel1.visible := false;

      memo1.Text := ('Perulangan While Do adalah statement perulangan akan terus melakukan suatu proses selama kondisi/syarat yang ditentukan bernilai benar.'+sLineBreak+sLineBreak+'Bentuk Umum'+sLineBreak+'While <Variabel><Syarat> Do <Statement>');
end;

procedure TForm4.Panel5Click(Sender: TObject);
begin
      shape2.visible := false;
      image7.Visible := false;
      image8.Visible := false;
      image9.visible := false;
      image10.visible := false;
      
      memo1.Visible := true; memo1.Height := 433;
      panel1.visible := false;

      memo1.Text := ('Perulangan repeat until digunakan untuk mengulang suatu kondisi sampai (until) kondisi bernilai salah.'+sLineBreak+sLineBreak+'Bentuk Umum'+sLineBreak+'Repeat <Statement> Until <Ungkapan logika/Syarat>');
end;

procedure TForm4.Panel6Click(Sender: TObject);
begin
      memo1.Visible := false;
      panel1.Visible := false;
      image8.visible := false;
      image9.visible := false;
      image10.visible := false;

      shape2.Visible := true;
      image7.Visible := true;

      shape2.Height := 433;
      shape2.Left := 424;
      shape2.Top := 8;
      shape2.Width := 489;

      image7.Height := 417;
      image7.Left := 432;
      image7.top := 16;
      image7.Width := 473;
end;

procedure TForm4.Panel8Click(Sender: TObject);
begin
      memo1.Visible := false;
      panel1.Visible := false;
      image7.Visible := false;
      image9.visible := false;
      image10.visible := false;

      shape2.Visible := true;
      image8.Visible := true;

      shape2.Height := 433;
      shape2.Left := 424;
      shape2.Top := 8;
      shape2.Width := 489;

      image8.Height := 417;
      image8.Left := 432;
      image8.top := 16;
      image8.Width := 473;
end;

procedure TForm4.Panel10Click(Sender: TObject);
begin
      memo1.Visible := false;
      panel1.Visible := false;
      image7.visible := false;
      image8.Visible := false;
      image10.visible := false;

      shape2.Visible := true;
      image9.Visible := true;

      shape2.Height := 433;
      shape2.Left := 424;
      shape2.Top := 8;
      shape2.Width := 489;

      image9.Height := 417;
      image9.Left := 432;
      image9.top := 16;
      image9.Width := 473;
end;

procedure TForm4.Panel12Click(Sender: TObject);
begin
      memo1.Visible := false;
      panel1.Visible := false;
      image7.visible := false;
      image8.visible := false;
      image9.Visible := false;

      shape2.Visible := true;
      image10.Visible := true;

      shape2.Height := 433;
      shape2.Left := 424;
      shape2.Top := 8;
      shape2.Width := 489;

      image10.Height := 417;
      image10.Left := 432;
      image10.top := 16;
      image10.Width := 473;
end;

procedure TForm4.Panel2MouseMove(Sender: TObject; Shift: TShiftState; X,
  Y: Integer);
begin
      image2.Left := 240;
      image3.Left := 0;
      image4.Left := 0;
      image5.Left := 0;
      image6.Left := 0;

      panel2.left := 0;
      panel6.left := 80;
      panel7.Left := 160;

      panel4.Left := -85;
      panel8.Left := -85;
      panel9.Left := -85;

      panel3.Left := -85;
      panel10.left := -85;
      panel11.Left := -85;

      panel5.Left := -85;
      panel12.Left := -85;
      panel13.left := -85;

      panel14.Left := -245;
      
      panel2.Color := clActiveCaption;
      panel6.color := clInactiveCaption;
      panel7.color := clInactiveCaption;

      panel4.Color := clInactiveCaption;
      panel8.color := clInactiveCaption;
      panel9.Color := clInactiveCaption;

      panel3.color := clInactiveCaption;
      panel10.color := clInactiveCaption;
      panel11.Color := clInactiveCaption;

      panel5.color := clInactiveCaption;
      panel12.color := clInactiveCaption;
      panel13.color := clInactiveCaption;
end;

procedure TForm4.Panel6MouseMove(Sender: TObject; Shift: TShiftState; X,
  Y: Integer);
begin
      image2.Left := 240;
      image3.Left := 0;
      image4.Left := 0;
      image5.Left := 0;
      image6.Left := 0;

      panel2.left := 0;
      panel6.left := 80;
      panel7.Left := 160;

      panel4.Left := -85;
      panel8.Left := -85;
      panel9.Left := -85;

      panel3.Left := -85;
      panel10.left := -85;
      panel11.Left := -85;

      panel5.Left := -85;
      panel12.Left := -85;
      panel13.left := -85;

      panel14.Left := -245;
      
      panel2.Color := clinactivecaption;
      panel6.color := clactivecaption;
      panel7.color := clInactiveCaption;

      panel4.Color := clInactiveCaption;
      panel8.color := clInactiveCaption;
      panel9.Color := clInactiveCaption;

      panel3.color := clInactiveCaption;
      panel10.color := clInactiveCaption;
      panel11.Color := clInactiveCaption;

      panel5.color := clInactiveCaption;
      panel12.color := clInactiveCaption;
      panel13.color := clInactiveCaption;
end;

procedure TForm4.Panel7MouseMove(Sender: TObject; Shift: TShiftState; X,
  Y: Integer);
begin
      image2.Left := 240;
      image3.Left := 0;
      image4.Left := 0;
      image5.Left := 0;
      image6.Left := 0;

      panel2.left := 0;
      panel6.left := 80;
      panel7.Left := 160;

      panel4.Left := -85;
      panel8.Left := -85;
      panel9.Left := -85;

      panel3.Left := -85;
      panel10.left := -85;
      panel11.Left := -85;

      panel5.Left := -85;
      panel12.Left := -85;
      panel13.left := -85;

      panel14.Left := -245;
      
      panel2.Color := clinactivecaption;
      panel6.color := clInactiveCaption;
      panel7.color := clactivecaption;

      panel4.Color := clInactiveCaption;
      panel8.color := clInactiveCaption;
      panel9.Color := clInactiveCaption;

      panel3.color := clInactiveCaption;
      panel10.color := clInactiveCaption;
      panel11.Color := clInactiveCaption;

      panel5.color := clInactiveCaption;
      panel12.color := clInactiveCaption;
      panel13.color := clInactiveCaption;
end;

procedure TForm4.Panel4MouseMove(Sender: TObject; Shift: TShiftState; X,
  Y: Integer);
begin
      image2.Left := 0;
      image3.Left := 240;
      image4.Left := 0;
      image5.Left := 0;
      image6.Left := 0;

      panel2.left := -85;
      panel6.left := -85;
      panel7.Left := -85;

      panel4.Left := 0;
      panel8.Left := 80;
      panel9.Left := 160;

      panel3.Left := -85;
      panel10.left := -85;
      panel11.Left := -85;

      panel5.Left := -85;
      panel12.Left := -85;
      panel13.left := -85;

      panel14.Left := -245;
      
      panel2.Color := clinactivecaption;;
      panel6.color := clInactiveCaption;
      panel7.color := clInactiveCaption;

      panel4.Color := clactivecaption;
      panel8.color := clInactiveCaption;
      panel9.Color := clInactiveCaption;

      panel3.color := clInactiveCaption;
      panel10.color := clInactiveCaption;
      panel11.Color := clInactiveCaption;

      panel5.color := clInactiveCaption;
      panel12.color := clInactiveCaption;
      panel13.color := clInactiveCaption;
end;

procedure TForm4.Panel8MouseMove(Sender: TObject; Shift: TShiftState; X,
  Y: Integer);
begin
      image2.Left := 0;
      image3.Left := 240;
      image4.Left := 0;
      image5.Left := 0;
      image6.Left := 0;

      panel2.left := -85;
      panel6.left := -85;
      panel7.Left := -85;

      panel4.Left := 0;
      panel8.Left := 80;
      panel9.Left := 160;

      panel3.Left := -85;
      panel10.left := -85;
      panel11.Left := -85;

      panel5.Left := -85;
      panel12.Left := -85;
      panel13.left := -85;

      panel14.Left := -245;
      
      panel2.Color := clinactivecaption;
      panel6.color := clInactiveCaption;
      panel7.color := clInactiveCaption;

      panel4.Color := clInactiveCaption;
      panel8.color := clactivecaption;
      panel9.Color := clInactiveCaption;

      panel3.color := clInactiveCaption;
      panel10.color := clInactiveCaption;
      panel11.Color := clInactiveCaption;

      panel5.color := clInactiveCaption;
      panel12.color := clInactiveCaption;
      panel13.color := clInactiveCaption;
end;

procedure TForm4.Panel9MouseMove(Sender: TObject; Shift: TShiftState; X,
  Y: Integer);
begin
      image2.Left := 0;
      image3.Left := 240;
      image4.Left := 0;
      image5.Left := 0;
      image6.Left := 0;

      panel2.left := -85;
      panel6.left := -85;
      panel7.Left := -85;

      panel4.Left := 0;
      panel8.Left := 80;
      panel9.Left := 160;

      panel3.Left := -85;
      panel10.left := -85;
      panel11.Left := -85;

      panel5.Left := -85;
      panel12.Left := -85;
      panel13.left := -85;

      panel14.Left := -245;
      
      panel2.Color := clinactivecaption;
      panel6.color := clInactiveCaption;
      panel7.color := clInactiveCaption;

      panel4.Color := clInactiveCaption;
      panel8.color := clInactiveCaption;
      panel9.Color := clactivecaption;

      panel3.color := clInactiveCaption;
      panel10.color := clInactiveCaption;
      panel11.Color := clInactiveCaption;

      panel5.color := clInactiveCaption;
      panel12.color := clInactiveCaption;
      panel13.color := clInactiveCaption;
end;

procedure TForm4.Panel3MouseMove(Sender: TObject; Shift: TShiftState; X,
  Y: Integer);
begin
      image2.Left := 0;
      image3.Left := 0;
      image4.Left := 240;
      image5.Left := 0;
      image6.Left := 0;

      panel2.left := -85;
      panel6.left := -85;
      panel7.Left := -85;

      panel4.Left := -85;
      panel8.Left := -85;
      panel9.Left := -85;

      panel3.Left := 0;
      panel10.left := 80;
      panel11.Left := 160;

      panel5.Left := -85;
      panel12.Left := -85;
      panel13.left := -85;

      panel14.Left := -245;
      
      panel2.Color := clinactivecaption;
      panel6.color := clInactiveCaption;
      panel7.color := clInactiveCaption;

      panel4.Color := clInactiveCaption;
      panel8.color := clInactiveCaption;
      panel9.Color := clInactiveCaption;

      panel3.color := clactivecaption;
      panel10.color := clInactiveCaption;
      panel11.Color := clInactiveCaption;

      panel5.color := clInactiveCaption;
      panel12.color := clInactiveCaption;
      panel13.color := clInactiveCaption;
end;

procedure TForm4.Panel10MouseMove(Sender: TObject; Shift: TShiftState; X,
  Y: Integer);
begin
      image2.Left := 0;
      image3.Left := 0;
      image4.Left := 240;
      image5.Left := 0;
      image6.Left := 0;

      panel2.left := -85;
      panel6.left := -85;
      panel7.Left := -85;

      panel4.Left := -85;
      panel8.Left := -85;
      panel9.Left := -85;

      panel3.Left := 0;
      panel10.left := 80;
      panel11.Left := 160;

      panel5.Left := -85;
      panel12.Left := -85;
      panel13.left := -85;

      panel14.Left := -245;
      
      panel2.Color := clinactivecaption;
      panel6.color := clInactiveCaption;
      panel7.color := clInactiveCaption;

      panel4.Color := clInactiveCaption;
      panel8.color := clInactiveCaption;
      panel9.Color := clInactiveCaption;

      panel3.color := clInactiveCaption;
      panel10.color := clactivecaption;
      panel11.Color := clInactiveCaption;

      panel5.color := clInactiveCaption;
      panel12.color := clInactiveCaption;
      panel13.color := clInactiveCaption;
end;

procedure TForm4.Panel11MouseMove(Sender: TObject; Shift: TShiftState; X,
  Y: Integer);
begin
      image2.Left := 0;
      image3.Left := 0;
      image4.Left := 240;
      image5.Left := 0;
      image6.Left := 0;

      panel2.left := -85;
      panel6.left := -85;
      panel7.Left := -85;

      panel4.Left := -85;
      panel8.Left := -85;
      panel9.Left := -85;

      panel3.Left := 0;
      panel10.left := 80;
      panel11.Left := 160;

      panel5.Left := -85;
      panel12.Left := -85;
      panel13.left := -85;

      panel14.Left := -245;
      
      panel2.Color := clinactivecaption;
      panel6.color := clInactiveCaption;
      panel7.color := clInactiveCaption;

      panel4.Color := clInactiveCaption;
      panel8.color := clInactiveCaption;
      panel9.Color := clInactiveCaption;

      panel3.color := clInactiveCaption;
      panel10.color := clInactiveCaption;
      panel11.Color := clactivecaption;

      panel5.color := clInactiveCaption;
      panel12.color := clInactiveCaption;
      panel13.color := clInactiveCaption;
end;

procedure TForm4.Panel5MouseMove(Sender: TObject; Shift: TShiftState; X,
  Y: Integer);
begin
      image2.Left := 0;
      image3.Left := 0;
      image4.Left := 0;
      image5.Left := 240;
      image6.Left := 0;

      panel2.left := -85;
      panel6.left := -85;
      panel7.Left := -85;

      panel4.Left := -85;
      panel8.Left := -85;
      panel9.Left := -85;

      panel3.Left := -85;
      panel10.left := -85;
      panel11.Left := -85;

      panel5.Left := 0;
      panel12.Left := 80;
      panel13.left := 160;

      panel14.Left := -245;
      
      panel2.Color := clinactivecaption;
      panel6.color := clInactiveCaption;
      panel7.color := clInactiveCaption;

      panel4.Color := clInactiveCaption;
      panel8.color := clInactiveCaption;
      panel9.Color := clInactiveCaption;

      panel3.color := clInactiveCaption;
      panel10.color := clInactiveCaption;
      panel11.Color := clInactiveCaption;

      panel5.color := clactivecaption;
      panel12.color := clInactiveCaption;
      panel13.color := clInactiveCaption;
end;

procedure TForm4.Panel12MouseMove(Sender: TObject; Shift: TShiftState; X,
  Y: Integer);
begin
      image2.Left := 0;
      image3.Left := 0;
      image4.Left := 0;
      image5.Left := 240;
      image6.Left := 0;

      panel2.left := -85;
      panel6.left := -85;
      panel7.Left := -85;

      panel4.Left := -85;
      panel8.Left := -85;
      panel9.Left := -85;

      panel3.Left := -85;
      panel10.left := -85;
      panel11.Left := -85;

      panel5.Left := 0;
      panel12.Left := 80;
      panel13.left := 160;

      panel14.Left := -245;
      
      panel2.Color := clinactivecaption;
      panel6.color := clInactiveCaption;
      panel7.color := clInactiveCaption;

      panel4.Color := clInactiveCaption;
      panel8.color := clInactiveCaption;
      panel9.Color := clInactiveCaption;

      panel3.color := clInactiveCaption;
      panel10.color := clInactiveCaption;
      panel11.Color := clInactiveCaption;

      panel5.color := clInactiveCaption;
      panel12.color := clactivecaption;
      panel13.color := clInactiveCaption;
end;

procedure TForm4.Panel13MouseMove(Sender: TObject; Shift: TShiftState; X,
  Y: Integer);
begin
      image2.Left := 0;
      image3.Left := 0;
      image4.Left := 0;
      image5.Left := 240;
      image6.Left := 0;

      panel2.left := -85;
      panel6.left := -85;
      panel7.Left := -85;

      panel4.Left := -85;
      panel8.Left := -85;
      panel9.Left := -85;

      panel3.Left := -85;
      panel10.left := -85;
      panel11.Left := -85;

      panel5.Left := 0;
      panel12.Left := 80;
      panel13.left := 160;

      panel14.Left := -245;
      
      panel2.Color := clinactivecaption;
      panel6.color := clInactiveCaption;
      panel7.color := clInactiveCaption;

      panel4.Color := clInactiveCaption;
      panel8.color := clInactiveCaption;
      panel9.Color := clInactiveCaption;

      panel3.color := clInactiveCaption;
      panel10.color := clInactiveCaption;
      panel11.Color := clInactiveCaption;

      panel5.color := clInactiveCaption;
      panel12.color := clInactiveCaption;
      panel13.color := clactivecaption;
end;

procedure TForm4.Image2MouseMove(Sender: TObject; Shift: TShiftState; X,
  Y: Integer);
begin
      image2.Left := 240;
      image3.Left := 0;
      image4.Left := 0;
      image5.Left := 0;
      image6.Left := 0;

      panel2.left := 0;
      panel6.left := 80;
      panel7.Left := 160;

      panel4.Left := -85;
      panel8.Left := -85;
      panel9.Left := -85;

      panel3.Left := -85;
      panel10.left := -85;
      panel11.Left := -85;

      panel5.Left := -85;
      panel12.Left := -85;
      panel13.left := -85;

      panel14.Left := -245;
end;

procedure TForm4.Image3MouseMove(Sender: TObject; Shift: TShiftState; X,
  Y: Integer);
begin
      image2.Left := 0;
      image3.Left := 240;
      image4.Left := 0;
      image5.Left := 0;
      image6.Left := 0;

      panel2.left := -85;
      panel6.left := -85;
      panel7.Left := -85;

      panel4.Left := 0;
      panel8.Left := 80;
      panel9.Left := 160;

      panel3.Left := -85;
      panel10.left := -85;
      panel11.Left := -85;

      panel5.Left := -85;
      panel12.Left := -85;
      panel13.left := -85;

      panel14.Left := -245;
end;

procedure TForm4.Image4MouseMove(Sender: TObject; Shift: TShiftState; X,
  Y: Integer);
begin
      image2.Left := 0;
      image3.Left := 0;
      image4.Left := 240;
      image5.Left := 0;
      image6.Left := 0;

      panel2.left := -85;
      panel6.left := -85;
      panel7.Left := -85;

      panel4.Left := -85;
      panel8.Left := -85;
      panel9.Left := -85;

      panel3.Left := 0;
      panel10.left := 80;
      panel11.Left := 160;

      panel5.Left := -85;
      panel12.Left := -85;
      panel13.left := -85;

      panel14.Left := -245;
end;

procedure TForm4.Image5MouseMove(Sender: TObject; Shift: TShiftState; X,
  Y: Integer);
begin
      image2.Left := 0;
      image3.Left := 0;
      image4.Left := 0;
      image5.Left := 240;
      image6.Left := 0;

      panel2.left := -85;
      panel6.left := -85;
      panel7.Left := -85;

      panel4.Left := -85;
      panel8.Left := -85;
      panel9.Left := -85;

      panel3.Left := -85;
      panel10.left := -85;
      panel11.Left := -85;

      panel5.Left := 0;
      panel12.Left := 80;
      panel13.left := 160;

      panel14.Left := -245;
end;

procedure TForm4.Image6MouseMove(Sender: TObject; Shift: TShiftState; X,
  Y: Integer);
begin
      image2.Left := 0;
      image3.Left := 0;
      image4.Left := 0;
      image5.Left := 0;
      image6.Left := 240;

      panel2.left := -85;
      panel6.left := -85;
      panel7.Left := -85;

      panel4.Left := -85;
      panel8.Left := -85;
      panel9.Left := -85;

      panel3.Left := -85;
      panel10.left := -85;
      panel11.Left := -85;

      panel5.Left := -85;
      panel12.Left := -85;
      panel13.left := -85;

      panel14.Left := 0;
end;

procedure TForm4.Panel14MouseMove(Sender: TObject; Shift: TShiftState; X,
  Y: Integer);
begin
      image2.Left := 0;
      image3.Left := 0;
      image4.Left := 0;
      image5.Left := 0;
      image6.Left := 240;

      panel2.left := -85;
      panel6.left := -85;
      panel7.Left := -85;

      panel4.Left := -85;
      panel8.Left := -85;
      panel9.Left := -85;

      panel3.Left := -85;
      panel10.left := -85;
      panel11.Left := -85;

      panel5.Left := -85;
      panel12.Left := -85;
      panel13.left := -85;

      panel14.Left := 0;
end;

procedure TForm4.Image1MouseMove(Sender: TObject; Shift: TShiftState; X,
  Y: Integer);
begin
      image2.Left := 0;
      image3.Left := 0;
      image4.Left := 0;
      image5.Left := 0;
      image6.Left := 0;

      panel2.left := -85;
      panel6.left := -85;
      panel7.Left := -85;

      panel4.Left := -85;
      panel8.Left := -85;
      panel9.Left := -85;

      panel3.Left := -85;
      panel10.left := -85;
      panel11.Left := -85;

      panel5.Left := -85;
      panel12.Left := -85;
      panel13.left := -85;

      panel14.Left := -245;
end;

procedure TForm4.Shape1MouseMove(Sender: TObject; Shift: TShiftState; X,
  Y: Integer);
begin
      image2.Left := 0;
      image3.Left := 0;
      image4.Left := 0;
      image5.Left := 0;
      image6.Left := 0;

      panel2.left := -85;
      panel6.left := -85;
      panel7.Left := -85;

      panel4.Left := -85;
      panel8.Left := -85;
      panel9.Left := -85;

      panel3.Left := -85;
      panel10.left := -85;
      panel11.Left := -85;

      panel5.Left := -85;
      panel12.Left := -85;
      panel13.left := -85;

      panel14.Left := -245;
end;

end.
