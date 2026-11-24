<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s1b0gzbhk.css';
import '../../css/l/lva836zoc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="s1b0gzbhk"/><path class="lva836zoc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:typestash-dark" {...props}></Icon>
