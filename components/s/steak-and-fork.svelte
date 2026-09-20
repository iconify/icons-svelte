<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m5ndsbo2i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="m5ndsbo2i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="roentgen:steak-and-fork" {...props}></Icon>
