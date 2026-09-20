<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/prptthbtt.css';
import '../../css/w/wu4g6i-qu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="prptthbtt"/><path class="wu4g6i-qu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:teslamate" {...props}></Icon>
