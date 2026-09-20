<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/ppk8ufbgj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ppk8ufbgj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:surfboard-line" {...props}></Icon>
