<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/njrf_nrvd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="njrf_nrvd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="maki:telephone" {...props}></Icon>
