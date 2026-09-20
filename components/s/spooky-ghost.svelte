<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/idsrm2ssw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="idsrm2ssw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:spooky-ghost" {...props}></Icon>
