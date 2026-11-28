<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qpc_mmbiz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qpc_mmbiz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:wand-check" {...props}></Icon>
