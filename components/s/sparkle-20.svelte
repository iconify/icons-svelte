<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m00v2ibis.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="m00v2ibis"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:sparkle-20" {...props}></Icon>
