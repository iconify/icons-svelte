<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/phmruwb5f.css';
import '../../css/r/r5_089bbx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="phmruwb5f"/><path class="r5_089bbx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:youtube-watcher-light" {...props}></Icon>
