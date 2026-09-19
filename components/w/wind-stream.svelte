<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cmwis782f.css';
import '../../css/j/j52z7pbtj.css';
import '../../css/c/chhmubb1r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="cmwis782f"/><path class="j52z7pbtj"/><path class="chhmubb1r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:wind-stream" {...props}></Icon>
