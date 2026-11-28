<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fhq63ab0q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fhq63ab0q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:video-play" {...props}></Icon>
