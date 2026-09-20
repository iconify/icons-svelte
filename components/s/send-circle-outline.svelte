<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sljpikbin.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sljpikbin"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:send-circle-outline" {...props}></Icon>
