<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jo1e-7b4g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":512};
const content = `<path class="jo1e-7b4g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-brands:vnv" {...props}></Icon>
