<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="xt41kvbyw"><path class="p888sqb4d"/><path class="rs-8xcc2v"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token-branded:xvg" {...props}></Icon>
<style>
:global(.p888sqb4d) {
  d: path("M17.226 3L12 15.774L6.774 3H4.452L12 21l7.55-18z");
}

:global(.rs-8xcc2v) {
  d: path("M12 9.715L14.903 3H9.097z");
}

:global(.xt41kvbyw) {
  fill: var(--svg-color--34bde2, #34bde2);
}

</style>
