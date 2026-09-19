<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yp5c0ubxx.css';
import '../../css/h/h5e9s-b1t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="yp5c0ubxx"/><path clip-rule="evenodd" class="h5e9s-b1t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cuida:tube-outline" {...props}></Icon>
