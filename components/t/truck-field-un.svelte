<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vbabcib3n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="vbabcib3n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:truck-field-un" {...props}></Icon>
