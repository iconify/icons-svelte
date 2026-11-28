<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hs6me8b2a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hs6me8b2a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:smartphone-check" {...props}></Icon>
