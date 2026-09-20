<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/ju98jybvi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="ju98jybvi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:tag-arrow-right-filled" {...props}></Icon>
