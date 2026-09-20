<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="locgzqbjm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token-branded:zksync" {...props}></Icon>
<style>
:global(.locgzqbjm) {
  fill-rule: evenodd;
  d: path("m21 12l-5.106-4.498v3.296l-5.07 3.298l5.07.002V16.5zM3 12l5.106 4.5v-3.263l5.034-3.3l-5.032-.002V7.5z");
}

</style>
