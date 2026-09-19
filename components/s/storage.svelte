<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jdytr4pqu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="jdytr4pqu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="at-icons:storage" {...props}></Icon>
