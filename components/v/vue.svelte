<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j1m2x9bvi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="j1m2x9bvi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="picon:vue" {...props}></Icon>
