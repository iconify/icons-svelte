<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/r/rj-i8dbss.css';
import '../../css/w/w8x7sqqrp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<g class="ft5dv1b6b"><path clip-rule="evenodd" class="rj-i8dbss"/><path class="w8x7sqqrp"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:storybook-wordmark" {...props}></Icon>
