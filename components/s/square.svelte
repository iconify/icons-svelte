<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/apoqu8bds.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="apoqu8bds"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="at-icons:square" {...props}></Icon>
