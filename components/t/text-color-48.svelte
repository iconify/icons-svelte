<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fdnq6pbqs.css';
import '../../css/i/i4drks1lj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="fdnq6pbqs"/><path class="i4drks1lj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:text-color-48" {...props}></Icon>
