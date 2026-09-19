<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jl656ybke.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="jl656ybke"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ant-design:truck-filled" {...props}></Icon>
