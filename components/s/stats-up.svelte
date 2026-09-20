<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tdo88m09q.css';
import '../../css/k/k3v_cudyg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":64,"height":64};
const content = `<path class="tdo88m09q"/><path class="k3v_cudyg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:stats-up" {...props}></Icon>
