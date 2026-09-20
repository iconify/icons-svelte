<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pms0pobwl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pms0pobwl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:wave-line" {...props}></Icon>
