<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jl_1o55vc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jl_1o55vc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:settings-6-line" {...props}></Icon>
