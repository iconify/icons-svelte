<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i8m49d65q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="i8m49d65q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:skip-backward-16" {...props}></Icon>
