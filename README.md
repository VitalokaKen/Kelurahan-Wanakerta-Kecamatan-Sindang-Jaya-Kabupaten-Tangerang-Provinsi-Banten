
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>KJPP Hari Utomo dan Rekan</title>
  <link rel="stylesheet" href="https://diy.magis.unwahas.ac.id/AdminLTE/plugins/fontawesome-free/css/all.min.css" />
  <link href="https://diy.magis.unwahas.ac.id/css/app.css" rel="stylesheet" />
  <link rel="stylesheet" href="https://unpkg.com/leaflet@1.7.1/dist/leaflet.css" integrity="sha512-xodZBNTC5n17Xt2atTPuE1HxjVMSvLVW9ocqUKLsCC5CXdbqCmblAshOMAS6/keqq/sMZMZ19scR4PsZChSR7A==" crossorigin="" />
  <script src="https://unpkg.com/leaflet@1.7.1/dist/leaflet.js" integrity="sha512-XQoYMqMTK8LvdxXYG3nZ448hOEQiglfqkJs1NOQV44cWnUrBc8PkAOcXy20w0vlaXaVUearIOBhiXZ5V3ynxwA==" crossorigin=""></script>
  <script src="https://cdnjs.cloudflare.com/ajax/libs/Chart.js/3.5.1/chart.js"></script>
  <!-- jQuery -->
  <script src="https://diy.magis.unwahas.ac.id/AdminLTE/plugins/jquery/jquery.min.js"></script>
  <!-- Bootstrap 4 -->
  <script src="https://diy.magis.unwahas.ac.id/AdminLTE/plugins/bootstrap/js/bootstrap.bundle.min.js"></script>
  <!-- DataTables -->
  <script src="https://diy.magis.unwahas.ac.id/AdminLTE/plugins/datatables/jquery.dataTables.min.js"></script>
  <script src="https://diy.magis.unwahas.ac.id/AdminLTE/plugins/datatables-bs4/js/dataTables.bootstrap4.min.js"></script>
  <script src="https://diy.magis.unwahas.ac.id/AdminLTE/plugins/datatables-responsive/js/dataTables.responsive.min.js"></script>
  <script src="https://diy.magis.unwahas.ac.id/AdminLTE/plugins/datatables-responsive/js/responsive.bootstrap4.min.js"></script>
</head>

<style>
  body {
    font-family: 'Montserrat', 'sans-serif';
  }
</style>
<div class="row mx-5 mt-3">
   <div class="col">
    <a href="https://hariutomo.co.id/" class="btn" style="background-color: #84C2D8; border-radius: 10px">Kembali</a>
   </div>
</div>
<div class="row mt-3 mx-5">
  <div class="col-sm-6">
    <div class="card">

      <div class="card-body">
        <h3 class="card-title">
          Peta
        </h3>
        <hr />
        <div id="map" style="width: 100%; height: 550px;"></div>
      </div>
    </div>
  </div>
  <div class="col-sm-6">
    <div class="card">
      <!-- /.card-header -->
      <div class="card-body">
        <h3 class="card-title">
      Gambar
        </h3>
        <hr />
        <div id="carouselExampleIndicators" class="carousel slide" data-ride="carousel">
          <ol class="carousel-indicators">
           <li data-target="#carouselExampleIndicators" data-slide-to="0" class="active"></li>
          </ol>
          <div class="carousel-inner">
                        <div class="carousel-item active" data-bs-interval="2000">
				<img class="d-block w-100" src="herwan1.png" alt="First slide" />
            </div>
                      </div>
          <a class="carousel-control-prev" href="herwan2.png" role="button" data-slide="prev">
            <span class="carousel-control-custom-icon" aria-hidden="true">
              <i class="fas fa-chevron-left"></i>
            </span>
            <span class="sr-only">Previous</span>
          </a>
          <a class="carousel-control-next" href="herwan3.png" role="button" data-slide="next">
            <span class="carousel-control-custom-icon" aria-hidden="true">
              <i class="fas fa-chevron-right"></i>
            </span>
            <span class="sr-only">Next</span>
          </a>
        </div>
      </div>
     
    </div>
  </div>
</div>
<div class="row mt-3 mx-5">
  <div class="col-md-6 ">
    <div class="card">
      <div class="card-header">
        <h3 class="card-title">Detail Objek</h3>
      </div>
    <!-- /.card-header -->
      <div class="card-body">
        <table class="table table-bordered">
          <tbody>
			 <tr>
              <td> Lokasi  </td>
              <td>:</td>
              <td>Lavon Swan City "Cluster Gracia", Jalan Gracia 8 Blok G-1 No. 06, Desa Wanakerta, Kecamatan Sindang Jaya, Kabupaten Tangerang, Provinsi Banten.</td>
            </tr>
			 <tr>
              <td>Basis Nilai</td>
              <td>: </td>
              <td>Nilai Pasar dan Indikasi Nilai Likuidasi</td>
            </tr>
			<tr>
              <td>Tanggal Inspeksi</td>
              <td>: </td>
              <td>22 Februari 2023</td>
            </tr>
			<tr>
              <td>Tanggal Penilaian</td>
              <td>: </td>
              <td>20 Februari 2023</td>
            </tr>
			<tr>
              <td>Tahun Penilaian</td>
              <td>: </td>
              <td>2023</td>
            </tr>
			<tr>
              <td>Titik Koordinat</td>
              <td>:</td>
              <td><a [href="https://www.google.com/maps/place/6%C2%B023'30.6%22S+106%C2%B053'53.3%22E/@-6.3918237,106.8955701,17z/data=!3m1!4b1!4m4!3m3!8m2!3d-6.391829!4d106.898145?entry=ttu](https://www.google.com/maps/place/6%C2%B011'39.6%22S+106%C2%B030'34.4%22E/@-6.194336,106.509544,17z/data=!3m1!4b1!4m4!3m3!8m2!3d-6.194336!4d106.509544?entry=ttu)">
 -6.194336, 106.509544											
                  </a></td>
            </tr>
			<tr>
              <th>Jenis Data</th>
              <th style="width: 10px">:</th>
              <th>Rumah Tinggal</th>
            </tr>
           <tr>
              <td>Luas Tanah Sertipikat</td>
              <td>:</td>
              <td> 83 m2</td>
            </tr>
			<tr>
              <td>Luas Bangunan</td>
              <td>:</td>
              <td> 90 m2</td>
            </tr>
			<tr>
              <td>Nilai Pnwrn/Transaksi</td>
              <td>:</td>
              <td> Rp 1.097.740.000.-</td>
            </tr>
			<tr>
              <td>Indikasi Nilai Pasar Tanah/m2</td>
              <td>:</td>
              <td> Rp. 8,870,000.-</td>
            </tr>
          </tbody>
        </table>
      </div>
    </div>
    <!-- /.card -->

    <div class="card">
      <div class="card-header">
        <h3 class="card-title">DATA Pembanding 1</h3>
      </div>
	   <div class="card-body">
        <table class="table table-bordered">

          <tbody>
<tr>
              <td> Lokasi  </td>
              <td>:</td>
              <td>Lavon Swan City "Cluster Gracia"</td>
            </tr>
			<tr>
              <td>Titik Koordinat</td>
              <td>:</td>
              <td><a [href="https://www.google.com/maps/place/6%C2%B023'28.8%22S+106%C2%B053'55.1%22E/@-6.3913227,106.8960741,17z/data=!3m1!4b1!4m4!3m3!8m2!3d-6.391328!4d106.898649?entry=ttu](https://www.google.com/maps/place/6%C2%B009'47.2%22S+106%C2%B034'14.9%22E/@-6.163117,106.570817,17z/data=!3m1!4b1!4m4!3m3!8m2!3d-6.163117!4d106.570817?entry=ttu)">
-6.163117, 106.570817				
                  </a></td>
            </tr>
			<tr>
              <th>Jenis Data</th>
              <th style="width: 10px">:</th>
              <th>Rumah Tinggal</th>
            </tr>
           <tr>
              <td>Nama Sumber Data</td>
              <td>:</td>
              <td>Anita</td>
            </tr>
			<tr>
              <td>No. Telp. Sumber Data </td>
              <td>: </td>
              <td>0878 8097 9116</td>
            </tr>
			<tr>
              <td>Luas Tanah Sertipikat</td>
              <td>:</td>
              <td>112 m2</td>
            </tr>
			<tr>
              <td>Luas Bangunan</td>
              <td>:</td>
              <td>140 m2</td>
            </tr>
			<tr>
              <td>Nilai Pnwrn/Transaksi</td>
              <td>:</td>
              <td> Rp. 1,650,000,000.-</td>
            </tr>
			<tr>
              <td>Indikasi Nilai Pasar Tanah/m2</td>
              <td>:</td>
              <td> Rp. 8,928,000.-</td>
            </tr>
          </tbody>
        </table>
      </div>
    </div>
  </div>
  <div class="col-md-6">
    <div class="card">
      <div class="card-header">
        <h3 class="card-title">DATA Pembanding 2</h3>
      </div>
      <!-- /.card-header -->
      <div class="card-body">
        <table class="table table-bordered">
          <tbody>
			<tr>
              <td> Lokasi  </td>
              <td>:</td>
              <td>Lavon Swan City "Cluster Gracia"</td>
            </tr>
			<tr>
              <td>Titik Koordinat</td>
              <td>:</td>
              <td><a href="https://www.google.com/maps/place/6%C2%B023'28.7%22S+106%C2%B053'56.6%22E/@-6.3912907,106.8964711,17z/data=!3m1!4b1!4m4!3m3!8m2!3d-6.391296!4d106.899046?entry=ttu">
-6.391296, 106.899046			
                  </a></td>
            </tr>
			<tr>
              <th>Jenis Data</th>
              <th style="width: 10px">:</th>
              <th>Rumah tinggal</th>
            </tr>
			<tr>
              <td>Nama Sumber Data</td>
              <td>:</td>
              <td>Pemilik</td>
            </tr>
			<tr>
              <td>No. Telp. Sumber Data </td>
              <td>: </td>
              <td> 0818 117 464 </td>
            </tr>
			<tr>
              <td>Luas Tanah Sertipikat</td>
              <td>:</td>
              <td>120 m2</td>
            </tr>
			<tr>
              <td>Luas Bangunan</td>
              <td>:</td>
              <td>200 m2</td>
            </tr>
			<tr>
              <td>Nilai Pnwrn/Transaksi</td>
              <td>:</td>
              <td> Rp. 1,800,000,000.-</td>
            </tr>
			<tr>
              <td>Indikasi Nilai Pasar Tanah/m2</td>
              <td>:</td>
              <td> Rp. 8,394,000.-</td>
            </tr>
          </tbody>
        </table>
      </div>
    </div>
    <!-- /.card -->
    <div class="card">
      <div class="card-header">
        <h3 class="card-title">DATA Pembanding 3</h3>
      </div>
      <!-- /.card-header -->
      <div class="card-body">
        <table class="table table-bordered">
         <tbody>
			<tr>
              <td> Lokasi  </td>
              <td>:</td>
              <td>Lavon Swan City "Cluster Gracia"</td>
            </tr>
			<tr>
              <td>Titik Koordinat</td>
              <td>:</td>
              <td><a href="https://www.google.com/maps/place/6%C2%B023'28.6%22S+106%C2%B054'01.9%22E/@-6.3912807,106.8979621,17z/data=!3m1!4b1!4m4!3m3!8m2!3d-6.391286!4d106.900537?entry=ttu">
-6.391286, 106.900537
                  </a></td>
            </tr>
			<tr>
              <th>Jenis Data</th>
              <th style="width: 10px">:</th>
              <th>Rumah tinggal</th>
            </tr>
           <tr>
              <td>Nama Sumber Data</td>
              <td>:</td>
              <td> Agen properti </td>
            </tr>
			<tr>
              <td>No. Telp. Sumber Data </td>
              <td>: </td>
              <td> 0812 14017813 </td>
            </tr>
			<tr>
              <td>Luas Tanah Sertipikat</td>
              <td>:</td>
              <td> 112 m2</td>
            </tr>
			<tr>
              <td>Luas Bangunan</td>
              <td>:</td>
              <td> 157 m2</td>
            </tr>
			<tr>
              <td>Nilai Pnwrn/Transaksi</td>
              <td>:</td>
              <td> Rp. 1,750,000,000.-</td>
            </tr>
			<tr>
              <td>Indikasi Nilai Pasar Tanah/m2</td>
              <td>:</td>
              <td> Rp. 9,068,000.-</td>
            </tr>
          </tbody>
        </table>
      </div>
    </div>
        
      </div>
 
  

<script>
  var peta1 = L.tileLayer('https://api.mapbox.com/styles/v1/{id}/tiles/{z}/{x}/{y}?access_token=pk.eyJ1IjoibWFwYm94IiwiYSI6ImNpejY4NXVycTA2emYycXBndHRqcmZ3N3gifQ.rJcFIG214AriISLbB6B5aw', {
            attribution: 'Map data &copy; <a href="https://www.openstreetmap.org/">OpenStreetMap</a> contributors, ' +
                '<a href="https://creativecommons.org/licenses/by-sa/2.0/">CC-BY-SA</a>, ' +
                'Imagery © <a href="https://www.mapbox.com/">Mapbox</a>',
            id: 'mapbox/streets-v11'
        });
    
    
        var map = L.map('map', {
            center: [-7.9409693,110.5509868],
            zoom: 14,
            layers: [peta1],
        });
    
        var baseMaps = {
            "Grayscale": peta1,
           
        };
    
        L.control.layers(baseMaps).addTo(map);



        var iconsekolah = L.icon({
            iconUrl: 'herwan.png',
            iconSize:     [300, 300],        
        });

		var informasi = '<table class="table table-bordered"> <tr><td colspan="2"><a href="https://www.google.com/maps/dir//-7.9409693,110.5509868" class="btn btn-sm btn-default">Rute</a></td></tr></body></table>';
         L.marker([-7.9409693,110.5509868],{icon: iconsekolah})
        // .bindPopup(L.popup({maxWidth:500}).setContent('<a href="https://www.google.com/maps/dir//-7.9409693,110.5509868" target="_blank">Rute Ke Lokasi</a>'))
		 .addTo(map);
</script>

