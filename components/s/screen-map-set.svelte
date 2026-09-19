<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gkb7xobyc.css';
import '../../css/a/avbzggl1s.css';
import '../../css/l/l6u_258ql.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="gkb7xobyc"/><path class="avbzggl1s"/><path class="l6u_258ql"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:screen-map-set" {...props}></Icon>
