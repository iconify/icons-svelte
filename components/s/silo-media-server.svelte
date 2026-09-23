<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ew-sr1mcj.css';
import '../../css/m/my_ftigmx.css';
import '../../css/w/w1-6qwzkf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ew-sr1mcj"/><path class="my_ftigmx"/><path class="w1-6qwzkf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:silo-media-server" {...props}></Icon>
