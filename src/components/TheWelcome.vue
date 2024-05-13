<script setup>
import WelcomeItem from './WelcomeItem.vue'
import DocumentationIcon from './icons/IconDocumentation.vue'
import ToolingIcon from './icons/IconTooling.vue'
import EcosystemIcon from './icons/IconEcosystem.vue'
import CommunityIcon from './icons/IconCommunity.vue'
import SupportIcon from './icons/IconSupport.vue'
</script>

<template>
  <div class="row bg-secondary-subtle">
    <div class="item">
      <h3>浣溪沙（山下蘭芽短浸溪） <small class="text-secondary"><span>[宋]</span> <span>蘇軾</span></small></h3>
      <p>
        Spacing utilities that apply to all breakpoints, from xs to xxl, have no breakpoint abbreviation in them. This is because those classes are applied from min-width: 0 and up, and thus are not bound by a media query. The remaining breakpoints, however, do include a breakpoint abbreviation.
      </p>
    </div>
  </div>
</template>
