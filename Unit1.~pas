unit Unit1;

interface

uses
  Windows, Messages, SysUtils, Variants, Classes, Graphics, Controls, Forms,
  Dialogs, StdCtrls, XPMan;

type
  TForm1 = class(TForm)
    Label1: TLabel;
    Label2: TLabel;
    Edit1: TEdit;
    Edit2: TEdit;
    Button1: TButton;
    Edit3: TEdit;
    Button2: TButton;
    Button3: TButton;
    Button4: TButton;
    Button5: TButton;
    Label3: TLabel;
    XPManifest1: TXPManifest;
    Label4: TLabel;
    procedure Button1Click(Sender: TObject);
    procedure Button2Click(Sender: TObject);
    procedure Button3Click(Sender: TObject);
    procedure Button4Click(Sender: TObject);
    procedure Button5Click(Sender: TObject);
  private
    { Private declarations }
  public
    { Public declarations }
  end;

var
  Form1: TForm1;

implementation

{$R *.dfm}

procedure TForm1.Button1Click(Sender: TObject);
var Angka1, Angka2, hasil :integer;
begin
Angka1:=(StrToInt(Edit1.Text));
Angka2:=(StrToInt(Edit2.Text));

hasil:=Angka1+Angka2;

Edit3.Text:=IntToStr(hasil);
end;
procedure TForm1.Button2Click(Sender: TObject);
var Angka1, Angka2, hasil :integer;
begin
Angka1:=(StrToInt(Edit1.Text));
Angka2:=(StrToInt(Edit2.Text));

hasil:=Angka1-Angka2;

Edit3.Text:=IntToStr(hasil);
end;

procedure TForm1.Button3Click(Sender: TObject);
var Angka1, Angka2, hasil :integer;
begin
Angka1:=(StrToInt(Edit1.Text));
Angka2:=(StrToInt(Edit2.Text));

hasil:=Angka1*Angka2;

Edit3.Text:=IntToStr(hasil);

end;

procedure TForm1.Button4Click(Sender: TObject);
var Angka1, Angka2, hasil :Real;
begin
Angka1:=(StrToFloat(Edit1.Text));
Angka2:=(StrToFloat(Edit2.Text));

hasil:=Angka1/Angka2;

Edit3.Text:=FloatToStr(hasil);

end;

procedure TForm1.Button5Click(Sender: TObject);
begin
Edit1.Text:=' ';
Edit2.Text:=' ';
Edit3.Text:=' ';
end;

end.
