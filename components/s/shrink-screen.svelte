<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v3c_78bkn.css';
import '../../css/v/v758r-tyc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="v3c_78bkn"/><path class="v758r-tyc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:shrink-screen" {...props}></Icon>
