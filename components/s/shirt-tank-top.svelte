<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/ql8bb5b0h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ql8bb5b0h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:shirt-tank-top" {...props}></Icon>
