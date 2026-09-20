<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oam1m3jkt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="oam1m3jkt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:shul-outline" {...props}></Icon>
