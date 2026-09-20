<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h3o-hk-9l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="h3o-hk-9l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:travel-wayfinder-stairs-2-stairs-staircase-left" {...props}></Icon>
