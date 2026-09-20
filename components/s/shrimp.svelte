<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/ww5e5e7-f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="ww5e5e7-f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="picon:shrimp" {...props}></Icon>
