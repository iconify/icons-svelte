<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h1v3__bro.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="h1v3__bro"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:weight" {...props}></Icon>
