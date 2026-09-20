<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k-e_1xbae.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k-e_1xbae"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:seatbelt" {...props}></Icon>
