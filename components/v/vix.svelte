<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="zwh0ceb2g"/><path class="hdotsrl_o"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token-branded:vix" {...props}></Icon>
<style>
:global(.ft5dv1b6b) {
  fill: none;
}

:global(.hdotsrl_o) {
  fill: var(--svg-color--32b5e1, #32b5e1);
  d: path("M14.25 20.158L21 3.878c-3.19-.382-5.389 2.397-6.565 5.271L9.75 20.158z");
}

:global(.zwh0ceb2g) {
  fill: var(--svg-color--bde6f3, #bde6f3);
  d: path("M9.188 20.158L3 3.878c3.19-.382 5.389 2.397 6.565 5.271l4.686 11.009z");
}

</style>
