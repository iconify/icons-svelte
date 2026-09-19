<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ujfs0bcgn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":344,"height":384};
const content = `<path class="ujfs0bcgn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:window-maximize" {...props}></Icon>
