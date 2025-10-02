# Nhom-14
git checkout -b feature-25161150
echo "Thông tin cá nhân
- Họ tên: Huỳnh Tuấn Kiệt
- MSSV: 25161150
- Giới thiệu: Thân thiện, hòa đồng, vui vẻ." > members/25161150.md
git add members/2012345.md
git commit -m "feat: add profile for MSSV 25161150"
echo "Email: htkiet04.2007@gmail.com >> members/25161150.md
git add members/25161150.md
git commit -m "docs: update profile with email"
sed -i 's/lập trình/lập trình & AI/' members/25161150.md
git add members/25161150.md
git commit -m "fix: correct wording in profile"
