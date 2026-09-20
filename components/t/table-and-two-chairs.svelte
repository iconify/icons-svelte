<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/omeljc3-r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="omeljc3-r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="roentgen:table-and-two-chairs" {...props}></Icon>
