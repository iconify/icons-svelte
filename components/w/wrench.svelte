<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/csqsnnd9x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="csqsnnd9x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="raphael:wrench" {...props}></Icon>
