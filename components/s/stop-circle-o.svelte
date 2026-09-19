<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sdt3dxbez.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1536,"height":1536};
const content = `<path class="sdt3dxbez"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa:stop-circle-o" {...props}></Icon>
