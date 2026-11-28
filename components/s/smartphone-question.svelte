<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vg_h37b8r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vg_h37b8r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:smartphone-question" {...props}></Icon>
