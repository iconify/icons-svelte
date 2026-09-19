<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f44evnslo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="f44evnslo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:vertical-fold" {...props}></Icon>
