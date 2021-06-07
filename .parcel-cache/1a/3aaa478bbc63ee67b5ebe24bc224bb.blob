const featureShare = document.querySelector(".feature-share");
const share = document.querySelector(".share");
const card = document.querySelector(".card");
const shareIcon = document.querySelector(".share-icon");
featureShare.addEventListener("click", function (e) {
  share?.classList.toggle("hidden");
});
card.addEventListener("click", function (e) {
  if (e.target == featureShare || e.target == shareIcon) return;
  share.classList.add("hidden");
});
