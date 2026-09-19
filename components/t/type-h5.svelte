<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q37h1n4jn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="q37h1n4jn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:type-h5" {...props}></Icon>
