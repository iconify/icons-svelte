<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vhg4i7byd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vhg4i7byd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:zig" {...props}></Icon>
