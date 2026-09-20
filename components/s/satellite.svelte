<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hke452bww.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hke452bww"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:satellite" {...props}></Icon>
