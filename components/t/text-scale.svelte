<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w04sejcqd.css';
import '../../css/s/s_xkkcbkt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="w04sejcqd"/><path class="s_xkkcbkt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:text-scale" {...props}></Icon>
