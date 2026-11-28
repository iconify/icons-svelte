<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gd9uvobdv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gd9uvobdv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:smartphone-refresh" {...props}></Icon>
