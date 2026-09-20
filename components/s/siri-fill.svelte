<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pnku-pbna.css';
import '../../css/s/sqo3g6whm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pnku-pbna"/><path class="sqo3g6whm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:siri-fill" {...props}></Icon>
