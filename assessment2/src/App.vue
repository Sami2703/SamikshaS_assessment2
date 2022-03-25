<template>
  <div>
    <header-bar></header-bar>
    <b-container>
      <b-row class="mt-5">
        <router-view />
      </b-row>
    </b-container>
    <DataTable/>
    <!-- <customer-overview/>
    <CreateCustomerForm/>
    
    <EditCustomerForm/>
    <HomeCustomer/> -->
  </div>
</template>

<script>
import HeaderBar from "@/components/HeaderBar.vue";
// import CustomerOverview from "@/components/CustomerOverview.vue";
// import CreateCustomerForm from "@/components/CreateCustomerForm.vue";
import DataTable from "@/components/DataTable.vue";
// import EditCustomerForm from "@/components/EditCustomerForm.vue";
// import HomeCustomer from "@/components/HomeCustomer.vue";



export default {
  components: {
    HeaderBar,
    DataTable

  },
};
</script>

