<template>
  <div className="main">
    <div className="left-bar">
      <div className="top">
        <h1>.portfolio</h1>
      </div>
      <div className="middle">
        <ul>
          <li>
            <router-link to="/"> Home </router-link>
          </li>
          <li>
            <router-link to="/skill"> Skill </router-link>
          </li>
          <li>
            <router-link to="/project"> Projects </router-link>
          </li>
          <li>
            <router-link to="/work"> Work </router-link>
          </li>
        </ul>
      </div>
      <div className="bottom">
        <ul>
          <li>
            <a href="/setting" className="text-link"> Setting </a>
          </li>
          <li>
            <a href="/logout" className="text-link"> Log out </a>
          </li>
        </ul>
      </div>
    </div>
    <div className="main-container">
      <div className="navbar">
        <div className="search-container">
          <input type="text" placeholder="  Search" />
        </div>
        <div className="profile-container">
          <div className="name-container">
            <p>Yejin</p>
          </div>
          <div className="img-container">
            <img
              src="https://gunbam27.github.io/Portfolio_ver2/img/profile.jpg"
              alt="프로필이미지"
            />
          </div>
        </div>
      </div>
      <div className="display-container">
        <router-view></router-view>
      </div>
    </div>
  </div>
</template>

<script>

export default {
};
</script>

<style>

</style>