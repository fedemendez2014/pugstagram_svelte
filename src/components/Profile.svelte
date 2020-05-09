<script>
  export let name;
  export let nickname;
</script>

<style>
  .profile-content {
    display: flex;
    align-items: center;
  }
  .profile-avatar img {
    width: 42px;
    height: 42px;
    border-radius: 50%;
  }
  .profile-info {
    margin: 0 0 0 0.5em;
  }
  .profile-info h2 {
    font-size: 14px;
    color: black;
    margin: 0;
    padding: 0;
  }
  .profile-info span {
    font-size: 12px;
    font-weight: normal;
  }
</style>

<div class="profile">
  <div class="profile-content">
    <div class="profile-avatar">
      <img
        src="https://media-exp1.licdn.com/dms/image/C4E03AQG32kvI_Ly1-Q/profile-displayphoto-shrink_200_200/0?e=1594252800&v=beta&t=13BPKwjaPQnAsHgKHzeJq3B-A4Lsg7VFM9hmtDVDJlg"
        alt="" />
    </div>
    <div class="profile-info">
      <h2>{nickname}</h2>
      <span>{name}</span>
    </div>
  </div>
</div>
