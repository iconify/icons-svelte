<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oy5egbc5m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="oy5egbc5m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:water-opacity" {...props}></Icon>
