<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x5k4ul-lc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="x5k4ul-lc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:skip-forward-20-bold" {...props}></Icon>
