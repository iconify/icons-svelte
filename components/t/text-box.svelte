<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mbwhfm2cv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":22,"height":22};
const content = `<path class="mbwhfm2cv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="memory:text-box" {...props}></Icon>
