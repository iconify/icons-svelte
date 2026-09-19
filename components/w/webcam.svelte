<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jl-yfk1zi.css';
import '../../css/y/ydy8y_b-w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jl-yfk1zi"/><path class="ydy8y_b-w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:webcam" {...props}></Icon>
