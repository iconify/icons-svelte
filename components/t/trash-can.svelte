<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iore6cbkm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="iore6cbkm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:trash-can" {...props}></Icon>
