<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fw8dmrebl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1664,"height":1728};
const content = `<path class="fw8dmrebl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa:spinner" {...props}></Icon>
