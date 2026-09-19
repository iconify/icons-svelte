<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vfpp4qbmp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="vfpp4qbmp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:tensorflow" {...props}></Icon>
