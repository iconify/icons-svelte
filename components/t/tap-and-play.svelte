<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o0ko1jb1z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":368,"height":480};
const content = `<path class="o0ko1jb1z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:tap-and-play" {...props}></Icon>
