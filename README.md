# DFD E-Commerce Payment System

Data Flow Diagram untuk sistem pembayaran e-commerce yang menggambarkan aliran data dari proses pemesanan hingga konfirmasi pembayaran.

## Komponen Utama

### External Entity
- **Customer** - Pengguna yang melakukan pemesanan
- **Payment Gateway** - Gateway pembayaran pihak ketiga
- **Bank** - Institusi keuangan pemroses transaksi

### Process
- Process Order
- Show Payment Options
- Select Payment Method
- Process Payment
- Process Payment Result
- Confirm Order

### Data Store
- **Order Database** - Penyimpanan data pesanan
- **Transaction Database** - Penyimpanan data transaksi

### Data Flow
15 aliran data yang menghubungkan komponen sistem dari order request hingga konfirmasi order.

## Trust Boundary

**Customer Boundary**  
Aktor eksternal yang tidak dikontrol oleh sistem.

**E-commerce Application Boundary**  
Mencakup semua proses internal aplikasi, Order Database, dan Transaction Database yang berada dalam kontrol penuh aplikasi.

**External Payment Network**  
Sistem pihak ketiga (Payment Gateway & Bank) di luar kendali e-commerce.

## Manfaat

- Memfasilitasi komunikasi antara stakeholder
- Mendokumentasikan proses bisnis
- Mengidentifikasi requirement yang missing
- Blueprint untuk implementasi sistem
- Analisis keamanan dan identifikasi vulnerability
