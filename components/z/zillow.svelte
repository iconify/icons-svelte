<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w38-p04fw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="w38-p04fw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cib:zillow" {...props}></Icon>
