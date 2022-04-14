formik. bize form yapısı hazırlıyor. kendi state var . validation yazmak zorunda kalmıyorsun . handleChange vb. yapıları kendi içinde veriyor.Normal form da da kullanabiliriz . material ui da kullanabiliriz.vb.

1- formik.org  dan formik ile ilgili tüm bilgilere ulaşabiliriz . esas mantık formumuzu Formik ile sarmallamamız gerek ve işlemlere öyle başlamalıyız.

2-Formik import etmeliyiz.Formumuzu Formik ile sarmallıyoruz.Formu {} içine alıyorum ve arrow func. ile içine değerler göndermeliyim.Formik yapısından aldığım değerleri formuniçine gönderecem.

3- Formik initialValues alır . kendimiz oluşturup formun içine gönderecez.ve {} içinde initialvalue ları Alıp forma göndermeliyim (values) şeklinde alıyorum .formun içine de value = values.username şeklinde gönderiyorum.

4-Formikden handceChange geliyor otomatik olarak. formun içine onChange={handleChange } yazıp arrow func. içine de {handleChange} yazmamız gerek.

5-arrow içine onSubmit={onSubmit} ve bunu formun props una daa ekliyorum onSubmit={onSubmit} const handleSubmit yapıyoruz ve yukarıda fonk. oluşturuyoruz.

6-