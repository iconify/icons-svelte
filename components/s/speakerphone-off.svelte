<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/og908q8dt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="og908q8dt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:speakerphone-off" {...props}></Icon>
