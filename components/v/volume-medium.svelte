<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rx_e1l.css';
import '../../css/d/dbz4uw.css';
import '../../css/s/so-from-34.css';
import '../../css/d/d-u-uo_p.css';
import '../../css/d/d-5-a1ir.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rx_e1l"/><path class="dbz4uw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="line-md:volume-medium" {...props}></Icon>
