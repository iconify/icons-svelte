<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bb7tl124z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="bb7tl124z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:webgl" {...props}></Icon>
