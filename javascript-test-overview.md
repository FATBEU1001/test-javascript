# Bài test javascript CONEX

**1.Tổng quan**

-   Học viên sẽ dựa vào dữ liệu mẫu để tạo ra một ứng dụng tìm kiếm thông tin sản phẩm
-   Học viên sử dụng javascript thuần để thực hiện

**2.Yêu cầu**
-   Học viên xây dựng giao diện tùy ý theo HTML (tên class theo chuẩn BEM),SCSS và thực hiện responsive
-   Người dùng nhập tên sản phẩm cần tìm kiểm vào khung input và nhấn enter thì chương trình sẽ tự động show các sản phẩm thỏa yêu cầu tìm kiếm
-  Người dùng click vào 1 sản phẩm sẽ chuyển sang trang detail hoặc mở popup để hiển thị thông tin chi tiết của sản phẩm đó

**3.Dữ liệu mẫu**

```js
[
    {
        id: 1,
        name: "Dry-EX T-shirt Round Neck short Sleeve (Texture)",
        price: "299",
        img: "https://image.uniqlo.com/UQ/ST3/vn/imagesgoods/465185/item/vngoods_33_465185.jpg",
    },
    {
        id: 2,
        name: "EZY Super Stretch Jeans",
        price: "299",
        img: "https://image.uniqlo.com/UQ/ST3/vn/imagesgoods/467039/item/vngoods_30_467039.jpg",
    },

    {
        id: 3,
        name: "Shirt Cotton with long collar",
        price: "499",
        img: "https://image.uniqlo.com/UQ/ST3/vn/imagesgoods/473162/item/vngoods_68_473162.jpg",
    },

    {
        id: 4,
        name: "Slim Fit Jeans",
        price: "299",
        img: "https://image.uniqlo.com/UQ/ST3/vn/imagesgoods/465195/item/vngoods_00_465195.jpg",
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
        img: "https://image.uniqlo.com/UQ/ST3/vn/imagesgoods/471585/item/vngoods_09_471585.jpg",
    },

    {
        id: 7,
        name: "Smart Pants Ankle Length (Pattern)",
        price: "499",
        img: "https://image.uniqlo.com/UQ/ST3/vn/imagesgoods/465492/item/vngoods_03_465492.jpg",
    },
    {
        id: 8,
        name: "Cotton T-shirt with short collar",
        price: "399",
        img: "https://image.uniqlo.com/UQ/ST3/vn/imagesgoods/465187/item/vngoods_59_465187.jpg",
    },
    {
        id: 9,
        name: "Slim Fit Stretch Shorts",
        price: "400",
        img: "https://image.uniqlo.com/UQ/ST3/vn/imagesgoods/468738/item/vngoods_01_468738.jpg",
    },
    {
        id: 10,
        name: "AIRism Boxer Briefs Seamless",
        price: "59",
        img: "https://image.uniqlo.com/UQ/ST3/vn/imagesgoods/467134/item/vngoods_36_467134.jpg",
    },
    {
        id: 11,
        name: "Jogger Dry-EX Super Stretchy Pants",
        price: "599",
        img: "https://image.uniqlo.com/UQ/ST3/vn/imagesgoods/469977/item/vngoods_00_469977.jpg",
    },
    {
        id: 12,
        name: "AIRism Printed Boxer Briefs Panties",
        price: "400",
        img: "https://image.uniqlo.com/UQ/ST3/vn/imagesgoods/465193/item/vngoods_52_465193.jpg",
    },
    {
        id: 13,
        name: "AIRism Deodorant Mesh Cloth Tank Top",
        price: "200",
        img: "https://image.uniqlo.com/UQ/ST3/vn/imagesgoods/472075/item/vngoods_32_472075.jpg",
    },
    {
        id: 14,
        name: "Cotton Relaxed Ankle Pants (Denim)",
        price: "599",
        img: "https://image.uniqlo.com/UQ/ST3/vn/imagesgoods/469940/item/vngoods_00_469940.jpg",
    },
    {
        id: 15,
        name: "Stretchy Dry Sweater Jacket With Zipper Hood Cotton Long Sleeve",
        price: "599",
        img: "https://image.uniqlo.com/UQ/ST3/vn/imagesgoods/469922/item/vngoods_68_469922.jpg",
    },
    {
        id: 16,
        name: "HEATTECH Feather Panties",
        price: "599",
        img: "https://image.uniqlo.com/UQ/ST3/vn/imagesgoods/473057/item/vngoods_00_473057.jpg",
    },
];
```
