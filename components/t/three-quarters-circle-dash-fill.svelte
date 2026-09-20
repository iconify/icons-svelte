<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b_ybpbcve.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b_ybpbcve"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:three-quarters-circle-dash-fill" {...props}></Icon>
