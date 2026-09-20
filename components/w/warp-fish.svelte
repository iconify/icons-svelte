<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jl2tvfctu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jl2tvfctu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:warp-fish" {...props}></Icon>
