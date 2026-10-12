<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="j0o-uwe0e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:sailboat-sharp" {...props}></Icon>
<style>
:global(.j0o-uwe0e) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M10.75 3.75V14.5h-7l.51-.86l5.98-10.03l.51-.86zm2.5 2v8.75h6.5l-.55-.83l-5.4-8.09l-.55-.83zm-10 11h17.5l-1.6 3.4l-.428 1.07l-1.152.03H6.43l-1.152-.03l-.428-1.07Z");
}

</style>
