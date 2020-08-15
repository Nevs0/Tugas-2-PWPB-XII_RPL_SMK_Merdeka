# Tugas-2-PWPB-XII_RPL_SMK_Merdeka
Nama : Arif Saputra
Nis :181020300

----------------------------------------------------------------------
<php?
$buah = 'Mangga';
$keterangan = 'Masuk kedalam Katagori';
swicth ($buah)
{
    case 'Strawberry' :
     $Katagori = $keterangan.' soft fruits';
     break;
    case 'Jambu' :
     $Katagori = $keterangan.' hard fruits';
     break;
    case 'Nanas' :
     $Katagori = $keterangan.' citrus fruits';
     break;
    case 'Pisanh' :
     $Katagori = $keterangan.' Tropical fruits';
     break;
   default:
     $Katagori = 'belum dimasukan kedalam Katagori';
}
echo 'buah'.$buah.$Katagori;
?>
