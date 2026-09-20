<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/np_xkiena.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="np_xkiena"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:vlc-media-player" {...props}></Icon>
