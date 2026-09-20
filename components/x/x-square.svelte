<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rfa3zybio.css';
import '../../css/s/so8u7503r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rfa3zybio"/><path class="so8u7503r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mage:x-square" {...props}></Icon>
