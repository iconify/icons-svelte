<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qdfl0cm_e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="qdfl0cm_e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-freehand:video-game-360-vr" {...props}></Icon>
