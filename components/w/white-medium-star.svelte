<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":64,"height":64};
const content = `<path class="h4gt3jbaf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="emojione:white-medium-star" {...props}></Icon>
<style>
:global(.h4gt3jbaf) {
  fill: var(--svg-color--ffce31, #ffce31);
  d: path("M62 25.2H39.1L32 3l-7.1 22.2H2l18.5 13.7l-7 22.1L32 47.3L50.5 61l-7.1-22.2z");
}

</style>
