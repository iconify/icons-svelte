<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r2i76-b5v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":29,"height":32};
const content = `<path class="r2i76-b5v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="et:streetsign" {...props}></Icon>
