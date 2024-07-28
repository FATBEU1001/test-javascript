# Bài test javascript CONEX

**1.Tổng quan**

-   Học viên sẽ dựa vào dữ liệu mẫu để tạo ra một ứng dụng tìm kiếm thông tin sản phẩm
-   Học viên sử dụng javascript thuần để thực hiện

**2.Yêu cầu**

-   Học viên xây dựng giao diện theo mẫu figma: 
-   Người dùng nhập tên sản phẩm cần tìm kiểm vào khung input và nhấn enter thì chương trình sẽ tự động show các sản phẩm thỏa yêu cầu tìm kiếm

**3.Dữ liệu mẫu**

```js
[
    {
        id: 1,
        name: "Dry-EX T-shirt Round Neck short Sleeve (Texture)",
        price: "299",
        img: "https://image.uniqlo.com/UQ/ST3/vn/imagesgoods/461994/item/vngoods_60_461994.jpg",
    },
    {
        id: 2,
        name: "EZY Super Stretch Jeans",
        price: "299",
        img: "https://image.uniqlo.com/UQ/ST3/vn/imagesgoods/455476/item/vngoods_68_455476.jpg",
    },

    {
        id: 3,
        name: "Shirt Cotton with long collar",
        price: "499",
        img: "https://image.uniqlo.com/UQ/ST3/vn/imagesgoods/461914/item/vngoods_32_461914.jpg",
    },

    {
        id: 4,
        name: "Slim Fit Jeans",
        price: "299",
        img: "https://image.uniqlo.com/UQ/ST3/vn/imagesgoods/461578/item/vngoods_64_461578.jpg",
    },
    {
        id: 5,
        name: "Dry Shirt pique long hand",
        price: "899",
        img: "https://image.uniqlo.com/UQ/ST3/vn/imagesgoods/459713/item/vngoods_55_459713.jpg",
    },
    {
        id: 6,
        name: "Short Sleeve Pique Fabric Dry Polo Shirt",
        price: "299",
        img: "https://image.uniqlo.com/UQ/ST3/vn/imagesgoods/457513/item/vngoods_00_457513.jpg",
    },

    {
        id: 7,
        name: "Smart Pants Ankle Length (Pattern)",
        price: "499",
        img: "https://image.uniqlo.com/UQ/ST3/vn/imagesgoods/461597/item/vngoods_69_461597.jpg",
    },
    {
        id: 8,
        name: "Cotton T-shirt with short collar",
        price: "399",
        img: "https://image.uniqlo.com/UQ/ST3/vn/imagesgoods/456773/item/vngoods_03_456773.jpg",
    },
    {
        id: 9,
        name: "Slim Fit Stretch Shorts",
        price: "400",
        img: "https://image.uniqlo.com/UQ/ST3/vn/imagesgoods/455533/item/vngoods_05_455533.jpg",
    },
    {
        id: 10,
        name: "AIRism Boxer Briefs Seamless",
        price: "59",
        img: "https://image.uniqlo.com/UQ/ST3/AsianCommon/imagesgoods/456710/item/goods_03_456710.jpg",
    },
    {
        id: 11,
        name: "Jogger Dry-EX Super Stretchy Pants",
        price: "599",
        img: "https://image.uniqlo.com/UQ/ST3/vn/imagesgoods/455408/item/vngoods_03_455408.jpg",
    },
    {
        id: 12,
        name: "AIRism Printed Boxer Briefs Panties",
        price: "400",
        img: "https://image.uniqlo.com/UQ/ST3/AsianCommon/imagesgoods/456679/item/goods_69_456679.jpg",
    },
    {
        id: 13,
        name: "AIRism Deodorant Mesh Cloth Tank Top",
        price: "200",
        img: "https://image.uniqlo.com/UQ/ST3/vn/imagesgoods/454318/item/vngoods_09_454318.jpg",
    },
    {
        id: 14,
        name: "Cotton Relaxed Ankle Pants (Denim)",
        price: "599",
        img: "https://image.uniqlo.com/UQ/ST3/vn/imagesgoods/455895/item/vngoods_67_455895.jpg",
    },
    {
        id: 15,
        name: "Stretchy Dry Sweater Jacket With Zipper Hood Cotton Long Sleeve",
        price: "599",
        img: "https://image.uniqlo.com/UQ/ST3/vn/imagesgoods/460325/item/vngoods_19_460325.jpg",
    },
    {
        id: 16,
        name: "HEATTECH Feather Panties",
        price: "599",
        img: "https://image.uniqlo.com/UQ/ST3/vn/imagesgoods/460335/item/vngoods_03_460335.jpg",
    },
];
```
