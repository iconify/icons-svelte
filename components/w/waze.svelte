<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vns7f7bfj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="vns7f7bfj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-brands:waze" {...props}></Icon>
