<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oe94j3tcg.css';
import '../../css/u/u-hablz3s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="oe94j3tcg"/><path class="u-hablz3s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:succession" {...props}></Icon>
