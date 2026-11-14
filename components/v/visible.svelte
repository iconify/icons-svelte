<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a1vk07bsc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-solid:visible" {...props}></Icon>
<style>
:global(.a1vk07bsc) {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M12 4.75q-6.532 0-10.164 6.901q-.042.08-.064.169T1.75 12t.022.18t.064.169Q5.468 19.25 12 19.25t10.164-6.901q.042-.08.064-.169t.022-.18t-.022-.18t-.064-.169Q18.532 4.75 12 4.75M8.25 12q0-3.75 3.75-3.75T15.75 12T12 15.75T8.25 12");
}

</style>
