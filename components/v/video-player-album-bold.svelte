<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gmmar6b6n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gmmar6b6n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:video-player-album-bold" {...props}></Icon>
