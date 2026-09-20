<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m0ub5pikl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m0ub5pikl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:toggle-switch-off-outline" {...props}></Icon>
