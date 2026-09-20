<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j3u6_3b8i.css';
import '../../css/f/fg0j46bvq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="j3u6_3b8i"/><path class="fg0j46bvq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uim:sync-exclamation" {...props}></Icon>
