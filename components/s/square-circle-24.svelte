<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lbiaezbeq.css';
import '../../css/u/uy-3x3bjx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lbiaezbeq"/><path class="uy-3x3bjx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:square-circle-24" {...props}></Icon>
