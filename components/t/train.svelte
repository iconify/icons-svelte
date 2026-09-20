<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sz6sfydxf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sz6sfydxf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:train" {...props}></Icon>
