<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l_an3wpxx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="l_an3wpxx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:smoke-detector-off-outline" {...props}></Icon>
