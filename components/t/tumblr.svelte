<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/ptkw2rnlp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":320,"height":512};
const content = `<path class="ptkw2rnlp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-brands:tumblr" {...props}></Icon>
