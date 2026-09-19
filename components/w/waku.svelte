<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z0isaxfvi.css';
import '../../css/z/znm6qw9zy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="z0isaxfvi"/><path class="znm6qw9zy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:waku" {...props}></Icon>
