<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pvz2snqgx.css';
import '../../css/g/gulcoab9z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="pvz2snqgx"/><path class="gulcoab9z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:sand-battery-20" {...props}></Icon>
