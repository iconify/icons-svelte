<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mvsu1r03w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1920,"height":1792};
const content = `<path class="mvsu1r03w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa:shower" {...props}></Icon>
