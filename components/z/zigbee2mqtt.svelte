<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vt-jrsb1y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vt-jrsb1y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:zigbee2mqtt" {...props}></Icon>
