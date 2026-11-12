<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gx46o0t2b.css';
import '../../css/j/jud9kib8r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="gx46o0t2b"/><path class="jud9kib8r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:ticky-dark" {...props}></Icon>
