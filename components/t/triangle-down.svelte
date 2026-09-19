<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f2w5s5t3x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":432,"height":392};
const content = `<path class="f2w5s5t3x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:triangle-down" {...props}></Icon>
