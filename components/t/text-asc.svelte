<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ov2t5ibwt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":40,"height":40};
const content = `<path class="ov2t5ibwt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iwwa:text-asc" {...props}></Icon>
