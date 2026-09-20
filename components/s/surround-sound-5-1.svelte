<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e8l01g8ad.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e8l01g8ad"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:surround-sound-5-1" {...props}></Icon>
