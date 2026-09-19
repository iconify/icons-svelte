<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iqf5m3bbu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="iqf5m3bbu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:signal-3" {...props}></Icon>
