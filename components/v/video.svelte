<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/anvo63bjo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="anvo63bjo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:video" {...props}></Icon>
