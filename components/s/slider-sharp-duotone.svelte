<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="izwey4bhr"/><path class="u9-miyjhj"/><path class="oq6cs3wpq"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:slider-sharp-duotone" {...props}></Icon>
<style>
:global(.cuyn6tgcc) {
  fill: currentColor;
}

:global(.izwey4bhr) {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M12 17V19H1V17H12ZM23 17V19H20V17H23ZM10 2C10.552 2 11 2.45 11 3V11C11 11.55 10.552 12 10 12H2C1.448 12 1 11.55 1 11V3C1 2.45 1.448 2 2 2H10Z");
}

:global(.oq6cs3wpq) {
  d: path("M17 14C19.209 14 21 15.79 21 18C21 20.21 19.209 22 17 22H15C12.791 22 11 20.21 11 18C11 15.79 12.791 14 15 14H17Z");
}

:global(.u9-miyjhj) {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M18 2C20.761 2 23 4.24 23 7C23 9.76 20.761 12 18 12C15.239 12 13 9.76 13 7C13 4.24 15.239 2 18 2Z");
}

</style>
