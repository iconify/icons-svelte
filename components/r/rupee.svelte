<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d47xi2b9o.css';
import '../../css/h/hgmaekite.css';
import '../../css/m/m5asxrbxd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="d47xi2b9o"/><path class="hgmaekite"/><path class="m5asxrbxd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="formkit:rupee" {...props}></Icon>
