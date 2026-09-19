<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dmwpo3s4r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="dmwpo3s4r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dashicons:video-alt" {...props}></Icon>
