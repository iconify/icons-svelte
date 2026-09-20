<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hc3uy0b4d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hc3uy0b4d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:user-badge-outline" {...props}></Icon>
