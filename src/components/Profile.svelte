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
        src="https://instagram.fmvd2-1.fna.fbcdn.net/v/t51.2885-19/s150x150/56526841_402805890553414_7747271917014351872_n.jpg?_nc_ht=instagram.fmvd2-1.fna.fbcdn.net&_nc_ohc=mWlSFv3dNrgAX_52Srm&edm=ABfd0MgBAAAA&ccb=7-4&oh=089879d26f4d9571b80a8f0ace9a5274&oe=611A9D63&_nc_sid=7bff83"
        alt="" />
    </div>
    <div class="profile-info">
      <h2>{nickname}</h2>
      <span>{name}</span>
    </div>
  </div>
</div>
