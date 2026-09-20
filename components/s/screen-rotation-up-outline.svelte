<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xx2z4so5p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:screen-rotation-up-outline" {...props}></Icon>
<style>
:global(.xx2z4so5p) {
  fill: currentColor;
  d: path("m13.75 23.25l-1.4-1.425L14.175 20H8q-.825 0-1.412-.587T6 18V7.825l2 2V18h6.175l-1.825-1.825l1.4-1.425L18 19zM18 16.175l-2-2V6H9.825l1.825 1.825l-1.4 1.425L6 5L10.25.75l1.4 1.425L9.825 4H16q.825 0 1.413.588T18 6z");
}

</style>
