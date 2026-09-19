<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kvj4naczm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1792,"height":1280};
const content = `<path class="kvj4naczm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa:youtube-play" {...props}></Icon>
