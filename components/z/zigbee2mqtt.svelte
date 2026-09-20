<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y9__3c02i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="y9__3c02i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:zigbee2mqtt" {...props}></Icon>
