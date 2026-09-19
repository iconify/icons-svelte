<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lm24th03j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="lm24th03j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:street-view" {...props}></Icon>
