<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="eqc7zybux"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:screen-search-desktop-outline-sharp" {...props}></Icon>
<style>
:global(.eqc7zybux) {
  fill: currentColor;
  d: path("m15.45 15.05l1.1-1.05l-2.1-2.1q.275-.425.413-.9T15 10q0-1.475-1.037-2.488T11.5 6.5T9.037 7.513T8 10t1.038 2.488T11.5 13.5q.525 0 .988-.137t.912-.413zM11.5 12q-.825 0-1.412-.587T9.5 10t.588-1.412T11.5 8q.8 0 1.4.588T13.5 10t-.587 1.413T11.5 12M1 21v-2h22v2zm1-3V3h20v15zm2-2h16V5H4zm0 0V5z");
}

</style>
