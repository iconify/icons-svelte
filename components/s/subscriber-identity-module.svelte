<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/ry4jo_b0p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ry4jo_b0p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:subscriber-identity-module" {...props}></Icon>
