<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zg2pkyu3c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="zg2pkyu3c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="nimbus:tools" {...props}></Icon>
