<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xd5rz4sgs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xd5rz4sgs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:timeline" {...props}></Icon>
