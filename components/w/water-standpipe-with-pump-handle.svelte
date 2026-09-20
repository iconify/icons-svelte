<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o2gwocbva.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="o2gwocbva"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:water-standpipe-with-pump-handle" {...props}></Icon>
