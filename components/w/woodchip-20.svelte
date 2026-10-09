<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zcuvsac6i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="zcuvsac6i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:woodchip-20" {...props}></Icon>
