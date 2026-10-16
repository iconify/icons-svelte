<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/ndqwi9bcc.css';
import '../../css/h/h5s-pvbvf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="ndqwi9bcc"/><path class="h5s-pvbvf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:smartphone-charging-20-bold" {...props}></Icon>
