<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fxj_3jtzx.css';
import '../../css/t/t18caz0-h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="fxj_3jtzx"/><path class="t18caz0-h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:warning-other" {...props}></Icon>
