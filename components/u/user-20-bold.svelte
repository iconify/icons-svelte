<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pn-vy1b2g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="pn-vy1b2g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:user-20-bold" {...props}></Icon>
