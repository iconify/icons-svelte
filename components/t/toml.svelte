<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dhybq6bxs.css';
import '../../css/n/n5ithpbrj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="dhybq6bxs"/><path class="n5ithpbrj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:toml" {...props}></Icon>
