<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dpy9ok0_d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dpy9ok0_d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:zdotai" {...props}></Icon>
