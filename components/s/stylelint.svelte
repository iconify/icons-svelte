<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j51sodbls.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="j51sodbls"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:stylelint" {...props}></Icon>
