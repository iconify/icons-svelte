<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c3s6o4b0m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="c3s6o4b0m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:sort-desc-16" {...props}></Icon>
