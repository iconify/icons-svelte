<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ohq7uzbwc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ohq7uzbwc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:utensils" {...props}></Icon>
