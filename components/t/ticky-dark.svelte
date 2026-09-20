<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gx46o0t2b.css';
import '../../css/z/zbzbr2c9t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="gx46o0t2b"/><path class="zbzbr2c9t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:ticky-dark" {...props}></Icon>
