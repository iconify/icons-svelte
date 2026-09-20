<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hgc8pk4bh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hgc8pk4bh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:send-variant-clock" {...props}></Icon>
