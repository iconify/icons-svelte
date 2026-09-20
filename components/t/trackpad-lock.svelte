<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nt1ol5ibt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nt1ol5ibt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:trackpad-lock" {...props}></Icon>
