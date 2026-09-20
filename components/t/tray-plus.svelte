<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o336t47vq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="o336t47vq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:tray-plus" {...props}></Icon>
