<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h_l8cd96n.css';
import '../../css/y/yo_3w-v9d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="h_l8cd96n"/><path class="yo_3w-v9d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:user-x-20-bold" {...props}></Icon>
