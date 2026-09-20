<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mg5l5wb2n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mg5l5wb2n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:smartphone-settings" {...props}></Icon>
