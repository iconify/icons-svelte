<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ye4bivxcv.css';
import '../../css/u/uq7ud8o0q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ye4bivxcv"/><path class="uq7ud8o0q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="prime:wifi" {...props}></Icon>
