<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/knbra1tuf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="knbra1tuf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:tshirt-crew-outline" {...props}></Icon>
