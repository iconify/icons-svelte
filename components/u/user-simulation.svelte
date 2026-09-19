<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mz2q2c5nh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="mz2q2c5nh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:user-simulation" {...props}></Icon>
