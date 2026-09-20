<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w1ef6tblq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w1ef6tblq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:solar-compass" {...props}></Icon>
