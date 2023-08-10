unit Calculadora;

interface

uses
  Winapi.Windows, Winapi.Messages, System.SysUtils, System.Variants,System.StrUtils ,System.Classes, Vcl.Graphics,
  Vcl.Controls, Vcl.Forms, Vcl.Dialogs, Vcl.ExtCtrls, Vcl.WinXPanels,
  Vcl.StdCtrls;

type
  TForm1 = class(TForm)
    buttonMaisMenos: TButton;
    button0: TButton;
    buttonVirgula: TButton;
    button1: TButton;
    button4: TButton;
    button7: TButton;
    button2: TButton;
    button5: TButton;
    button8: TButton;
    button3: TButton;
    button6: TButton;
    button9: TButton;
    buttonIgual: TButton;
    buttonMais: TButton;
    buttonMenos: TButton;
    buttonMulti: TButton;
    buttonDivisao: TButton;
    resultB: TEdit;
    resultA: TEdit;
    buttonApagar: TButton;
    buttonC: TButton;
    buttonCE: TButton;
    buttonPorcet: TButton;
    buttonX2: TButton;
    procedure button1Click(Sender: TObject);
    procedure buttonMaisMenosClick(Sender: TObject);
    procedure button2Click(Sender: TObject);
    procedure button3Click(Sender: TObject);
    procedure button4Click(Sender: TObject);
    procedure button5Click(Sender: TObject);
    procedure button6Click(Sender: TObject);
    procedure button7Click(Sender: TObject);
    procedure button8Click(Sender: TObject);
    procedure button9Click(Sender: TObject);
    procedure button0Click(Sender: TObject);
    procedure buttonVirgulaClick(Sender: TObject);
    procedure buttonMaisClick(Sender: TObject);

  private
    { Private declarations }
  public
    { Public declarations }
    valorRB:string;
    valorRA:string;
    result:Double;
    valorX:Double;
    ValorY:Double;
  end;

var
  Form1: TForm1;


implementation

{$R *.dfm}



procedure TForm1.button0Click(Sender: TObject);
begin
  var valor0:string:='0';

  valorRB:= valorRB+valor0;
  resultB.Text := valorRB;
end;

procedure TForm1.button1Click(Sender: TObject);
begin
  var valor1:string:='1';

  valorRB:= valorRB+valor1;
  resultB.Text := valorRB;
end;

procedure TForm1.button2Click(Sender: TObject);
begin
  var valor2:string:='2';

  valorRB:=valorRB+valor2;
  resultB.Text := valorRB;
end;

procedure TForm1.button3Click(Sender: TObject);
begin
  var valor3:string:='3';

  valorRB:=valorRB+valor3;
  resultB.Text:= valorRB;
end;

procedure TForm1.button4Click(Sender: TObject);
begin
  var valor4:string:='4';

  valorRB:=valorRB+valor4;
  resultB.Text := valorRB;
end;

procedure TForm1.button5Click(Sender: TObject);
begin
  var valor5:string:='5';

  valorRB:= valorRB+valor5;
  resultB.Text := valorRB;
end;

procedure TForm1.button6Click(Sender: TObject);
begin
  var valor6:string:='6';

  valorRB:= valorRB+valor6;
  resultB.text := valorRB;
end;

procedure TForm1.button7Click(Sender: TObject);
begin
  var valor7:string:='7';

  valorRB:= valorRB+valor7;
  resultB.Text := valorRB;
end;

procedure TForm1.button8Click(Sender: TObject);
begin
  var valor8:string:='8';

  valorRB:= valorRB+valor8;
  resultB.Text := valorRB;
end;

procedure TForm1.button9Click(Sender: TObject);
begin
  var valor9:string:='9';

  valorRB:= valorRB+valor9;
  resultB.Text := valorRB;
end;

procedure TForm1.buttonMaisClick(Sender: TObject);
begin
    var valorMais:string:='+';

    if AnsiContainsStr(valorRA, '+') then begin
         valorY:= StrToFloat(valorRB);
         result:= valorX + ValorY;
         resultB.Text := result.ToString;
  //       valorRB:=FloatToStr(valorRB);
    //     resultA:=valorRA + valorRB;
    end
      else
          valorX:= StrToFloat(valorRB);
          valorRA:= valorRB+valorMais;
          resultA.Text:=valorRA;
          valorRB:='';
          resultB.Text:='0';

end;

procedure TForm1.buttonMaisMenosClick(Sender: TObject);
begin
  var valorMM:Double:= -1;
if (valorRB <> '') then begin
   valorMM:=ValorMM*StrToFloat(valorRB);
   valorRB:=FloatToStr(valorMM);
   resultB.Text:=valorRB;
end
  else
   valorRB:= valorRB;
   resultB.Text:=valorRB;
end;

procedure TForm1.buttonVirgulaClick(Sender: TObject);
begin
  var valorPonto:string:=',';

  if  AnsiContainsStr(valorRB, ',') then begin
      valorRB:= valorRB;
      resultB.Text:=valorRB;
  end
    else
      valorRB:=valorRB+valorPonto;
      resultB.Text := valorRB;

end;

end.
