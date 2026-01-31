const intro = document.getElementById("intro");
const gallery = document.getElementById("gallery");
const note = document.getElementById("note");
const music = document.getElementById("music");

intro.addEventListener("click", () => {
  intro.classList.add("hidden");
  gallery.classList.remove("hidden");
  music.volume = 0.4;
  music.play();
});

gallery.addEventListener("dblclick", () => {
  gallery.classList.add("hidden");
  note.classList.remove("hidden");
});
