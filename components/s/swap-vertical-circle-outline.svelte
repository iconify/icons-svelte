<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tljny4ckc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tljny4ckc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:swap-vertical-circle-outline" {...props}></Icon>
