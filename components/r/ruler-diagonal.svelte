<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ijdv2nm9r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ijdv2nm9r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:ruler-diagonal" {...props}></Icon>
