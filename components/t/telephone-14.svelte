<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l4-bzk02u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="l4-bzk02u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="osmic:telephone-14" {...props}></Icon>
