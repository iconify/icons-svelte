<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fwe5dkr3d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="fwe5dkr3d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:thumbs-down" {...props}></Icon>
