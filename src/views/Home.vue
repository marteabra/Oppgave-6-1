<template>
  <div class="weather__container">
    <header>
      <svg
        width="37"
        height="33"
        viewBox="0 0 37 33"
        fill="none"
        xmlns="http://www.w3.org/2000/svg"
        class="logo"
      >
        <path
          d="M17.1793 29.2471L15.5699 32.7202C15.3074 33.2927 14.4035 32.9009 14.7092 32.2941L16.3231 28.8169C16.5855 28.2488 17.4851 28.6404 17.1793 29.2474L17.1793 29.2471Z"
          fill="white"
        />
        <path
          d="M20.4109 29.2471L18.8014 32.7202C18.539 33.2927 17.6395 32.9009 17.9452 32.2941L19.5546 28.8169C19.817 28.2488 20.721 28.6404 20.4109 29.2474V29.2471Z"
          fill="white"
        />
        <path
          d="M23.2212 28.541C23.5697 28.541 23.8236 28.8983 23.6473 29.2468L22.0378 32.7199C21.9561 32.8964 21.7839 32.9996 21.6032 32.9996C21.2504 32.9996 21.0008 32.6423 21.1772 32.2938L22.7866 28.8166C22.8683 28.6444 23.0405 28.541 23.2212 28.541V28.541Z"
          fill="white"
        />
        <path
          d="M26.8794 29.2471L25.2699 32.7202C25.0075 33.2927 24.1036 32.9009 24.4093 32.2941L26.0231 28.8169C26.2856 28.2488 27.1851 28.6404 26.8794 29.2474L26.8794 29.2471Z"
          fill="white"
        />
        <path
          d="M30.111 29.2471L28.5015 32.7202C28.2391 33.2968 27.3395 32.8967 27.6452 32.2941L29.2547 28.8169C29.5215 28.2444 30.4167 28.6491 30.111 29.2473V29.2471Z"
          fill="white"
        />
        <path
          d="M19.4427 4.91489L18.113 6.24465C17.6526 6.70503 16.9639 6.64495 16.555 6.26192C16.1032 5.83584 16.0988 5.10428 16.5378 4.66533L17.8675 3.33556C18.3021 2.90511 19.0037 2.90097 19.4427 3.33994C19.4986 3.284 20.144 4.21348 19.4427 4.91508L19.4427 4.91489Z"
          fill="white"
        />
        <path
          d="M9.82865 16.0349C10.7238 16.3233 10.2849 17.6874 9.38969 17.3992C5.06032 16.0091 3.65295 10.5907 6.66982 7.2642C9.22604 4.44121 13.7624 4.56596 16.1548 7.53973C16.7443 8.27562 15.6298 9.17085 15.0403 8.43909C13.2501 6.20997 9.91909 6.03342 7.89646 8.05606C5.33151 10.6166 6.44188 14.9506 9.82864 16.0349L9.82865 16.0349Z"
          fill="white"
        />
        <path
          d="M11.3908 0C12.0019 0 12.5054 0.50342 12.5054 1.11456V2.99518C12.5054 3.58055 12.0664 4.07108 11.4725 4.10974C10.8743 4.14841 10.2762 3.68804 10.2762 2.99518V1.11456C10.2762 0.585129 10.8013 0 11.3908 0Z"
          fill="white"
        />
        <path
          d="M3.33458 3.33533C3.76918 2.90073 4.48367 2.90488 4.90972 3.3397L6.23949 4.6651C6.67845 5.10407 6.67408 5.81832 6.23949 6.24024C6.29542 6.29618 5.35304 6.94602 4.66435 6.24024L3.33458 4.91484C2.90413 4.48439 2.89562 3.77447 3.33458 3.33552V3.33533Z"
          fill="white"
        />
        <path
          d="M2.99456 12.5062H1.11394C0.537316 12.5062 0.0596589 12.0672 0.00350072 11.4991C-0.0480611 10.9656 0.476997 10.2769 1.11394 10.2769H2.99456C3.68307 10.2769 4.13929 10.8707 4.10499 11.4646C4.07046 12.05 3.57556 12.506 2.99456 12.506V12.5062Z"
          fill="white"
        />
        <path
          d="M3.33453 17.8729L4.6643 16.5387C5.09889 16.1041 5.81339 16.1082 6.23943 16.5431C6.291 16.4871 6.94079 17.4166 6.23943 18.1182L4.90967 19.448C4.47508 19.8826 3.77348 19.8826 3.33453 19.4436C3.2786 19.5039 2.63317 18.5571 3.33453 17.8728V17.8729Z"
          fill="white"
        />
        <path
          d="M27.3656 13.5045C27.9594 13.3452 28.5791 13.2635 29.1946 13.2635C33.0721 13.2635 36.2182 16.4051 36.2182 20.2824C36.2182 24.2158 33.2875 27.1292 29.3844 27.3013H13.9736C11.0042 27.241 8.62866 24.8139 8.62866 21.8444C8.62866 18.974 10.8537 16.5897 13.7155 16.3962C13.5176 14.3047 14.2535 12.2475 15.7425 10.7584C19.3963 7.10903 25.7137 8.54221 27.3666 13.5041L27.3656 13.5045ZM16.7533 11.7744C15.3977 13.1344 14.834 15.1011 15.2557 16.9645C15.1781 16.9645 15.6861 17.8166 14.0893 17.8166C11.8643 17.8166 10.0613 19.6199 10.0613 21.8446C10.0613 24.0351 11.8086 25.8726 13.9991 25.8726H29.1477H29.1951H29.208H29.2338C29.2982 25.8726 29.2683 25.8726 29.2338 25.877C32.3065 25.8556 34.781 23.3551 34.781 20.2823C34.781 17.1967 32.2807 14.6964 29.1951 14.6964C28.9886 14.6964 27.1338 15.0838 27.1338 15.0838C26.725 15.2472 26.2687 15.0021 26.1785 14.5673C25.2575 10.2034 19.852 8.67566 16.7536 11.7742L16.7533 11.7744ZM29.1694 25.877H29.1479H29.1565H29.1694Z"
          fill="white"
        />
      </svg>
      <div class="city-and-date">
        <div class="city-name">OSLO, Norway</div>
        <div class="date">Today</div>
      </div>
    </header>
    <div class="weather__information">
      <div class="temperature">{{ temperature }}</div>
      <div class="wind">{{ wind }}</div>
      <div class="description">{{ description }}</div>
    </div>
  </div>
  <div class="buttons">
    <svg
      width="18"
      height="21"
      viewBox="0 0 18 21"
      fill="none"
      xmlns="http://www.w3.org/2000/svg"
      class="prev"
      @click="prev"
      v-if="activeDay > 0"
    >
      <path
        d="M-5.02681e-07 10.5L17.25 0.54071L17.25 20.4593L-5.02681e-07 10.5Z"
        fill="white"
      />
    </svg>
    <svg
      width="18"
      height="21"
      viewBox="0 0 18 21"
      fill="none"
      xmlns="http://www.w3.org/2000/svg"
      class="next-day"
      @click="next"
      v-if="activeDay < 3"
    >
      <path d="M18 10.5L0.75 20.4593L0.75 0.540708L18 10.5Z" fill="white" />
    </svg>
  </div>
</template>

<script>
export default {
  data() {
    return {
      appName: import.meta.env.VITE_APP_NAME,
      temperature: "",
      wind: "",
      description: "",
      activeDay: 0,
      forecast: [],
    };
  },
  created() {
    this.fetchData();
  },
  methods: {
    async fetchData() {
      const url = "https://goweather.herokuapp.com/weather/oslo";
      const response = await fetch(url);
      const result = await response.json();
      this.temperature = result.temperature;
      this.wind = result.wind;
      this.description = result.description;
      this.forecast = result.forecast;
    },

    prev() {
      this.activeDay = this.activeDay - 1;
    },
    next() {
      this.activeDay = this.activeDay + 1;
      const newDay = this.forecast.filter((item) => {
        return item.day == this.activeDay;
      });
      this.temperature = newDay[0].temperature;
      console.log(newDay);
    },
  },
};
</script>

<style>
body {
  height: 100vh;
  width: 100vw;
  background: #859cb1;
  color: white;
}

header {
  display: flex;
}

.weather__container {
  background-color: #9fafbe50;
  height: 50vh;
  width: 80vw;
  padding: 20px;
  border-radius: 20px;
  margin: 0 auto;
  margin-top: 10px;
}

.city-and-date {
  display: grid;
  margin-left: 30px;
  text-align: center;
}

.weather__information {
  text-align: center;
}

.temperature {
  padding: 30px;
  font-size: 3rem;
}

.buttons {
  display: flex;
  justify-content: space-between;
  padding: 20px;
}
</style>