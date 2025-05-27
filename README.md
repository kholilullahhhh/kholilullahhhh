```json

type UserProfile = {
  username: string;
  name: string;
  pronouns: string;
  city: string;
  about: string;
  interests: string[];
  learning: string[];
  contact: {
    email: string;
    instagram: string;
  };
  message: string;
};

function getUserProfile(): UserProfile {
  return {
    username: "@kholilullahhhh",
    name: "Muhammad Kholilullah/Luluuu",
    pronouns: "he/him",
    city: "Makassar, South Sulawesi, Indonesia",
    about: "A Tech Enthusiast",
    interests: [
      "Web Development 🌐",
      "Mobile App Development 📱"
    ],
    learning: [
      "Php (Laravel) 💰",
      "JavaScript (React, Node.js) ⚛️",
      "React Native for Mobile Development 📱"
    ],
    contact: {
      email: "muhammadkholil045@gmail.com",
      instagram: "@kholilullahhh_"
    },
    message: "Double Chesseburger, cola 1"
  };
}
