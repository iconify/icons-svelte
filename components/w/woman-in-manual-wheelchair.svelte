<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gm9294b3s.css';
import '../../css/x/x4t5v5w5k.css';
import '../../css/s/s4m1sv55m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="gm9294b3s"/><path class="x4t5v5w5k"/><path class="s4m1sv55m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-emoji-high-contrast:woman-in-manual-wheelchair" {...props}></Icon>
