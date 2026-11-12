<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wtwl263qg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="wtwl263qg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:shaarli-light" {...props}></Icon>
