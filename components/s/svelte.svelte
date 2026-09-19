<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s61fxyb8s.css';
import '../../css/t/tyum8jbog.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="s61fxyb8s"/><path class="tyum8jbog"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:svelte" {...props}></Icon>
