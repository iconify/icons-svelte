<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e95yi8b2t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1200,"height":1200};
const content = `<path class="e95yi8b2t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="el:step-forward" {...props}></Icon>
