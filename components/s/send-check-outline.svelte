<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/darsq7b4j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="darsq7b4j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:send-check-outline" {...props}></Icon>
