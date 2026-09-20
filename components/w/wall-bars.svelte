<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i72axjbac.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="i72axjbac"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="roentgen:wall-bars" {...props}></Icon>
