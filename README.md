65011075  สรพัศ พิศิลป์





กรณีใช้ localhost


ใน index.js ลบ comment นี้

/*
const PORT = process.env.PORT || 4001;
app.listen(PORT, () => {
  console.log(`Server is running on port ${PORT}`);
});
*/




และใน script.js เปลี่ยน http ด้านเป็นตามนี้

const API_HOST = window.API_HOST || "http://localhost:4001";
