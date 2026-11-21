<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wv72ichwa.css';
import '../../css/r/r14-wv_-r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wv72ichwa"/><path class="r14-wv_-r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:screen-share-off-filled" {...props}></Icon>
