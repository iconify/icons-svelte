<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f5xtwkbfe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="f5xtwkbfe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cil:wifi-signal-3" {...props}></Icon>
