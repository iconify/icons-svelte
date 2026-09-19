<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ylpoqbbdx.css';
import '../../css/k/klf1_rboj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="ylpoqbbdx"/><path class="klf1_rboj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:screen-map" {...props}></Icon>
