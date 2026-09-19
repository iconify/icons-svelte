<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e73x-3b6j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="e73x-3b6j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon-plain:wasm-wordmark" {...props}></Icon>
