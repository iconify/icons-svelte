<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wy2m2ubdb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="wy2m2ubdb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:rust" {...props}></Icon>
