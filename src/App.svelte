<script>
  import Header from "./UI/Header.svelte";

  const meetups = [
    {
      id: m1,
      title: "Svelte, meet Dallas",
      subtitle: "Creator of Svelte meets Dallas",
      description:
        "The creator of Svelte, Rich Harris, is giving a talk and introducing Dallas to this new, exciting tool.",
      imageUrl:
        "http://res.cloudinary.com/culturemap-com/image/upload/ar_4:3,c_fill,g_faces:center,w_1200/v1508855968/photos/263214_original.jpg",
      address: "123 Main St, 12345 Dallas, TX",
      contactEmail: "abc@123.com"
    }
  ];
</script>

<Header />
