<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/grheaacqj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="grheaacqj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-brands:ups" {...props}></Icon>
