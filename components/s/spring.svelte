<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mvp6aebxd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="mvp6aebxd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon-plain:spring" {...props}></Icon>
