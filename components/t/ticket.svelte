<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vp_aarktq.css';
import '../../css/u/uy9bf6bqn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":100,"height":100};
const content = `<path class="vp_aarktq"/><path class="uy9bf6bqn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="foundation:ticket" {...props}></Icon>
