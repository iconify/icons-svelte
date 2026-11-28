<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zz3ht99ey.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="zz3ht99ey"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pullo:satellite-thin" {...props}></Icon>
