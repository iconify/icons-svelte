<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f_vf0_b6s.css';
import '../../css/p/ph4zn2b4t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="f_vf0_b6s"/><path class="ph4zn2b4t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:smartphone-vibrate-20-bold" {...props}></Icon>
