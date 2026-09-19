<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dxpc2vbsc.css';
import '../../css/p/p575c8b4f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":18,"height":16};
const content = `<path class="dxpc2vbsc"/><path class="p575c8b4f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icomoon-free:users" {...props}></Icon>
