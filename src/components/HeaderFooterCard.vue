<template>
<div class="card text-center">
  <div class="card-header">
    <slot name="header"></slot>
  </div>
  <div class="card-body">
    <slot name="body"></slot>
  </div>
  <div class="card-footer text-muted">
    <slot name="footer"></slot>
  </div>
</div>
</template>