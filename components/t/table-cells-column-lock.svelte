<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nbv4uiyrx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="nbv4uiyrx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:table-cells-column-lock" {...props}></Icon>
