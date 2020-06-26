# Date-Calculation-in-Lavarel
#Calculate the Number of days between two dates 

$ddto = strtotime("2020-05-25"); 
$ddfrom = strtotime("2010-06-23");

$date_difference = $ddto- $ddfrom;

$result =  ( $date_difference / (60 * 60 * 24) );

print_r($result);
