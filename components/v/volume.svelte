<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d80jiwb1a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="d80jiwb1a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="picon:volume" {...props}></Icon>
