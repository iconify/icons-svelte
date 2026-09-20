<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gxwxdtx4a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="gxwxdtx4a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-color:sort-descending" {...props}></Icon>
