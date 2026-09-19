<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r4_czfbpz.css';
import '../../css/u/uhn9qnbwc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="r4_czfbpz"/><path class="uhn9qnbwc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="formkit:settings" {...props}></Icon>
