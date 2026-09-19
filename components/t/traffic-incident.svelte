<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k8wtggbuj.css';
import '../../css/r/r7cq4bfcx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="k8wtggbuj"/><path class="r7cq4bfcx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:traffic-incident" {...props}></Icon>
