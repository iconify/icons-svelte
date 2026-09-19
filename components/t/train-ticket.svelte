<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zkaoz6bjf.css';
import '../../css/o/oztuellfc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="zkaoz6bjf"/><path class="oztuellfc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:train-ticket" {...props}></Icon>
