<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xbno5b9ah.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xbno5b9ah"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:street-road-filled" {...props}></Icon>
