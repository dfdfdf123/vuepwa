<template>
  <div id="app">
    <main>
      <template>
        <Panel class="calculator-panel" headline="Income Tax Calculator">
          <template>
            <span>content goes here.<span/>
          </template>
        </Panel>
      </template>
    </main>
  </div>
</template>

<script>
import Panel from './components/Panel.vue';
import InputForm from './components/InputForm.vue';
import Result from './components/Result.vue';
import { calcTaxes } from './calc.js';

export default {
  name: 'app',
  components: {
    Panel,
    InputForm,
    Result
  }
}
</script>

<style lang="scss" src="../assets/styles/InputForm.scss"/>
