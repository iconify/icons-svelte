<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m7cjqrbqv.css';
import '../../css/f/fq4_qkb3m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":72,"height":72};
const content = `<path class="m7cjqrbqv"/><path class="fq4_qkb3m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="openmoji:white-heart" {...props}></Icon>
