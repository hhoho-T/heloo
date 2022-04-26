# heloo
bài test
using System;
namespace cong
{
    class Program
    {
        static void Main(string[] args)
        {
            /*CanBo c = new CanBo("ba tri", 19, "nam", "cau giay");
            Congnhan cn = new Congnhan("kds", 145, "nu", "cau giay", 1);
            Kysu ks = new Kysu("abc", 13, "khac", "cau giau", 2);
            Nhanvien nv = new Nhanvien("abc", 13, "khac", "cau giau", 2);

            c.In();
            cn.In();
            ks.In();
            nv.In();*/


            //Khai báo 1 mảng cán bộ
            //Khai báo 1 mảng cán bộ


            /*CanBo[] a = new CanBo[3];
            // Nhập thông tin cho các cán bộ: duyệt mảng
            Console.WriteLine("Nhap 1 neu muon nhap moi CAN BO");
            Console.WriteLine("Nhap 2 neu muon nhap moi CONG NHAN");
            Console.WriteLine("Nhap 3 neu muon nhap moi KY SU");
            Console.WriteLine("-----------------------------------");
            for (int i = 0; i < a.Length; i++)
            {
                byte t = 0;//Lưu loại đối tượng
                Console.Write("Nhap loai doi tuong: ");
                t = byte.Parse(Console.ReadLine());
                switch (t)
                {
                    case 1:
                        a[i] = new CanBo();
                        a[i].NhapTT();
                        break;
                    case 2:
                        a[i] = new CongNhan();
                        a[i].NhapTT();
                        break;
                    case 3:
                        a[i] = new KySu();
                        a[i].NhapTT();
                        break;
                    default:
                        a[i] = new CanBo();
                        a[i].NhapTT();
                        break;
                }

            }
            //In TT của mảng cán bộ
            for (int i = 0; i < a.Length; i++)
            {
                a[i].InTT();
            }*/
            Animal a = new Animal();
            IAnimal b = new Animal();
            a.Keu();
            b.Keu();
        }
    }

}

