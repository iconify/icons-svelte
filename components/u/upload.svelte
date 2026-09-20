<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pa3cnv-4o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":22,"height":22};
const content = `<path class="pa3cnv-4o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="memory:upload" {...props}></Icon>
