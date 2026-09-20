<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c_jl0xt4l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="c_jl0xt4l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex:target-dollar-solid" {...props}></Icon>
