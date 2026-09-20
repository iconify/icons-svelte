<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hbh9tiw4m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="hbh9tiw4m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:text-alginment-justified" {...props}></Icon>
