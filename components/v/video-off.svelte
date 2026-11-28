<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ew5jinb1p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ew5jinb1p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:video-off" {...props}></Icon>
