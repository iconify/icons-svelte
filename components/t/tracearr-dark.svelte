<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dyzg-tbfy.css';
import '../../css/b/baziz2k_k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="dyzg-tbfy"/><path class="baziz2k_k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:tracearr-dark" {...props}></Icon>
