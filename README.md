# Whois-Domain-Sorgula
.NET ile Yazdığınız Projelerinizde Domain Sorgulama İşlemlerinizi Yapmak İçin Kullanabileceğiniz Dll Kütüphanesi
whois.internic.com üzerinden sorgulama yapar.

            var a = plugin.whois.GetDomainResult("xxxxxxxxx", "com");
            MessageBox.Show(a.ToString());
