<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gw5d_zbeu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gw5d_zbeu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:tunnel-outline" {...props}></Icon>
