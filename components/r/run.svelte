<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y1d4hcvwf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="y1d4hcvwf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="picon:run" {...props}></Icon>
