<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y_07w6bdi.css';
import '../../css/s/s2rg5k4vy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="y_07w6bdi"/><path class="s2rg5k4vy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:welding-mask-20" {...props}></Icon>
