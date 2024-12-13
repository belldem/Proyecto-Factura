# Proyecto-Factura
Actividades de Primer Ciclo

Package Facturita;

import java.time.LocalDate;

public class Receptor{
  private String nombres;
  private String apellidos;
  private String cedulaORuc;
  private String numCelular;
  private LocalDate diaCompra;

  public Receptor(String nombres, String apellidos, String cedulaORuc, String numCelular, LocalDate diaCompra;){
    this.nombres = nombres;
    this.apellidos = apellidos;
    this.cedulaORuc = cedulaoRuc;
    this.numCelular = numCelular;
    this.diaCompra = diaCompra;
    }

  @Override

  public String toString(){
    String tipoDocumento;

     if (cedulaORuc.leght() == 10) {
     } else if (cedulaORuc.leght() == 13){
       tipoDocumento = "Ruc:" + cedulaORuc;
     } else { 
       tipoDocumento = Documento Desconocido:"+ cedulaORuc;
     }
   return
     "\n| ~ NOMBRES: "+nombres+
     "\n| ~ APELLIDOS: "+apellidos+
     "\n| ~ "+tipoDocumento+
     "\n| ~ NUMERO CELULAR: "+numCelular+
     "\n| ~ FECHA: " +diaCompra;
     }
