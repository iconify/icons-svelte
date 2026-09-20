<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/apw_yjbts.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="apw_yjbts"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:spray-paint" {...props}></Icon>
