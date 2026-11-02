<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r4ircgmnm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="r4ircgmnm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:vector-bezier-line" {...props}></Icon>
