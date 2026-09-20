<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/durr5709b.css';
import '../../css/i/ibed8bc7x.css';
import '../../css/f/f30-13bws.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="durr5709b"/><path class="ibed8bc7x"/><path class="f30-13bws"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-freehand:waiting-room-clock" {...props}></Icon>
