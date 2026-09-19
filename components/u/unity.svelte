<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cmm9_6bsx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="cmm9_6bsx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon-plain:unity" {...props}></Icon>
