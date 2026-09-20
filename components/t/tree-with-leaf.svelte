<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j5_bhwb0y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="j5_bhwb0y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="roentgen:tree-with-leaf" {...props}></Icon>
