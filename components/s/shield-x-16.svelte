<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nf80xcb_m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="nf80xcb_m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:shield-x-16" {...props}></Icon>
