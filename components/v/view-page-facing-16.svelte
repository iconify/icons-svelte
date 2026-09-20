<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d3jjpgbqp.css';
import '../../css/r/rvcx90b2h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="d3jjpgbqp"/><path clip-rule="evenodd" class="rvcx90b2h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:view-page-facing-16" {...props}></Icon>
