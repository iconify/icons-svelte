<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gxfrv-bud.css';
import '../../css/n/nw12yw8jj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="gxfrv-bud"/><path class="nw12yw8jj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:wave-height" {...props}></Icon>
