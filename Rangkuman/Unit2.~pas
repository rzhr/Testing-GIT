unit Unit2;

interface

uses
  Windows, Messages, SysUtils, Variants, Classes, Graphics, Controls, Forms,
  Dialogs, ExtCtrls, jpeg;

type
  TForm2 = class(TForm)
    Image1: TImage;
    Image2: TImage;
    Image3: TImage;
    Panel1: TPanel;
    Panel2: TPanel;
    Panel3: TPanel;
    Image4: TImage;
    GarisTepi: TShape;
    procedure Image2MouseMove(Sender: TObject; Shift: TShiftState; X,
      Y: Integer);
    procedure Panel1Click(Sender: TObject);
    procedure Image3MouseMove(Sender: TObject; Shift: TShiftState; X,
      Y: Integer);
    procedure Panel2Click(Sender: TObject);
    procedure Panel3Click(Sender: TObject);
    procedure Image4MouseMove(Sender: TObject; Shift: TShiftState; X,
      Y: Integer);
    procedure Image1MouseMove(Sender: TObject; Shift: TShiftState; X,
      Y: Integer);
    procedure GarisTepiMouseMove(Sender: TObject; Shift: TShiftState; X,
      Y: Integer);
  private
    { Private declarations }
  public
    { Public declarations }
  end;

var
  Form2: TForm2;

implementation

uses Unit3, Unit4, Unit1;

{$R *.dfm}

procedure TForm2.Image2MouseMove(Sender: TObject; Shift: TShiftState; X,
  Y: Integer);
begin
      panel1.Left := 0;
      image2.Left := 312;
      image3.Left := 0; panel2.Left := -315;
      image4.Left := 0; panel3.Left := -315;
end;

procedure TForm2.Panel1Click(Sender: TObject);
begin
      form2.hide;
      form3.show;
end;

procedure TForm2.Image3MouseMove(Sender: TObject; Shift: TShiftState; X,
  Y: Integer);
begin
      panel2.Left := 0;
      image3.Left := 312;
      image2.Left := 0; panel1.Left := -315;
      image4.Left := 0; panel3.Left := -315;
end;

procedure TForm2.Panel2Click(Sender: TObject);
begin
      form2.Hide;
      form4.Show;
end;

procedure TForm2.Panel3Click(Sender: TObject);
begin
      form1.Close;
      form2.Close;
      form3.Close;
      form4.Close;
end;

procedure TForm2.Image4MouseMove(Sender: TObject; Shift: TShiftState; X,
  Y: Integer);
begin
      panel3.Left := 0;
      image4.Left := 312;
      image2.Left := 0; panel1.Left := -315;
      image3.Left := 0; panel2.Left := -315;
end;

procedure TForm2.Image1MouseMove(Sender: TObject; Shift: TShiftState; X,
  Y: Integer);
begin
      image2.Left := 0; panel1.Left := -315;
      image3.left := 0; panel2.left := -315;
      image4.left := 0; panel3.left := -315;
end;

procedure TForm2.GarisTepiMouseMove(Sender: TObject; Shift: TShiftState; X,
  Y: Integer);
begin
      image2.Left := 0; panel1.Left := -315;
      image3.left := 0; panel2.left := -315;
      image4.left := 0; panel3.left := -315;
end;

end.
