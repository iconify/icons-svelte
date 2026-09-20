<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sca9mvbzp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sca9mvbzp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:window-shutter-open" {...props}></Icon>
