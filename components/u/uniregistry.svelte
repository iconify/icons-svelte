<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k618ejbth.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="k618ejbth"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-brands:uniregistry" {...props}></Icon>
