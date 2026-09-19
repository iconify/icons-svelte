<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rt-e5pb0j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="rt-e5pb0j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:user-circle-fill-12" {...props}></Icon>
