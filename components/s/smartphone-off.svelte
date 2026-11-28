<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g0bo2fi3v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="g0bo2fi3v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:smartphone-off" {...props}></Icon>
