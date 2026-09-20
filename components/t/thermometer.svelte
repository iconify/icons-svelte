<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wh3k1sbwv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wh3k1sbwv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:thermometer" {...props}></Icon>
