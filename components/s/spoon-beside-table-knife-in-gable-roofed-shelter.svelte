<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c_2_1m9-s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="c_2_1m9-s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:spoon-beside-table-knife-in-gable-roofed-shelter" {...props}></Icon>
