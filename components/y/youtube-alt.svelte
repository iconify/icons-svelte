<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vayekvf8d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vayekvf8d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:youtube-alt" {...props}></Icon>
