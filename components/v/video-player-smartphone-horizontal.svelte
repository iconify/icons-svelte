<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y8pd40b5k.css';
import '../../css/y/ylglf9x3a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="y8pd40b5k"/><path class="ylglf9x3a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-freehand:video-player-smartphone-horizontal" {...props}></Icon>
