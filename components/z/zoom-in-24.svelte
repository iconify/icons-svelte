<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lc15x1w_o.css';
import '../../css/s/scnvldbzx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lc15x1w_o"/><path class="scnvldbzx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:zoom-in-24" {...props}></Icon>
