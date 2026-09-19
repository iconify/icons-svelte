<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t4xhpyb2w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="t4xhpyb2w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon-plain:stackoverflow" {...props}></Icon>
