<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y5hw2bbps.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="y5hw2bbps"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon-plain:zsh" {...props}></Icon>
