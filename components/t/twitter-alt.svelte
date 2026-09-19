<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hr92bcb3d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="hr92bcb3d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dashicons:twitter-alt" {...props}></Icon>
